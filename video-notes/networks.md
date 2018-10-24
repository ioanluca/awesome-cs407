# Networks

Multiple *nodes* (devices) connected together to communicate


Types: 
- LAN
- WAN - LANs connected together
    - require broadbands
    - internet is the largest WAN

## Packets

Data is split into packets that are recombined at the other end.

### CRC - cyclic redundancy check is the numbers of `1`s
in the payload. 
Receiver counts `1`s and if they don't match asks the sender 
to resend.

## Receiving and transmitting data

### Hubs
Broadcasts the incoming packets to all nodes. 

Nodes are expected to ignore the packets that are not addressed
to them.

### Switches
Know where to send the data using `M.A.C`
(*Media Access Control and are physical*). 
Can also broadcast.

### Routers
the same but can't broadcast

they can also connect to internet and protect the LAN


# OSI 
- open systems interconnection model
- theoretical model for communication
- protocol independent

## 7 Layers
they depend on each other and they prepare data for the
next level

## Internet protocol suite

internet - network of networks




## TCP / IP

TCP - transmission control protocol
IP - internet protocol

### Application
- app protocol - `http` \ `ftp`

### Transport
TCP ports
`80` for `http`


### Network
routing data

uses ip

### Link
responsible for passing packets


### ip 
socket = ip + port

tcp - verifies the correct delivery of data from
client to server 





