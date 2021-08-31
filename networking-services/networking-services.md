---
description: Networking Services
---

# Networking Services

Networking Services -

DNS \(Domain Name System\) -

This resolves domain name to ip addresses.

In networking, computers don’t go by name like humans do, they go by numbers.

If you type in a web addresses in your web browser, DNS will transform the name to a number because all computers know numbers.

For ex - When you type in yahoo.com in your web browser, the DNS server will search through its database to find its matching ip address for that domain name. When it finds it, it will transform that domain name to the ip address of the yahoo web server.

WINS \(Windows Internet Name Service\) -

It is used in NETBIOS network.

This server is similar to DNS.

WINS resolves NETBIOS names or computer names to ip addresses.

So If you want to communicate with another computer on the same network, you would do so by using the computer’s name and then the WINS server will resolve the name to the ip address of that computer.

NAT \(Network Address Translation\) -

It is a service that is typically used in the routers.

This is used to translate a set of IP addresses to another set of IP addresses.

Private IP address is public and public ip address is private.

Ex- There is a private network and it is using a set of private ip addresses internally and we have a router with its public ip address and the router is running the NAT service.

If the computer in this network wanted to communicate over the internet, it needs to translate its private ip address to the internet’s public ip address and this goes both the way.

If the computer on the internet wants to communicate with the computer on the private network then the public ip address needs to be translated to the private ip address for that computer.

PAT \(Port Address Translation\) -

Another version of NAT is called PAT.

This translates ip addresses based on port numbers.

Each computer in a private network is issued not only an unique ip address but they are also issued a unique port number.

This is done so that the external data packets from the internet knows which computer on a private network it wants to talk to.

For ex- If a device outside this network wanted to communicate with a computer on this private network, the ip address along with its port number will be translated by PAT to find the correct computer.

SNAT \(Static Network Address Translation\) -

NAT translates a private network’s ip addresses to a public ip address.

All the private ip addresses will be translated to a one single public ip address and vice verse.

So what SNAT does, it can link a public ip address with a private ip address permanently.

This is used when a computer or a server needs to be accessed from outside the network.

Proxy Service -

A proxy service is similar to our web browser.

Whenever you look at the web page, your web browser will store that web page into cache.

So at a later time if you were to look at the web page again, your browser retrieves it much faster because it doesn’t have to download the contents of the web page all over again since it is already stored in your computer, proxy server does the same thing.

Ex- If a company uses proxy server whenever a user wants to retrieve a web page, the proxy server will retrieve the web page from the internet on behalf of the user and then it will store that web page into a centralized cached database.

So, if another user on a different computer goes to a web page that has been stored in the proxy database, the proxy server does not have to go out on the internet to retrieve the web page.

It can simply retrieve it from its database and send it to the user.

Benefits of using proxy service -

Speed - Since web page retrieval is much faster.

It saves bandwidth - Because a proxy server reduces the need to go out on the internet.

Security - Because it reports what web pages are retrieved to the network administrator.

RDP \(Remote Desktop Protocol\) -

It is a technology from Microsoft to access a remote computer desktop.

RDP is based on Microsoft terminal services.

So if a user wanted to access another computer, the user can simply type in proper credentials and then the user can have the remote computer’s desktop displayed on their own computer screen.

CSMA/CD \(Carrier Service Multiple Access with Collision Detection\) -

When you have a lot of computers on a network and they all are sending data, the potential for collision is present and when we have collision, data communication is lost so that’s why they developed a protocol called CSMA/CD which is the access method used on ethernet network and this method works by each computer first sensing if the wire is idle and if it is then it sends its data therefore avoiding any collision.

But if you have two computers trying to send data at the same time, a collision will happen and when it happens, the computers will wait a random amount of time and retries to send their data.

CSMA/CA \(Carrier Sense Multiple Access with Collision Avoidance\) -

This is the access method used for carrier transmission and wireless networks.

This is similar to CSMA/CD except when the computer wants to send the data, it first sends out a small data packet to make sure that the channel is clear before sending out its main data.

If the packet is successfully transmitted then the computer is clear to send out its main data.

Broadcast -

The term broadcast refers to when there is a single transmitter of data and that data is being received by multiple receivers.

For ex - A wireless router can broadcast its wireless signals and be picked up by multiple computers to access the internet.

Unicast vs Multicast -

With unicast, the data packets are sent to a single destination.

With multicast, the data packets are sent to multiple destination at the same time.

