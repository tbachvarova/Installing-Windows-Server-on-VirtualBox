# Configuring Windows Server Active Directory (AD DS)

After the reboot, the Windows Server Аctive Directory must be configured. An example setup is shown below:

> 1) If you are going to add local domains for personal needs or for the test, choose the **forest** option -> (next):
>
>![](https://www.bachvarova.com/__git/install_windows_server_virtualbox/ad_conf_wiz01.jpg)


> 2) Then it is necessary to specify a password for Directory Services Restore Mode (DSRM) -> (next)
>
>![](https://www.bachvarova.com/__git/install_windows_server_virtualbox/ad_conf_wiz02.jpg)


> 3) Active Directory DNS delegation  -> leave unchecked -> (next)
>
>The names within a zone can be delegated to another zone maintained by a different server. Thus the responsibility of a subdomain can be passed on to a different name server which will handle requests for the resource records through a process called AD DNS delegation.
>
>_**For this test leave unchecked.**_
>
>![](https://www.bachvarova.com/__git/install_windows_server_virtualbox/ad_conf_wiz03.jpg)

> 4) NetBIOS domain name in Active Directory-> set what you like -> (next)
>
>**NetBIOS domain name**: Typically, the NetBIOS domain name is the **subdomain** of the DNS domain name. For example, if the DNS domain name is test.com, the NetBIOS domain name is "test". If the DNS domain name is app.test.com, the NetBIOS domain name is "app".
>
> ![](https://www.bachvarova.com/__git/install_windows_server_virtualbox/ad_conf_wiz04.jpg)


> 5) **Paths** -> (next)
>
>![](https://www.bachvarova.com/__git/install_windows_server_virtualbox/ad_conf_wiz05.jpg)
>![](https://www.bachvarova.com/__git/install_windows_server_virtualbox/ad_conf_wiz06.jpg)

> 6) (Install)
![](https://www.bachvarova.com/__git/install_windows_server_virtualbox/ad_conf_wiz07.jpg)

> 7) After the installation, you must restart the server.
     Your login screen should be different:
![](https://www.bachvarova.com/__git/install_windows_server_virtualbox/ad_conf_wiz08_afterRestart.jpg)
![](https://www.bachvarova.com/__git/install_windows_server_virtualbox/server_after_ad_dns.jpg)

`For now, you have Windows installed, configured Active Directory and a DHCP server to which you can connect client machines.`
