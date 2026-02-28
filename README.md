# Network Security & Pentesting Tools

A comprehensive collection of Python scripts designed for network exploration, security auditing, and protocol manipulation. This repository contains custom implementations of classic networking tools and specialized security scripts.

## 🚀 Overview

This project for network engineers and security researchers. It covers from low-level TCP/UDP communication to advanced techniques like ARP spoofing.

## 🛠️ Tools & Features

### Core Networking

* `netcat.py`: A modern Python light weight classic Netcat.
* `tcp_server.py` / `tcp_client.py`: Standard implementations for TCP communication.
* `udp_client.py`: Lightweight client for UDP-based data transmission.
* `proxy.py`: A multi-threaded TCP proxy for monitoring and intercepting traffic between a client and a remote host.

### Sniffing & Analysis

* **`simple_sniffer.py`**: Basic packet capture tool.
* **`mail_sniffer.py`**: Specifically designed to intercept and log email credentials and data.
* **`sniffer_ip_header.py`**: Decodes and displays IP header information from captured packets.

### Remote Access & Exploitation

* **`ssh_cmd.py` / `ssh_server.py**`: Tools for executing commands over SSH and setting up custom SSH server environments.
* **`arper.py`**: A powerful ARP cache poisoning tool to facilitate Man-in-the-Middle (MitM) attacks.
* **`scanner.py`**: A network scanner to identify active hosts and open ports.



## ⚠️ Disclaimer

This repository is for **educational and ethical security testing purposes only**. Unauthorized access to networks or systems is illegal. The author is not responsible for any misuse of these tools. Always ensure you have explicit permission before testing on any network.

---

### How to use this

1. Clone the repo: `git clone https://github.com/omarahmedxp/network.git`
2. Navigate to the tool you need.
3. Run with sudo/admin privileges (required for raw sockets and sniffing):
```bash
sudo python3 arper.py [targets]

```

