---
title: "chiTCP"
date: 2017-01-20T00:00:00Z
showDate: false
draft: false
tags: ["academic","networking"]
---

Implemented Transmission Control Protocol (TCP), usinc C.

**Class**: CMSC 23300 -- Networks & Distributed Systems

**Description**: chiTCP is a programming assignment where students have to implement the TCP protocol. It provides a framework for students to bypass the operating system’s TCP stack and, instead, use a sandboxed and testable TCP stack that runs in userspace (instead of kernelspace). All the details of how TCP interacts with the other layers of the protocol stack (including how packets are handed down to the network layer, and how data is passed up to the application layer) are already implemented for the students, who can then focus on implementing the TCP protocol itself. Furthermore, chiTCP also allows students to write socket-based network applications on top of their TCP implementation (by using a “chisocket” library instead of the standard socket library). If two students write standard-compliant versions of TCP, their applications will be able to communicate over a real network.



**Score**: 93/100