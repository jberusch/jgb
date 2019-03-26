---
title: "chiRouter"
date: 2017-01-23T00:00:00Z
showDate: false
draft: false
tags: ["academic","networking"]
---

Implemented IPv4, ICMP, and ARP in C, leveraging POX & Mininet.

**Class**: CMSC 23300 -- Networks & Distributed Systems

**Description**: In this project you will be implementing a simple IP router capable of routing IPv4 datagrams between multiple networks. This router will have a static routing table, so you will not have to deal with implementing a routing protocol like RIP or OSPF; instead, the project will focus on the routing of IP datagrams. While, at a high level, this just involves receiving IP datagrams and figuring out what interface they should be sent on, this requires building additional functionality before you can actually start routing IP datagrams:

* Your code must process the raw Ethernet frames that arrive through the router’s interfaces.
* Because you will be working at the Ethernet level, you will need to use ARP to map Ethernet addresses to IP addresses.
* Your router will need to support a small subset of the ICMP protocol so you can use tools like ping and traceroute, and to notify hosts of certain errors (e.g., if the router is given an IP datagram it cannot forward).




**Score**: 94/100