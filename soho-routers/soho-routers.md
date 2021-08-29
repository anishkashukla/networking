# SOHO Routers

SOHO Routers -

It stands for small office/home office router.

Used primarily by homes and small businesses.

These are fairly easy to set up but if you don’t configure the router correctly you would not have access to the network.

To configure it -

Enter the routers built in web page to configure the router.

Most SOHO routers have a DHCP server built into it.

DHCP server automatically assigns the ip address to each computer in your network because all computers need an ip address to function on a network.

You can configure the wireless settings.

SSID \(Service Set Identifier\) -

You can set the SSID which is basically the name of your wireless network.

The SSID is shared among all wireless devices in your network.

The SSID is customisable and you can call it whatever you want.

Ex - When a wireless laptop scans for wireless networks to join in the vicinity of this router, the laptop will see the router’s SSID broadcast called My Wireless and if it has the proper credentials, it can join the network.

Channel Wireless Settings -

Channels are used to avoid interference with other wireless networks nearby.

So, if you are experiencing any connectivity issues to your wireless router, there might be interference with another nearby wireless network that is operating on the same channel as yours.

You can try changing the channel and see, if it solves your problem.

Wireless Security -

You can configure security of your wireless network.

There you can choose to disable security and have your network wide open or you can choose to secure your network with one of these security modes.

WEP \(Wired Equivalent Privacy\) -

It is one of the security protocols that are used for wireless networks.

It is meant to supply the same security to wireless networks as it did for wired networks.

After some time, it was found out that the 40 bit encryption key that WEP used was not secured and it was easily hackable so a better security protocol was needed for wireless.

WPS \(Wi-Fi Protected Setup\) -

This security protocol was designed for users who know little about wireless networks to make it as easy as possible for them to join a secure wireless network.

WPS is the easiest way to join a wireless network.

MAC Filter -

Every wireless adapter has a MAC address.

A MAC address is a hexadecimal number that uniquely identifies each device on a network.

With a MAC filter, you can either prevent or permit access by using the device’s MAC address.

DMZ \(Demilitarized Zone\) -

DMZ allows a designated computer on your network to be fully exposed to the internet.

It does this by the router’s forwarding all ports, at the same time to the designated DMZ computer.

So while those computers on our internal LAN are protected inside the firewall, the DMZ computer is outside firewall, the DMZ computer is outside the firewall and is not protected.

The DMZ is typically used for testing purposes.

So, if you just setup a computer that you want to be accessed from the internet and if you are having a problem configuring firewall and applications so that it can be accessed from the internet, you can simply bypass all firewall security and put the computer in DMZ temporarily to make sure everything is working until you pinpoint a problem you are having such as a firewall setting.

DMZ computer must be assigned a static ip address.

Port Forwarding -

You can customize port services for certain applications.

So, when a user sends these types of requests to your network from the internet, the router will forward those request to the appropriate computer.

Ex - A friend of your wants to access one of your computers in your home using RDP \(Remote Desktop Protocol\).

As you know RDP services uses port 3389 so when your friend starts up their RDP service on their computer, they put in their public ip address of your router and once that request hits your router, your router needs to know which computer on your network to forward that request to.

So, your friend can access the correct computer.

Guest Network -

A separate wireless network that is built into a wireless router that your guest can join so that they can have access to the internet.

Provides internet access for your guests.

The guest network will have their own SSID and it is typically the same name as your main network SSID but may have -Guest suffix added to the SSID

