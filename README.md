# azure
Azure Projects
Part 1: Creating Resources

Create a Resource Group
Create a Windows 10 VM in the Resource Group with a new Vnet and Subnet
Create a Linux (Ubuntu) VM in the same Resource Group and Vnet
Observe the Virtual Network within Network Watcher
Part 2: Observing Traffic

Use Remote Desktop to connect to the Windows 10 VM
Install Wireshark within the Windows 10 VM
Filter Wireshark for ICMP traffic
Ping the Ubuntu VM from the Windows 10 VM and observe traffic in Wireshark
Ping a public website and observe traffic in Wireshark
Initiate a perpetual/non-stop ping from the Windows 10 VM to the Ubuntu VM
Disable incoming ICMP traffic for the Ubuntu VM's Network Security Group, observe traffic in Wireshark and ping activity in Windows 10 VM
Re-enable ICMP traffic, observe traffic in Wireshark and ping activity in Windows 10 VM
Filter Wireshark for SSH traffic
SSH into the Ubuntu VM from the Windows 10 VM and observe traffic in Wireshark
Exit SSH connection and observe traffic in Wireshark
Filter Wireshark for DHCP traffic
Attempt to renew the IP address for Windows 10 VM and observe traffic in Wireshark
Filter Wireshark for DNS traffic
Use nslookup to see the IP addresses of google.com and disney.com and observe traffic in Wireshark
Filter Wireshark for RDP traffic and observe non-stop traffic due to the constant live stream of the RDP protocol.
