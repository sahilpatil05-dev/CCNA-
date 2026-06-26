# Interfaces and Cables

# Cables
-RJ 45 :Rejestered Jack 45 

# Ethernet 
-Ethernet is a collectio of network protoclos/standards

# Bits and Bytes
-Data is measured in bits per scond (kbps,mbps,gbps,etc)and not in bytes 
8 bits = 1 bytes
1 kilobit(kb)=1000b bist 
1 megabit(mb)=1000,000 bits
1 gegabit(gb)=1000,000,000 bits
1 terabit(tb)=1000,000,000,000 bits


| Speed | Common Name | IEEE Standard | Informal Name | Maximum Length  |
|------- |-------------|---------------|---------------|----------------|
| 10 Mbps  | Ethernet          | 802.3i  | 10BASE-T   | 100 m |
| 100 Mbps  | Fast Ethernet    | 802.3u  | 100BASE-T  | 100 m |
| 1 Gbps   | Gigabit Ethernet  | 802.3ab | 1000BASE-T | 100 m |
| 10 Gbps   | 10 Gig Ethernet  | 802.3an | 10GBASE-T  | 100 m |









# Ethernet Stadards 
-IEEE : Institute of Electrical and Electronics 
Ethernet was originally defined in the IEEE 802.3 standard in 1983.
- the maximum length of an Ethernet UTP cable is 100 meters
- 10GBASE-SR, 10GBASE-LR, and 10GBASE-ER were defined in the IEEE [802.3ae] standard.
- the speed of a 'FastEthernet' connection is 100Mbps
# UTP - UnShielded Twisted pair cables

-Wire pairs in UTP are twisted together to protect it from Electromagnetic Inference(EMI)

-Straight Through Cable
-Cross-over Cable 
-Auto MDI -X calble 

-If Auto MDI-X is disabled, Cross Over UTP cable is used to connect two routers together
-In a FastEthernet connection, a firewall transmits data on  pins 1 and 2
- In a FastEthernet connection, a PC receives data on 3 and 6 pins 
- In a FastEthernet connection, a switch receives data on 1 and 2 pins 
- In a FastEthernet connection, a router transmits data on 1 and 2 pins
- In a FastEthernet connection, a PC transmits data on 1 and 2 pins and recives on 3 and 6
- If Auto MDI-X is disabled, Straight Trough Cable  should be used to connect a PC and a switch
- the speed of an 'Ethernet' connection is 10 MBps
-  A full-duplex connection allows a device to send and recive a data at the same time
- UTP cables emit a faint signal outside of the cable, which can be detected and copied.
- UTP cables are vulnerable to EMI (electromagnetic interference).
-If Auto MDI-X is disabled, cross over  cable is used to connect two switches together
- 10GBASE-SR maximum cable length is 400meter
- Pair 1-2, Pair3-6 pin pairs are used in a 10BASE-T or 100BASE-T connection
- If Auto MDI-X is disabled, straight-through cable cable is used to connect a router and a switch
- A  straight-through cable cable connects a pin pair on one end of a UTP cable to the same pair on the other end
- 2 (=4 wires)  pairs of wires are used in a 10BASE-T cable
- Pair 1-2, Pair 3-6, Pair 4-5, pair 7-8 are the   four pin pairs are used in a 1000BASE-T or 10GBASE-T connection

- Auto MDI-X is  the feature that allows a device to automatically adjust which RJ45 pin pairs it uses to transmit and receive data

-10GBASE-ER maximum cable length is 30 kilometers
-1000BASE-LX maximum cable length: 550 meters (multimode)
5 kilometers (single-mode)
-10GBASE-LR maximum cable length: 10 kilometers







# Fiber-optic Connection 
-Single Mode
-Multi mode
--Fiber optic  cables are connected to SFP(small Form-Factor Pluggable) trancivers in a router or a switch 
-Multimode Fiber cables have a wider fiberglass core than single-mode fiber cables.
-Single mode is cheaper that multi mode
-Single mode cables allow longer cables than   multimode cables
-In single mode  fiber cables, light travels straight through the fiberglass core at a single angle.
-Multimode fiber cables allow multiple angles (modes) of light waves to enter the fiberglass core.


| Informal Name | IEEE Standard | Speed | Cable Type | Maximum Length |
|--------------|--------------|-------|-------------|----------------|
| 1000BASE-LX | 802.3z | 1 Gbps | Multimode or Single-Mode | 550 m (MM), 5 km (SM) |
| 10GBASE-SR | 802.3ae | 10 Gbps | Multimode | 400 m |
| 10GBASE-LR | 802.3ae | 10 Gbps | Single-Mode | 10 km |
| 10GBASE-ER | 802.3ae | 10 Gbps | Single-Mode | 30 km |