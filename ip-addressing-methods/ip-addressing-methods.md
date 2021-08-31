---
description: IP Addressing Methods
---

# IP Addressing Methods

Every computer on a network has to have an ip address for communication purposes.

There are two ways that a computer can be assigned an ip address.

It could be done either by using a dynamic ip or a static ip.

A dynamic ip is where a computer gets an ip address automatically from a DHCP server.

DHCP stands for Dynamic Host Configuration Protocol.

A DHCP server automatically assigns a computer with an ip address and in addition to an ip address, it can also assign a subnet mask, default gateway and a DNS server.

Dynamic ip addressing is the best choice because it makes managing a network a lot easier.

We can also assign an ip address to the computer manually and this is called a static ip.

This kind of ip addressing is also called as permanent because unlike dynamic addressing where the ip address can change automatically, a static ip only changes if the user decides to.

Self-assigned ip address -

If there is some problem witht DHCP server or something like that then the computer will itself assign an ip address \(169.254.0.0\).

Self assigned addressing is called APIPA \(Automatic private ip address assignment\).

Computer running microsoft windows do this so that they can still be able to communicate with other computers on the same network that also have the self assigned ip address.

If the DHCP server later becomes available then the computer changes its ip address to the one that is obtained from DHCP server.

Scope DHCP -

A DHCP server assigns ip addresses to the computers on a subnet from its scope.

A scope is a group and a range of consecutive IP addresses for computers that gets their ip address from a DHCP server.

Ex- 192.168.0.1 - Starting to 192.168.0.254 - Ending

If you want computer on your network to have a specific ip address all the time, you could create a reservation on the DHCP server.

A reservation ensures that a specific computer or device \(identified by MAC address\) will always be given the same IP address when that computer or device accesses the DHCP server.

Reservations are typically given to special devices or computers, such as network printers and servers that require using the same IP address constantly.

The DHCP server assigns the ip address as a lease.

The computer does not actually own the ip address, its actually a lease.

A lease is the amount of time in which an ip address is assigned to a computer.

A DHCP server will automatically renew the ip address for us.

DHCP Relay -

When a computer needs an ip address it would broadcast its request to a DHCP server and if DHCP server is on the same subnet as the computer then the DHCP server will receive the request and assign the computer an ip address.

If the computer and the DHCP server are not on the same subnet or if they are not using the same ip address settings then the DHCP server will not receive the request because broadcast cannot go outside their own subnet.

DHCP relay or ip helper is a service that is enabled on a router that will relay a DHCP broadcast it receives and forwards it.

The computer will broadcast its request for an ip address and once the DHCP relay on the router receives the broadcast, it would forward the broadcast to the DHCP server and then the DHCP server will send the ip address back to the computer.

