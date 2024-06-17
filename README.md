
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
## Network Topology
## This is the basic setup of my Topology. The two virtual machines I used were Windows server 2019 and Windows 10 Pro. I decided to configure it as an Internal Network instead of the default NAT configuration so the environment could be excluded from communicating with any other devices.
 ![image](https://github.com/TolantioGanzi/Active-Directory-Lab/assets/172088474/24504448-e488-4831-bcaf-70f6071c19ac)


## Changed the name of my Domain Controller for the Active Directory server to DC1
 ![image](https://github.com/TolantioGanzi/Active-Directory-Lab/assets/172088474/670f1a6c-6bf5-4b9d-b4cb-ae82b1908990)


## For this purpose of this lab and the limitations of my current hardware I added Active Directory and DNS role to the Server. 
![Adding-DNS-AD](https://github.com/TolantioGanzi/Active-Directory-Lab/assets/172088474/5089d147-719e-43c4-8874-1352949c9a58)




## Finished Configuring the Domain Controller and created the new forest. 
  ![creating-forest](https://github.com/TolantioGanzi/Active-Directory-Lab/assets/172088474/f3c8491f-2476-46ca-8d77-546cc7e93a04)

## DC Created
![picture-of-dc-after-restart](https://github.com/TolantioGanzi/Active-Directory-Lab/assets/172088474/16e92657-e1da-44e4-b628-dd3ed843451a)






## The next step of this lab was to create new users in the AD. To best mimick a real life environment I disabled the guest account to reduce the risk of a security breach since that is an account that attackers tend to see as an easy way into an organization's network.
 ![Disable-guest-accouont](https://github.com/TolantioGanzi/Active-Directory-Lab/assets/172088474/0ca3d657-b325-45d3-a562-ee8201f525ec)


## I created a new user using my credentials and added this user to the Administrator group in the Active Directory. By adding this user to this group, it gives it full control over the operating system. 
 ![creating-new-user](https://github.com/TolantioGanzi/Active-Directory-Lab/assets/172088474/6a848914-86f2-480f-886f-61f25bd871b8)
![creating-new-user2](https://github.com/TolantioGanzi/Active-Directory-Lab/assets/172088474/72025f64-f043-423f-8b38-a3e35d258b95)
![adding-tganzi-to-admin-group](https://github.com/TolantioGanzi/Active-Directory-Lab/assets/172088474/7947fedc-fd0b-41de-a476-ea1903ae9ca1)



## I created an organization unit called "SOC" team that's going to server as a container in the active directory for Security of Operations Center employees. I created a generic user and added it to the OU. 
![creating-ou](https://github.com/TolantioGanzi/Active-Directory-Lab/assets/172088474/60514066-a938-4f9c-ad42-d44e0c7c2407)
![adding-user-to-ou](https://github.com/TolantioGanzi/Active-Directory-Lab/assets/172088474/3556e9cc-daae-4b2f-a0f5-74fc56aff6c5)
![image](https://github.com/TolantioGanzi/Active-Directory-Lab/assets/172088474/2c8ba659-dfe6-4d23-ba9e-0bd9d7c8cc06)

## This is only part one of the Active Directory project, and I expect to explore a plethora of tools andconfigurations in order to strengeth my knowledge on AD and windows. 


## Adding Windows 10 Virtual Machine to Domain
-  Last part of this project is adding the Windows 10 Pro machine to the "ganzinetwork.com" domain. 
![image](https://github.com/TolantioGanzi/Active-Directory-Lab/assets/172088474/2e10bb46-9700-43e5-a0ac-214273985d07)
