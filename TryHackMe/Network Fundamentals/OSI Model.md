The **OSI** model (or **O**pen **S**ystems **I**nterconnection Model) is an absolute fundamental model used in networking.  This critical model provides a framework dictating how all networked devices will send, receive and interpret data.
Process of Encapsulation (reverse: decapsulation) follows these Layers:
![[osimodel.svg]]

7) **Application**
how user interacts with data sent/received (protocols, applications, programs)
6) **Presentation**
standardization of data to work on any client
data encryption + security features
5) **Session**
 create a connection to the other computer that the data is destined for. When a connection is established, a session is created
 Pakets (chunks of data) sent over session
4) **Transport**
	Protocols:
	**T**ransmission **C**ontrol **P**rotocol (**TCP**):
	  for situations such as file sharing, internet browsing or sending an email. This usage is because these services require the data to be accurate and complete (no good having half a file!)
	  
	 **User Datagram Protocol (UDP):**
	  UDP doesn't care if the data is received.
3) **Network**
	Routing: determines the most optimal path in which these chunks of data should be sent.
	**OSPF** (**O**pen **S**hortest **P**ath **F**irst) and **RIP** (**R**outing **I**nformation **P**rotocol)
	-   What path is the shortest? I.e. has the least amount of devices that the packet needs to travel across.
	-   What path is the most reliable? I.e. have packets been lost on that path before?
	-   Which path has the faster physical connection? I.e. is one path using a copper connection (slower) or a fibre (considerably faster)?
	- 
2) Data Link
	 The data link layer focuses on the physical addressing of the transmission. It receives a packet from the network layer (including the IP address for the remote computer) and adds in the physical **MAC** (Media Access Control) address of the receiving endpoint. Inside every network-enabled computer is a **N**etwork **I**nterface Card (**NIC**) which comes with a unique MAC address to identify it.
1) Physical 
	Cables / Devices