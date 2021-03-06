# Network scanner

> A small project that I wrote on the fly for (IT351) Computer Networks University Course to identify and label the devices in my networks and open ports.


# Technical Points
- Built using `python3` and for 
  - `main.py` file that used `socket` library for TCP Scanning which used three-way handshake (ACK-SYN)
  - `main-scapy.main` file that used `scapy` library for ARP Scanning which sends broadcast ARP message
- Built GUI with `PyQt5` library

## How to use

### Getting started
 1. clone or download the project and `cd` into the project folder
 2. install dependencies
    1. `pip install -r requirements.txt`

### How to run
1. run: `python main.py`, `python main-scapy.py` or from IDE like PyCharm
2. input network to scan: e.g. `192.168.1.1`

***Scanning could take a little while (around 20sec - 2min is normal). In addition, it may have to be run several times to get all devices.***

## Demo or What you will get
1. For running `main.py` file which scanning network using built in library `socket`

<p align="center" width="100%">
  <img src="https://github.com/aboelkassem/Network-Scanner/blob/master/images/main.jpg" width="500" hight="500"/>
</p>

2. For running `main-scapy.py` file which scanning network using library `scapy`

<p align="center" width="100%">
  <img src="https://github.com/aboelkassem/Network-Scanner/blob/master
  /images/main-scapy.jpg" width="500" hight="500"/>
</p>




