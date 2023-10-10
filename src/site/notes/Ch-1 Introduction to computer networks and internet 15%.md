---
{"dg-publish":true,"permalink":"/ch-1-introduction-to-computer-networks-and-internet-15/"}
---


*"A computer network is a system in which multiple computer are connected to each other to share information and resources."*
### Advantages:
- File Sharing
- Resource Sharing
- Better connectivity and communication
- Internet access
- Entertainment
- Inexpensive system
- Flexible access
- Instant and multiple access
### Disadvantages:
- Lack of data security and privacy
- Presence of computer viruses and malware
- Lack of independence
- Lack of Robustness
- Need an efficient handler

### Applications / Use of computer network:
- Financial services
- Business
- Email services
- Mobile applications
- Directory services
- Teleconferencing


### Different types of computer networks:
#### LAN: local area network:
- private ownership has control over the local area network rather than the public.
- covers smaller areas such as collage, schools, hospitals etc.
#### MAN: metropolitan area network:
- It covers large area than LAN such as small towns, cities etc.
- ownership can be public or private.
#### WAN: wide area network:
- It covers large area than LAN as well as MAN such as country/continent etc.
- It is expensive and should or might not be owned by one organization.

|  | **LAN** | **MAN** | **WAN** |
|-|-----|-----|-----|
| Full-Form | Local Area Network | Metropolitan Area Network | Wide Area Network |
| Area | Small such as the same building or campus. | Large area such as city. | Larger area such as country/continent. |
| Ownership | Private | Public or Private | Owned by one or more organizations. |
| Transmission Speed | High | Average | Low |
| Error rates | Lowest | Moderate | Highest |
| Equipment cost | Inexpensive | Moderate-expensive | Most expensive |
| Design & Maintenance | Easy | Moderate | Difficult |

**Network Edge:** Those computers of the network used at the edge (end) of the network.
**Clients:** Computer system that request for communication.
**Servers:** Computer system that receive that requests from the clients and process them.

**Various network design models:**
1. Peer to Peer network
2. Client-Server network

![](https://i.imgur.com/PYQknSF.png)


### Techniques used in data communication to transfer data:

**1. Connection-oriented method**
**2. Connectionless method**

![](https://i.imgur.com/QLWCVbV.png)

**1. Connection-oriented method:**
- It actually a data transfer method among two computers in different network.
- Typically used to transport and send data at session layer.
- The data packets are transferred  to receiver in a similar order in which they have seen transferred by sender.
- Operations:
		1. Establishing Connection
		2. Transferring Data or Message
		3. Releasing the connection
- Different Ways:
	1. Without virtual circuits / Circuit-switched connection:
		A dedicated route is being established among sender and receiver, and whole data is send through it. 
		A dedicate physical route or a circuit is established among all communication nodes, and after that, data is transferred.
		TCP - Transmission Control Protocol
	2. With virtual circuits / Virtual Circuit-switched connection:
		A preplanned route is established before data transferred.
		The message is transferred over the network in such a way that it seems to use that there is a dedicated route from sender to receiver.  
		X.25

**2. Connectionless method:**
- Allow data to be transferred without any link among processes.
- A message is broken into packets, and each packet is transferred separately.
- Some of data packets may also be lost during transmission.
- UDP - User Datagram Protocol













