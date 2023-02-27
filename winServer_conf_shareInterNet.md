# Share Windows Server Internet to Local Network PC
"Installing the Remote Access role in Windows Server"

> For this is necessary to add another feature - **Remote Access**

> 1) menu Manage -> Add Roles and Features -> (next);
> 2) Installation Type -> (1) Role-based or feature-based installation -> (next);
> 3) Server Selection -> (next);

> 4)  Server Roles -> check **Remote Access** -> (next)

![](https://www.bachvarova.com/__git/install_windows_server_virtualbox/ra_add_feature01.jpg)


> 5) Features -> (next)

> 6) Remote Access -> (next)

> 7) Role Service -> **Check "Routing"** -> (Add Features) -> (next)
This will Add "DirectAccess and VPN (RAS)" , this is OK.
     ![](https://www.bachvarova.com/__git/install_windows_server_virtualbox/ra_add_feature02.jpg)

> 8) (next) -> (next)
> 
> Check "Restart the destination server automatically if required", then (INSTALL). After install complete just "Close"

> 9) Then go to menu Tools -> **Routing and Remote Access** 
>
> Mark your server name and right click -> "Configure"
    ![](https://www.bachvarova.com/__git/install_windows_server_virtualbox/ra_add_feature03.jpg)
> * In the Routing and Remote Access Server setup wizard click (NEXT)


> 10) In list of options **choose "Network Address Translation (NAT)"** -> (next)
     ![](https://www.bachvarova.com/__git/install_windows_server_virtualbox/ra_add_feature04.jpg)


> 11) Leave first Checked -> (next) -> (Finish)
      ![](https://www.bachvarova.com/__git/install_windows_server_virtualbox/ra_add_feature05.jpg)
      ![](https://www.bachvarova.com/__git/install_windows_server_virtualbox/ra_add_feature06.jpg)

