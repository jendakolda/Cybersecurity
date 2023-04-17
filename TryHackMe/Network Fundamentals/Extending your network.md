### Introduction to Port Forwarding
![[Pasted image 20230416123555.png]]
 port forwarding opens specific ports (recall how packets work). In comparison, firewalls determine if traffic can travel across these ports (even if these ports are open by port forwarding).

### Firewals 101
A firewall is a device within a network responsible for determining what traffic is allowed to enter and exit. Think of a firewall as border security for a network. An administrator can configure a firewall to **permit** or **deny** traffic from entering or exiting a network based on numerous factors such as:
-   Where the traffic is coming from? (has the firewall been told to accept/deny traffic from a specific network?)
-   Where is the traffic going to? (has the firewall been told to accept/deny traffic destined for a specific network?)
-   What port is the traffic for? (has the firewall been told to accept/deny traffic destined for port 80 only?)
-   What protocol is the traffic using? (has the firewall been told to accept/deny traffic that is UDP, TCP or both?)

Firewalls perform packet inspection to determine the answers to these questions.

Stateless vs. Stateful firewalls


### VPN Basics
- Allows networks in different geographical locations to be connected.
- offers privacy + anonymity

### LAN networking devices

**Routers vs. Switches**

**VLAN** (**V**irtual **L**ocal **A**rea **N**etwork) allows specific devices within a network to be virtually split up