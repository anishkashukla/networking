---
description: Remote Access Protocols and Services
---

# Remote Access Protocols and Services

Remote Access Protocols and Services

RAS \(Remote Access Service\) -

Service that enables you to connect to a computer from a remote location Ex - From home to work.

It allows the services which would be available on a remote network to be accessed over a dial-up connection.

RAS was originally developed by Microsoft and built into their windows NT line of server software.

Works with major network protocols such as TCP/IP, NetBeri and IPX/SPX

SLIP \(Serial Line Internet Protocol\) -

This is a protocol for communication between two computers using a serial connection such as typical phone line.

Designed so data can transmit over serial ports and modem connections \(phone lines\).

It is rarely used anymore because it is not a secured protocol.

Does not support encryption or authentication.

All information is sent in clear text.

Does not provide error checking and is limited to using only the TCP/IP protocol.

So a better protocol was needed to address these issues and that protocol was PPP.

PPP \(Point-To-Point Protocol\) -

The standard remote access protocol used today.

Supports encryption or authentication.

This is a protocol used for communication between two computers using a serial connection such as a typical phone line.

This is a secure protocol.

Most ISPs use this protocol for their customers who want to access the internet through a dial up connection.

PPPoE \(Point-To-Point Protocol over Ethernet\) -

Protocol uses PPP over ethernet.

Used for encapsulating PPP frames in Ethernet frames.

Developed for DSL cable modem or wireless connections to the internet.

Used for connecting multiple users on a LAN to a remote site sharing a common device.

PPPTP \(Point-To-Point Tunneling Protocol\) -

Used for creating VPNs \(Virtual Private Network\).

This is the default protocol associated with VPN.

Ensures data transfer is secure by creating a secure tunnel.

GRE \(Generic Route Encapsulation\) -

Protocol that is used with PPTP in creation of a VPN network.

Creates the tunnel in PPTP.

Encapsulates the data in a secure manner.

