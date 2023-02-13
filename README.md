# azure
<i>Azure Projects</i>
<b><u> Creating Resources </b></u>

<b>Create a Resource Group</b>

<ul><li>Create a Windows 10 VM in the Resource Group with a new Vnet and Subnet</li>
 <li>Create a Linux (Ubuntu) VM in the same Resource Group and Vnet</li>

  <li>Observe the Virtual Network within Network Watcher</li></ul>

 <b> Observing Traffic </b>

<ul>  <li>Use Remote Desktop to connect to the Windows 10 VM</li>
  <li>Install Wireshark within the Windows 10 VM</li>
  <li>Filter Wireshark for ICMP traffic</li>
  <li>Ping the Ubuntu VM from the Windows 10 VM and observe traffic in Wireshark</li>
  <li>Ping a public website and observe traffic in Wireshark</li>
  <li>Initiate a perpetual/non-stop ping from the Windows 10 VM to the Ubuntu VM</li>
  <li>Disable incoming ICMP traffic for the Ubuntu VM's Network Security Group, observe traffic in Wireshark and ping activity in Windows 10 VM</li>
  <li>Re-enable ICMP traffic, observe traffic in Wireshark and ping activity in Windows 10 VM</li>
  <li>Filter Wireshark for SSH traffic</li>
  <li>SSH into the Ubuntu VM from the Windows 10 VM and observe traffic in Wireshark</li>
  <li>Exit SSH connection and observe traffic in Wireshark</li>
  <li>Filter Wireshark for DHCP traffic</li>
  <li>Attempt to renew the IP address for Windows 10 VM and observe traffic in Wireshark</li>
  <li>Filter Wireshark for DNS traffic</li>
  <li>Use nslookup to see the IP addresses of google.com and disney.com and observe traffic in Wireshark</li>
  <li>Filter Wireshark for RDP traffic and observe non-stop traffic due to the constant live stream of the RDP protocol.</li></ul>
