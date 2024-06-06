# Network-Sniffer-and-Spoofer
Network Scanner

Network Scanner
Overview
The Network Scanner is a Python tool designed to scan a network for devices and retrieve their IP and MAC addresses. It utilizes the Scapy library for crafting and sending ARP packets, allowing for efficient network discovery.

Features
IP Address Discovery: Scans the network to discover devices and retrieve their IP addresses.
MAC Address Retrieval: Retrieves the MAC addresses of discovered devices.
Flexible Usage: Supports specifying target IP addresses for customized scans.
Installation
Clone the repository:
bash
Copy code
git clone https://github.com/your-username/network-scanner.git
cd network-scanner
Install dependencies:
bash
Copy code
pip install scapy
Usage
Run the network_scanner.py script with the -t or --target option followed by the target IP address or addresses.
bash
Copy code
python network_scanner.py -t 192.168.1.1
Example
bash
Copy code
$ python network_scanner.py -t 192.168.1.1
-----------------------------------
IP Address     MAC Address
-----------------------------------
192.168.1.1    00:0c:29:2f:6a:db
192.168.1.2    00:0c:29:17:d2:7b
192.168.1.3    00:0c:29:57:62:7b
Contributing
Contributions are welcome! Please follow these steps to contribute:

Fork the repository.
Create a new branch (git checkout -b feature/new-feature).
Make your changes and commit them (git commit -am 'Add new feature').
Push to the branch (git push origin feature/new-feature).
Create a new Pull Request.
![NetworkScanner](https://github.com/Ashusharma246/Network-Sniffer-and-Spoofer/assets/102012643/7693de39-78e6-4f67-b136-0f9ec8b52cdd)
