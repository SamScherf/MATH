# MATH (Mathematical Ascribing Tool for Handwriting)

MATH is a tool for solving hand written mathematical expressions. This is a work in progress project and therefore not yet feature complete.

## Roadmap
- [ ] Digit Recognition
  - [ ] Proof of concept network
  - [ ] Natural numbers
  - [ ] Integers
  - [ ] Real numbers
  - [ ] Complex numbers
- [ ] Web Interface
  - [ ] Flexible outline of website
  - [ ] API based model deployment
  - [ ] JavaScript based model deployment
  - [ ] Public release
- [ ] Operation Recognition
  - [ ] Arithmetic
  - [ ] Simple Calculus

## Installation Instructions

### 1. Clone the repository

```
git clone https://github.com/SamScherf/MATH.git
cd MATH/
```

### 2. Install dependencies using Poetry

```
poetry install
```

### Troubleshooting

- NUMA node read from SysFS had negative value (-1)

  - A softfix for this is available [here](https://stackoverflow.com/questions/44232898/memoryerror-in-tensorflow-and-successful-numa-node-read-from-sysfs-had-negativ)
