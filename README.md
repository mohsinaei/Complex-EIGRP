# Complex EIGRP
 
Enhanced Interior Gateway Routing Protocol (EIGRP)

This is a project which invovles several Cisco routers and the routing protocol used is EIGRP.

Vendor: Cisco Type: Distance vector protocol EIGRP is an enhanced distance vector protocol that evolved from Cisco's IGRP

EIGRP steps:

HELLO packets. Sent out at regular intervals to facilitate the neighbor discovery process. QUERY packets. Used by a router to advertise that a route is in an active state and to request alternate path information from neighbors. REPLY packets. Sent after an entire QUERY packet has been received to acknowledge that packet's receipt. REQUEST packets. Used to request specific information from one or more neighbors, similar to QUERY packets but sent unreliably -- no notification if delivery fails. UPDATE packets. Convey information about destinations and their reachability.

EIGRP benefits:

Faster convergence Better routing protoocol to avoid routing loops Optimized network performance and lower load on the routers Reduces the protocol's load on the network because only changes to the routing table are propagated, rather than the entire routing table

How EIGRP finds other networks:

An EIGRP-based router keeps a copy of its neighbor's routing tables. If it can't find a route to a destination in one of these tables, it queries its neighbors for a route, and they, in turn, query their neighbors until a route is found. When a routing table entry changes in one of the routers, it notifies its neighbors of the change only. Some earlier protocols required sending the entire table.

Reference: https://www.techtarget.com/searchnetworking/definition/EIGRP

Mohammad Sinaei
