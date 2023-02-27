# Windows Server Setup - Add DHCP, DNS and Active Directory (AD)

Adding a **DHCP** to a Windows server is done by:
1) menu Manage -> Add Roles and Features -> (next);
2) Installation Type -> (1) Role-based or feature-based installation -> (next);
3) Server Selection -> (next);
4) Server Roles -> select: DHCP Server, Active Directory Domain Services and DNS Server;

![](https://www.bachvarova.com/__git/install_windows_server_virtualbox/addDNS_DHCP_AD_GP.png)
![](https://www.bachvarova.com/__git/install_windows_server_virtualbox/serverAddAD.jpg)
5) Then "next" and Install features ...
![](https://www.bachvarova.com/__git/install_windows_server_virtualbox/addingAD_DHCP_DNS.jpg)
![](https://www.bachvarova.com/__git/install_windows_server_virtualbox/addingAD_DHCP_DNS_result.jpg)

6) and then restart ...
   ![](https://www.bachvarova.com/__git/install_windows_server_virtualbox/addingAD_DHCP_DNS_toConf.jpg)