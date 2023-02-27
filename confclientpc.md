# Configuring Windows Client PC to join Active Directory (AD DS)

``It is recommended to first add the user to the Active Directory and then join the computer to the Domain.`` 

## Add User to Active Directory
> 1) Adding the USER to AD is done from a menu "Tools -> Active Directory Users and Computers"


Here you can add new Organization Units (OU) and/or Groups to the AD.

![](https://www.bachvarova.com/__git/install_windows_server_virtualbox/ad_add_usr.jpg)

## Organizational Units and Groups in Active Directory
>* **Organizational Units vs Groups In Active Directory**
> 
> Groups have SIDs, can be placed on access control lists, and can contain other groups (even the same type of group referred to as group nesting). 
> Organizational units do not have SIDs, can't be placed on an access control list, and can not be placed into a group.

>* **What is the difference between group and organizational units in Active Directory?**
> 
> The difference between an OU and a group is that OUs can contain different kinds of objects rather than being limited to accounts or groups, whereas groups can only contain accounts and other groups.

> Аdded a test user: 
> * "tedytest@domain.local" with the desired password and settings


## Client machine network status:

> After installation on the client machine, the network settings are:
- IP by DHCP (it can be seen that it was taken automatically)
- DNS is also automatic
  ![](https://www.bachvarova.com/__git/install_windows_server_virtualbox/client_pc_net_status.jpg)

## Add Client machine to AD 

> 1) In Windows Explorer right click on "This PC" -> "Properties"
> 2) Find "Rename this PC (advanced)"
     ![](https://www.bachvarova.com/__git/install_windows_server_virtualbox/client_pc_step01.jpg)

> 3) In the section "... rename this computer ..." click (change)


> 4) In the section "Member of" change from **Workgroup** to **Domain**
> 
>  ![](https://www.bachvarova.com/__git/install_windows_server_virtualbox/client_pc_step02.jpg)
 
> 5) Will be prompted to log in to Windows Server for authorization;
> If you authenticate correctly you will be greeted with "Welcome to domain domain.local and a **Restart** message.

> 6) After the restart, you will be able to log in to the domain with the previously created user and password.
     ![](https://www.bachvarova.com/__git/install_windows_server_virtualbox/client_pc_step03.jpg)


*** IN Preogress ..... 