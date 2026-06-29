* Elevate Labs Internship - Task 1

* Objective

Scan the local network using Nmap to identify active devices and open ports.

* Tools Used

- Nmap
- Termux (Android)
- GitHub

* Scan Results

** Active Devices

- 192.168.1.1 (Router)
- 192.168.1.3
- 192.168.1.7 (Android Device)

** Open Ports

| Port | Service | State |
|------|---------|-------|
| 53 | DNS | Open |
| 80 | HTTP | Open |
| 443 | HTTPS | Open |

** Observation

The scan identified three active devices on the local network. The router had DNS, HTTP, and HTTPS services open, while FTP, SSH, and Telnet ports were filtered. The other devices did not expose open TCP ports.
I didn't hide the ip because it is private ip used by many devices.

* Author 

Vishal S K 
