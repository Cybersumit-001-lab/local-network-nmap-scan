# 🧩 Task 1: Scan Your Local Network for Open Ports

## 🎯 Objective
To discover open ports and running services in my local network using **Nmap**, and understand the possible security risks related to them.

---

## 🧰 Tools Used
- **Nmap** – for scanning ports and services  
- **Wireshark (optional)** – for analyzing network packets  
- **GitHub** – for saving and documenting the task

---

## 🪜 Steps Performed

1. **Installed Nmap**
   - On Kali Linux: `sudo apt install nmap -y`
   - On Windows: Downloaded from [https://nmap.org/download.html](https://nmap.org/download.html)

2. **Found Local IP Range**
   - Used `ipconfig` (Windows) or `ip addr show` (Linux)
   - My local range was `192.168.***.0/24`

3. **Performed a TCP SYN Scan**
   
   nmap -sS 192.168.***.0/24
