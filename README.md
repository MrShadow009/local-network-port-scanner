**# local-network-port-scanner**
Discover open ports and services running on devices in your local network using Nmap. This project demonstrates basic network reconnaissance techniques using Kali Linux for cybersecurity learning and analysis.
# 🔍 Nmap Network Scanning - Cyber Security Internship Task

## 📌 Objective
Perform basic network reconnaissance using **Nmap** to identify open ports and services on devices within a local or external network.

## 🛠 Tools Used
- **Nmap** (Network Mapper)
- **Kali Linux** (Operating System)

## 🧪 Tasks Performed

1. TCP SYN Scan on local network (`192.168.1.0/24`)
2. Service version detection on `scanme.nmap.org`
3. Specific port scan for ports `80,443`
4. Full range port scan (`-p 1-100`)
5. Saved output to `.txt` file

## 📂 Files Included

| File Name                  | Description                             |
|----------------------------|-----------------------------------------|
| `nmap_task_kali_linux.txt` | Contains all terminal commands, outputs |

## 📸 Screenshots
*(Add these before uploading to GitHub)*  
- Screenshot of each command being executed  
- Screenshot of scan results

## 📥 How to Run
```bash
# Basic SYN scan
nmap -sS 192.168.1.0/24

# Scan specific host with service detection
nmap -sV scanme.nmap.org

# Save output
nmap -sS 192.168.1.0/24 -oN scan_results.txt
