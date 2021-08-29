---
description: Subnet Mask
---

# Subnet Mask

Subnet Mask

IP address consists of two parts - A network address and a host address.

The way to tell which portion belongs to either the network or the host is where the subnet mask comes in.

IP address - 176.16.0.0

Subnet mask - 255.255.0.0

A subnet mask is a number that resembles an ip address.

It reveals how many bits in the ip address are used for the network by masking the network portion of the ip address.

In the example, the first two octets are 255.

If we look the subnet mask in a binary form, then the first two octets will be all ones because when you count all the numbers in an octet, it will be equal to 255.

173.16.0.0 - 10101101.00010000.00000000.00000000

255.255.0.0 - 11111111.11111111.00000000.00000000

176.16 - Network portion 0.0 - Host portion

When subnet mask is one or it aligns with 1, that is the network portion.

Default subnet mask for class A,B and C.

N- Network h- host

Class A - Subnet Mask - 255.0.0.0 - NNNNNNNN.hhhhhhhh.hhhhhhhh.hhhhhhhh

Class B - Subnet Mak - 255.255.0.0 - NNNNNNNN.NNNNNNNN.hhhhhhhh.hhhhhhhh

Class C - Subnet Mask - 255.255.255.0 - NNNNNNNN.NNNNNNNN.NNNNNNNN.hhhhhhhh

