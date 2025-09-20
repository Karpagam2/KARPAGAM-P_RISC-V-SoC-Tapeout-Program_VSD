# RISC-V SoC Tapeout Program VSD

# Tools Installation

**All the instructions for installation of required tools can be found here**  

---

## System Requirements
- 6 GB RAM
- 50 GB HDD
- Ubuntu 20.04 or higher
- 4 vCPU

---

# TOOL CHECK: Yosys

```bash
$ sudo apt-get update
$ git clone https://github.com/YosysHQ/yosys.git
$ cd yosys
$ sudo apt install make
$ sudo apt-get install build-essential clang bison flex \
    libreadline-dev gawk tcl-dev libffi-dev git \
    graphviz xdot pkg-config python3 libboost-system-dev \
    libboost-python-dev libboost-filesystem-dev zlib1g-dev
$ make config-gcc
$ make
$ sudo make install
```

# TOOL CHECK: IVerilog
```bash
$ sudo apt-get update
$ sudo apt-get install iverilog
```

# TOOL CHECK: GTKWave
```bash
$ sudo apt-get update
$ sudo apt install gtkwave
```
