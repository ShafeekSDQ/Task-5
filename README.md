# Task Five: Nmap Scan

This repository contains the results of an Nmap scan performed on the Metasploitable virtual machine. The purpose of this task was to install Metasploitable, perform a full port scan using Nmap.

## Steps Followed

### 1. Install Metasploitable
- **Downloaded Metasploitable2**: The virtual machine image was downloaded from [SourceForge](https://sourceforge.net/projects/metasploitable/files/Metasploitable2/).
- **Set Up the VM**: The Metasploitable2 VM was set up using VirtualBox/VMware with the following settings:
  - **OS Type**: Linux
  - **Version**: Linux 2.6/3.x/4.x/5.x (32-bit)
### 2. Perform an Nmap Scan of All Ports
- **IP Address**: The IP address of the Metasploitable VM was determined using  `ip a`.
- **Nmap Scan**: A full port scan was performed using the following command:
  ```bash
  nmap -p- [Metasploitable_IP]
### 3. Results
- The scan results were saved in a file named `task5.txt`.
- The file was then added to this GitHub repository.

