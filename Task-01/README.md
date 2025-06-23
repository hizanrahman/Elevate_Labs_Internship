# TASK 1: Scan Your Local Network for Open Ports

## Objective

Learn to discover open ports on devices in your local network to understand network exposure.



## Local IP Range

** 192.168.1.0/24



## TCP SYN Scan
** nmap -sS 192.168.1.0/24


## Scan Results

### IP Addresses & Open Ports Found

| IP Address     | Open Ports       |
|----------------|------------------|
| 192.168.1.1    | 53, 80           |
| 192.168.1.2    | 80               |
| 192.168.1.3    | 8009             |
| 192.168.1.5    | -                |
| 192.168.1.6    | 49152, 62078     |
| 192.168.1.8    | 1309             |
| 192.168.1.9    | -                |
| 192.168.1.12   | -                |

---

## Common Services Running on Ports

| Port Number | Common Service         |
|-------------|------------------------|
| 53          | DNS                    |
| 80          | HTTP                   |
| 8009        | Apache JServ Protocol (AJP) |
| 49152       | Windows RPC Dynamic Ports |
| 62078       | Apple iTunes Sync Service |
| 1309        | GWMP (Gateway Management Protocol) |

---

## Analysing Packets Captured in Wireshark

[Click here to view the Wireshark screenshot](https://github.com/your-repo-name/path-to-screenshot.png)



---
