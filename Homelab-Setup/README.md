# Homelab Setup and Configuration
## Homelab Setup
My homelab is comprised of three virtual machines running on VirtualBox
### Server VM
OS: Windows Server 2022\
RAM: 6 GB\
CPU Cores: 2
### Client VM
OS: Windows 11\
RAM: 6 GB\
CPU Cores: 2
### Attack VM
OS: Kali Linux\
RAM: 6 GB\
CPU Cores: 2

*All VMs are hosted on VirtualBox and were configured using the standard setup process*

### Network Setup
All three VMs were configured with two network adapters
- The first adapter is configured as an internal network named *"LabNet"*
- The second adapter is confiured as NAT
