
# Active Directory

## Objective

The Active Directory Lab is aimed to set up an Active Directory Home lab assignment and simulate administrating an organization's AD from a Help-Desk technician's point of view. Primary focus is to configure a domain controller and adding another Windows 10 environment to the domain and create Organizatinal Units (OUs)
### Skills Learned

- Setting up and Configuring an Active Directory in a very small scale.
- Adding roles and features to a Domain Controller
- Creating groups and adding users to it
- Creating Organizational Units.
- Adding a Windows 10 Machine to the domain created.

### Tools / Environments Used

- Oracle VirtualBox.
- Server 2019
- Windows 10 22H2
## Steps
- Network Topology
- This is the basic setup of my Topology. The two virtual machines I used were Windows server 2019 and Windows 10 Pro. I decided to configure it as an Internal Network instead of the default NAT configuration so the environment could be excluded from communicating with any other devices.
 ![image](https://github.com/TolantioGanzi/Active-Directory-Lab/assets/172088474/24504448-e488-4831-bcaf-70f6071c19ac)


- Changed the name of my Domain Controller for the Active Directory server to DC1
 ![image](https://github.com/TolantioGanzi/Active-Directory-Lab/assets/172088474/670f1a6c-6bf5-4b9d-b4cb-ae82b1908990)


-  Importing Roles into the Domain Controller



- Adding DNS, Active Directory, DHCP roles to DC1



- Establishing New Environment | Adding Forest



- Creating Users in "DC1"



- Disable Guest Account/Rename Administrator Account and explain why



- Adding user



- Setting User Account up with Password Policy Best practices



- Crreating a Group



- Adding User to Group



- Making a Finance Organizational Unit



- Add Finance Employee to OU Group



## Adding Windows 10 Virtual Machine to Domain
- Configuring IPV4 so VMs can communicate with eachother. 
