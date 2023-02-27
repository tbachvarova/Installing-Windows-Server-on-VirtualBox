# Configure Windows Server DHCP

The Configuration is set from menu:

1) menu Tools -> DHCP;
2) In the tree windows go to "your server" -> IPv4
3) then right click -> "New Scope ..."
4) In the wizard set your preferred settings.
My Scope is IP FROM: 192.168.50 to  192.168.0.200
5) in "Add Exclusions and Delay" for me is (next);
6) Lease Duration -> leave default - 8 Days
7) Configure DHCP Options -> (YES) -> (next)
8) Router (Default Gateway) -> add current server IP: 192.168.0.1
9) Domain Name and DNS Server -> add current server IP: 192.168.0.1
10) (next) -> (next)


![](https://www.bachvarova.com/__git/install_windows_server_virtualbox/dhcp.jpg)