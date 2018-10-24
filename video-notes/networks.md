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




