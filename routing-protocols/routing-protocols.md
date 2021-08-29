---
description: Routing Protocols
---

# Routing Protocols

Routing Protocols

Loopback Interface -

A loopback interface is a fake or virtual interface that is created on a router.

It is not a physical interface, it is virtual.

This is virtual interface is assigned an ip address of your choice.

The purpose of loopback interface is, it is used for testing and administration purposes.

Commands - conf t int loopback 0 ip address 192.168.1.1.255.255.255.0

Routing Table -

A routing table is a file that contains set of rules that shows information on what path a data packet takes to its destination.

For ex - A router uses routing tables so as the data packet arrives at the router.

The router looks at its routing table to find out where to forward the data packet along the best path to its destination.

The basic routing table contains -

A network destination - The ip address of the final destination.

Subnet mask - Determines which part of the ip address is the host and network portion.

Gateway - Tells the router which ip address the data packet should be forwarded to.

Interface - The outgoing ip address of the device that’s sending the data.

Next hop - The ip address to which the ip address is forwarded to.

Metric - Determines the best route among multiple destinations.

Routing Protocols -

In order for data to travel across a network and reach its destination, it needs a map to determine the best path to take and the way it does it by using routing protocols.

Routing protocols collect information about the current network status and map out the best path for data packets to take to their specific destination.

There are 3 types of Routing Protocols

Distance Vector Link State Hybrid

Distance Vector Protocol -

Factors in distance to the destination based on how many hops.

Hop refers to how many routers a data packet has to go through to reach its destination.

One of the distance factor protocol is RIP : Routing Information Protocol.

RIP \(Routing Information Protocol\) -

The oldest routing protocol.

Routers that use RIP, broadcast their routing information to other routers every 30 seconds regardless if the routing information has changed or not.

So, as a result of this, as networks got larger, this calls a lot of necessary traffic on a network. So the developers created RIPv2 which solved the problem of excessive broadcast traffic that RIPv1 caused.

BGP \(Border Gateway Protocol\) -

Another distance routing protocol is called BGP.

This is the standard routing protocol of the internet.

Determines routing directions that are based on paths and policies.

Link State Protocol -

The addition to distance vector protocol, there is also link state.

It is a routing protocol that is used by routers to share information and independently map out the best path on a network.

Two examples of link state protocols are -

OSPF IS-IS

OSPF \(Open Shortest Path First\) -

A routing protocol that is used to determine the correct route for data packets to take their destination.

It collects information from other routers using IP.

Creates a topology map of the network.

IS-IS \(Intermediate System to Intermediate System\) -

Routers are organized into a domain or groups.

IS-IS primarily functions within these domains.

Unlike OSPF where it uses IP to communicate IS-IS uses CLNS to communicate to other routers.

CLNS - ConnectionLess Network Service.

Hybrid Protocol -

EIGRP - Enhanced Interior Gateway Routing Protocol.

Combination of distance vector and link state protocols.

Runs on cisc routers.

It is fast less overhead and it support many network layer protocols.

SIP \(Session Initiation Protocol\) -

This protocol is used for establishing communication sessions over the Internet.

Ex - Voip \(Voice over Internet Protocol\) -

Term that is used for voice communication over IP networks.

It is also used for services such as instant messaging and conferencing services.

SIP operates at the application layer of the OSI model.

RTP \(Real-Time Transport Protocol\) -

This protocol is the internet standard for transporting real time data such as streaming audio and video.

RTP is often used over UDP so it does not guarantee data delivery.

RTP is also used with RICP \(Real-Time Transport Control Protocol\)

This unables you to monitor the quality of the data being delivered.

RTP can be used to send data in both, unicast and multicast.

