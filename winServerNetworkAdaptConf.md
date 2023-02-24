# Windows Server Setup - Network Adapters Configuration

It is necessary to configure both network adapters, for Internet and local network.

1) The NAT is set to the network card (compare mac address) to take IP and DNS from automatically.

![](https://www.bachvarova.com/__git/install_windows_server_virtualbox/winServerAdapter01.jpg)



2) For The LAN card the configuration is as shown below:
   Of course you can use another internal network IP range, I used 192.168.0.1

![](https://www.bachvarova.com/__git/install_windows_server_virtualbox/winServerAdapter02.jpg)

For the local network, we use our IP (192.168.8.1) for DNS to find the domain that we will register for AD (Active Directory) in the DNS server zone, and 8.8.8.8 is Google of course.
