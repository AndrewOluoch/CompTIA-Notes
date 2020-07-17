OSI Model (Open Systems interconnect)-

Physical layer:
cable types- twisted pair, caox, wireless, copper, fiber optic, propiertary


2.Data link layer- The second layer of the seven-layer OSI model of computer networking
provides the functional and procedural means to transfer data between network entities
and might provide the means to detect and possibly correct errors that may occur in the 
physical layer.

Ethernet switching//

switches- used to connect all devices in network together

CSMA/CD(Carrier Sense Multiple access with collision Detection)-

collision- If there is a detection of more then 5 volts(voltage spike), devices stop and wait till they 
can send information again

Half duplex communication- one device communicates at a time 

Full duplex communication- Two devices can communicate at the same time
*Prevents collisions

Modern collision domain- Half duplex connection between a pc and a switch

Ethernet Speed-
Ethernet = 10Mbs
FastEthernet = 100Mbs
GigabitEthernet = 1Gbps
10GigabitEthernet = 10Gbps
400GigabitEthernet = 40Gbps

Frame- A chunk of data, with a data link layer header

Destination MAC Adress & Source MAC Adress- Layer two adress tied to a network interface card

Network interface card- Device that we plug in our Ethernet cable into

Frame Check Sequence (FCS)-
Preforms Cyclical Redundancy Check(CRC)- runs info through algorithm generates a value 
that is put into a 32 bit feild

MTU(Maximum Transmission Unit)-for ethernet is 1500 bytes

Protocol Data Unit- Varies frm model to model, Layer 2 PDU can contain entire frame,
source and destination MAC adress, type feild, FCS and data itself.

Topologies-
Bus network Topology- All devices connected through one central wire network

Star Topology- Used by modern ethernet

Brodcast storms & Prevention- Overflow of broadcast messeges between switches due to overflow 
of traffic

Spanning Tree Protocol- Shuts down redundancy between switches

VLANs(Virtual LANs)- are logical grouping of devices in the same broadcast domain, 
they are usually configured on switches by placing some interfaces into one broadcast domain 
and some interfaces into another. Each VLAN acts as a subgroup of the switch ports in an Ethernet LAN.


Switch port Mirroring-Port mirroring is used on a network switch to send a copy of network packets seen 
on one switch port (or an entire VLAN) to a network monitoring connection on another switch port.
commonly used for network appliances that require monitoring of network traffic 

Power over Ethernet(POE)-
describes any of several standard or ad hoc systems that pass electric power along with data on twisted 
pair Ethernet cabling.

7.Application Layer:
abstraction layer that specifies the shared communications protocols and interface 
methods used by hosts in a communications network.

https- encrypted layer version of http

FTP-File transfer protocol,transfer files from one divece to another
*require username & password
Ports:20 & 21/ authentification & transferring info


sFTP-Secure fle transfer protocol,transfer files from one divece to another
*require username & password
*encryps traffic
Port:22 used for SSH to encrypt traffic

TFTP-Trivial file transfer protocol, send tiny files between two diveces 
Port:69

SMB- Server Message block
Microsoft or Linux Systems,
Port:445

Authentication
LDAP- Lightweight Directory Access Protocol
Port:389

LDAPs- 
Port:636

DHCP(Dynamic Host Configuration protocol)-
client asks server for ip adress 
DHCP server returns IP adress, Subnet Mask, Default Gateway Dns Server & other info
Automatically tells you about information you need and allows you to connect.

NTP(Network time Protocol)-Way to use a server configure all of the times on our 
clients to be the same.

SSH(secure shell)- 
*Encrypted
can be used to access device remotley
Port:22
Putty configuration/SSH Tool

Telnet-
Port:23

SNMP"Walk the tree"- Gathers all info from different clients and transfers them
to SNMP server  

RDP-
remotly manage device
Port:3389

H.232-
Audio/ visual communication
Port:1720-1721

SIP-
for voice over ip
Port:5060/5061

Network Layer:
responsible for packet forwarding including routing through intermediate routers.


4.Transport Layer:
fourth layer, provides logical communication between application processes running on 
different hosts within a layered architecture of protocols and other network components.

TCP(Transmission Control Protocol)-
Three way hand shake: SYN,SYN-ACK,ACK-Three steps in appling a connection between a client and a server

Four way disconnect/TCP Reset: disconnect methods


UDP(User Datagram Protocol)-
No threee way handshake
no reliable communication
No sequence numbers or aknowledgement numbers 
Used for efficient small data transfer

protocol hierarchy- Port numbers


Presention Layer:
used to present data to the application layer (layer 7) in an accurate, well-defined and 
standardized format.
 

Session Layer:
layer 5, session layer provides the mechanism for opening, closing and managing a session 
between end-user application processes, i.e., a semi-permanent dialogue.

IP Config CMD- Shows ip adress & subnet mask

Binary converison//

IP Address:
Network Portion||Host POrtion
203.0.113	   ||.10

32 bit value broke into 4 octets

Network Address-
*zip code
-Identifier for a group of devices
-network prefix
-has all binary zeros in the host portion

Broadcast Address-
-Identifier for all devices on a network
-Has all binary ones in the host portion

Host Adress-
-Identifies unique device on a network
-anything cother than all zeros or ones in host portion
*Used when communicating on an ip network

DHCP Server(Dynamic Host Configuration Protocol )- A network server that automatically provides and assigns IP addresses, 
default gateways and other network parameters to client devices.

Gateway- Device that joins 2 networks together, does not change the data, it only changes the format of the data
  
CSU/DSU- Converts from WAN to LAN

NICs (Network Interface Card)/ Mac Adress = UID-
COnverts serial data to parallel Data

Transceivers- 
*Device with both a trsnsmitter and a reciver in the same package.

*A term used for any device that recives data, converts it then transits the data to anothet location
 
WAPs (Wireless Access Point)- 

Modem - transmits analog data from telephone lines and converts it into digital at 56kbps
