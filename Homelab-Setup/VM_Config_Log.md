# Virtual Machine Configuration Log
## Windows Server 2022 VM
- Completed standard Windows Server 2022 OS install
- Installed all available Windows Updates
- Installed and configured VirtualBox Guest Additions
- Named system *DC01*
- Completed network settings
  - Set static IP of 10.0.0.10
  - Set subnet mask of 255.255.255.0
  - Set default gateway to 10.0.0.1
  - Set DNS to 10.0.0.10
- Installed AD DS in Server Manager
  - Promoted to domain controller
  - Named new Root domain *corp.local*
- Installed and configured DHCP in Server Manager
  - After install, option to choose New Scope was not available
  - Removed DHCP role in powershell
  - Reinstalled DHCP
  - Authorized DHCP server
- Created new scope
  - Name: LabScope
  - Start IP: 10.0.0.50
  - End IP: 10.0.0.200
  - Subnet Mask: 255.255.255.0
  - Router: 10.0.0.1
  - DNS: 10.0.0.10
## Windows 11 VM
- Completed standard Windows 11 OS install
- Installed all available Windows Updates
- Installed and configured VirtualBox Guest Additions
- Named system *WIN11-USER*
- Confirmed VM got an IP from DHCP: SUCCESS
- Connected VM to domain
##Kali Linux VM
- Completed standard Kali Linux OS install
- Ran all updated/upgrades
- Confirmed VM got in IP from DHCP: SUCCESS
##Misc
- Confirmed all three VM networks settings were configured properly and all three systems could communicate appropriately
