# 🐉Cybersecurity Lab Environment Setup
---
### 1. My Laptop Specification
* Processor	Intel(R) Celeron(R) N4120 CPU @ 1.10GHz   1.10 GHz
* Installed RAM	4.00 GB (3.82 GB usable)
* System type	64-bit operating system, x64-based processor
* Pen and touch	No pen or touch input is available for this display

### 2. My Lab Architecture
  
![My virtual machine](<Screenshot 2026-10-26 192136.png>)

### 3. Installation Steps 
- Open VirtualBox > Machine > click on "Add"
- Select `kali-linux-2026.2-virtualbox-amd64.ova`
- The importing process takes about 5 minutes
- Go to File > Tools > Network Manager.
- Create a new NAT Network using ipv4 address: 10.0.0.0/24
- Enable network adapter to the NAT Network (the one i have created)
- Start the virtual machine and login to kali Linux
- Edit the Wired Connection

### 4. IP Verification and Connectivity Test
- Open the terminal
- Type `ip a` to ip address
![ip address](<Screenshot 2026-10-26 191251.png>)
- Type `ping Your Linux ip` (mine is 10.0.0.2)  
![connection test](<Screenshot 2026-10-26 191819.png>)  

### 6. My Real Problem
> I could not use the internet to browser, so i use 3 commands given to us and it work very great.

![3 help tips](<Screenshot 2026-10-26 151952.png>)
![youtube](<Screenshot 2026-10-26 152530.png>)

