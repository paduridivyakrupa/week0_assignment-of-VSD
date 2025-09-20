# week0_assignment-of-VSD
# RISC-V Reference SoC Tapeout Program VSD

## Tools Installation

#### <ins>All the instructions for installation of required tools can be found here:</ins>

### **System Requirements**
- 6 GB RAM
- 50 GB HDD
- Ubuntu 20.04 or higher
- 4 vCPU

### **Resizing the Ubuntu window to fit the screen**
```bash
$ sudo apt update
$ sudo apt install build-essential dkms linux-headers-$(uname -r)
$ cd /media/spatha/VBox_GAs_7.1.8/
$ ./autorun.sh
```

### **TOOL CHECK**

#### <ins>**Yosys**</ins>
```bash
$ sudo apt-get update
$ git clone https://github.com/YosysHQ/yosys.git
$ cd yosys
$ sudo apt install make               # If make is not installed
$ sudo apt-get install build-essential clang bison flex \
    libreadline-dev gawk tcl-dev libffi-dev git \
    graphviz xdot pkg-config python3 libboost-system-dev \
    libboost-python-dev libboost-filesystem-dev zlib1g-dev
$ make config-gcc
# Yosys build depends on a Git submodule called abc, which hasn't been initialized yet. You need to run the following command before running make
$ git submodule update --init --recursive
$ make 
$ sudo make install
```
![Alt Text]<img width="713" height="196" alt="Screenshot from 2025-09-20 17-30-42" src="https://github.com/user-attachments/assets/72139897-3336-40d8-9802-8b74736d58a4" />


#### <ins>**Iverilog**</ins>
```bash
$ sudo apt-get update
$ sudo apt-get install iverilog
```
![Alt Text]<img width="725" height="219" alt="Screenshot from 2025-09-20 17-34-18" src="https://github.com/user-attachments/assets/ed3d8331-ccf5-4ba1-b9f8-fd67ca296e3e" />


#### <ins>**gtkwave**</ins>
```bash
$ sudo apt-get update
$ sudo apt install gtkwave
```
![Alt Text]<img width="704" height="124" alt="Screenshot from 2025-09-20 17-33-20" src="https://github.com/user-attachments/assets/38ea3041-4aaf-4224-b11d-ac9b77e78341" />


![Alt Text]<img<img width="1006" height="639" alt="Screenshot from 2025-09-20 17-33-41" src="https://github.com/user-attachments/assets/2e17947d-00a0-44f3-9bb0-b8b8f9b44f72" />
