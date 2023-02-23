# Step 2: Creating a virtual machine for Windows Server and Clients PC;

## Download and install Windows Server image file (.ISO) 

For the test it can be downloaded from Microsoft.
I choose ver. 2016: 

https://www.microsoft.com/en-us/evalcenter/download-windows-server-2016

Here I will not explain in detail  the steps when creating a new virtual machine in VirtualBox, but it is important to enter the minimum requirements (parameters) for the relevant operating system.

I set:

- Disk space - 80 GB
- Base memory - 4 GB (4096 MB)

After creating the virtual machine in Settings -> Storage -> Optical drive load your Windows Server .ISO file

Then start the machine and install the server.


## Download and install Windows 10 & 11 image file (.ISO)

Look here:

https://www.microsoft.com/en-us/software-download/windows10

https://www.microsoft.com/en-us/software-download/windows11

The virtual machine is created in the same way. Then the .ISO file is added
and the installation of the corresponding  operating system is started.
```
If you want Windows 11 to have Internet during the installation, you need first to set up DHCP and set up the Internet via NAT on the server.
```
