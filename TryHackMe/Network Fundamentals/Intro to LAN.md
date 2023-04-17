### Local Area Network (LAN) Topologies
1) star
![[Pasted image 20230415215447.png]]
2) bus![[Pasted image 20230415215522.png]]
3) ring![[Pasted image 20230415215539.png]]

#### Switch
dedicated devices within a network that are designed to aggregate multiple other devices such as computers, printers, or any other networking-capable device using ethernet![[Pasted image 20230415215656.png]]

#### Router 
Routing is the label given to the process of data travelling across networks. Routing involves creating a path between networks so that this data can be successfully delivered.

### Subnetting
 splitting up a network into smaller, miniature networks within itself.
 Subnetting is achieved by splitting up the number of hosts that can fit within the network, represented by a number called a subnet mask

### ARP Protocol
the **ARP** protocol or **A**ddress **R**esolution **P**rotocol for short, is the technology that is responsible for allowing devices to identify themselves on a network.
Simply, the ARP protocol allows a device to associate its MAC address with an IP address on the network. Each device on a network will keep a log of the MAC addresses associated with other devices.
When an **ARP request** is sent, a message is broadcasted to every other device found on a network by the device, asking whether or not the device's MAC address matches the requested IP address. If the device does have the requested IP address, an **ARP reply** is returned to the initial device to acknowledge this.

#### DHCP Protocol
IP addresses can be assigned either manually, by entering them physically into a device, or automatically and most commonly by using a **DHCP** (**D**ynamic **H**ost **C**onfiguration **P**rotocol) server.![[Pasted image 20230416074120.png]]