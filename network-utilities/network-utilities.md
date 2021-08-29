# Network Utilities

Network Utilities

Ping Utility -

The ping command is the most widely used of the network utilities.

It is the tool that is used to test issues such as network connectivity.

Ex - ping  ip address

It is going to send out four data packets to the destination ip address we choose.

Then the destination will send the data packets back to us as a reply.

These replies are called echo reply request.

These replies would inform you about what is happening with the destination host we pinged.

Ex - If we received the reply then that means there is general network connectivity between us and the destination.

But if we did not get the reply then that means that there is no reply from the host and that there is no network connectivity between us.

If we ping the host and we get the message “Request timed out” then that could mean the host is down or that it is blocking all ping requests.

If we ping and got message that “Destination host unreachable” then that message is coming from the router and it means that the route to the destination cannot be found.

The ping command can also be used to test DNS name resolution issues.

Ex - Before we use the ping command with an ip address but we can also use it with a domain name like ping yahoo.com

If by pinging the domain name, we get the same successful results as typing the ip address then this will indicate that the name resolution by DNS is working fine.

But if the domain name ping failed, then the next step will be typing the ip address instead.

So, if by typing the ip address, the ping is successful this time then we now know that we are having the problem with DNS.

The ping command can also be combined with other sub commands like switches.

Switches are used to alter the parameters of the ping utility.

You can view the full list of these switches by typing the ping /?

Pingpath Utility -

Pathping is another windows network utility that combines the functionality of the ping and tracert.

Pathping  ip address/domain name

Pathping output shows the detail of the path a data packet takes between two devices and it also gives ping like statistics for each device that data packet takes on its way to its destination.

If you wanted to check a device using the regular ping command and if you fail to get a response because a firewall on the device has blocked all ping requests, you can use the ARP ping command instead.

ARP Ping Utility -

The ARP ping command uses ARP data packets to ping network devices.

Since it uses ARP packets, a firewall will not block any ARP data because ARP data is never blocked or should never be block on the LAN.

It cannot be used on the internet because the data is not routable so it only works on LAN.

Traceroute Utility -

This is used to find out the exact path a data packet is taking on its way to the destination.

Ex - tracert  ip address

The data packet will find its way to the destination and each time it reaches its a router on its path, it will report back information about that router such as the ip address and the time it took between each hop.

So, the tracert utility is a great tool that can be used to pin point where the problem lies on a network if a data packet cannot reach the destination.

Ex - If we try to ping the destination and the ping command failed, we can use the tracert utility to find out where the data is failing along its path.

Netstat Utility -

It is used to resolve netbios names to ip addresses.

This is the least common utility you will ever user.

ARP \(Address Resolution Protocol\) -

ARP is used to resolve ip addresses to MAC addresses.

In order for a computer to communicate with another computer, it needs to know the MAC address for that computer.

So, the first thing that the computer does us check its ARP cache to check whether it already has a MAC address for that computer.

We can check this ourselves at the command prompt by using the ARP utility by typing arp -a and if no entries are found so it will now ask the computer with the corresponding ip address for its MAC address.

Once, it has the MAC address, it will store the information in the ARP cache.

Netstat Utility -

It is used to display current network connections to your computer.

You can use netstat utility to see what connections you have if you don’t know.

In addition to connections, it also display which ports are open and listening for a connection.

Ipconfig Utility -

It is very common.

This utility is a powerful tool used to display networks configuration for our computer and this information can be used for problem solving.

For ex - If we open a command prompt and write ipconfig /all so this will display the full TCP/IP configuration for our computer such as our computer name, MAC address, ip address, default gateway, DNS servers and so on.

By using this information, we can find solution if we are experiencing problem.

For ex - If we have a problem with our ip address, we can see information like DHCP is enabled which means that this computer is getting its ip from the DHCP server and it also tells the ip address for the DHCP server.

It also tells the ip address for the DNS server so if we are experiencing any problems browsing the internet with domain names then their might be the problem with DNS server itself.

Using the ipconfig utility by itself displays the ip address, subnet mask and default gateway.

But using this utility when combined with sub commands called switches changes the output slightly.

Ex - If we use ipconfig /all, it displays the full TCP/IP configuration for our computer.

When we use ipconfig /renew, this releases and renews the ip address lease given to us from the DHCP server.

When we use ipconfig /release, it releases the ip address but does not renews it.

To see the complete list of all the switches that can be used with ipconfig or any command utility, just type the name of that utility/? and that will show you all the switches that are available.

Ifconfig Utility -

A command that is used in unix and linux operating system.

Displays configuration information from the network interface card such as -we

Ip address Subnet mask How many packets received and sent Any errors

Like ifconfig, it can be also combined with switches to alter the output.

Nslookup/ dig utility -

It is short name for “Name Server Lookup”

Used to look up DNS information.

Dig command is the unix version of nslookup.

