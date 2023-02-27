# Configuring Windows Client PC to join Active Directory (AD DS)

``It is recommended to first add the user to the Active Directory and then join the computer to the Domain.`` 

> 1) Adding the USER to AD is done from a menu "Tools -> Active Directory Users and Computers"


Here you can add new Organization Units (OU) and/or Groups to the AD.

![](https://www.bachvarova.com/__git/install_windows_server_virtualbox/ad_add_usr.jpg)

>* **Organizational Units vs Groups In Active Directory**
> 
> Groups have SIDs, can be placed on access control lists, and can contain other groups (even the same type of group referred to as group nesting). 
> Organizational units do not have SIDs, can't be placed on an access control list, and can not be placed into a group.

>* **What is the difference between group and organizational units in Active Directory?**
> 
> The difference between an OU and a group is that OUs can contain different kinds of objects rather than being limited to accounts or groups, whereas groups can only contain accounts and other groups.

> Аdded a test user: 
> * "tedytest@domain.local" with the desired password and settings

// **********************************************

> After installation on the client machine, the network settings are:
- IP by DHCP (it can be seen that it was taken automatically)
- DNS is also automatic




*** IN Preogress ..... 