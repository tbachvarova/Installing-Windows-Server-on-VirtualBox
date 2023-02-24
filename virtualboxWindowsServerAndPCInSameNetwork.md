# Step 3: Network setting of the virtual machines (to be on the same network)

It's so simple...
* Windows Server must have two network adapters (for Local network and for Internet /NAT/);
* Every Client PC in the Local network should be in the same network group (LAN);
 
## Set Windows Server Network in Virtual machine
To have Internet and to share it with the other PC in the local network - must have 2 (two) network adapters;

**1) Adapter 1** (NAT):
**NAT** stands for **N**etwork **A**ddress **T**ranslation. It's a way to map multiple local private addresses to a public one before transferring the information.

**2) Adapter 2** (Local Network):
It should be set to "**Internal Network**"
The network name "**intnet**" it is important to indicate that they are on the same network:

![](https://www.bachvarova.com/__git/install_windows_server_virtualbox/virtual_box_WindowsServerNetwork.jpg))


## Set Windows Client PCs Network in Virtual machine

Client machines only need 1 (one) network adapter with "**Internal Network**" setting with name "**intnet**".

![](https://www.bachvarova.com/__git/install_windows_server_virtualbox/virtual_box_WindowsClientsNetwork.jpg)