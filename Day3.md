# Protocol and Standards 
The IETF publishes standards in documents called RFCs (Requests for Comments)
-The IETF publishes standards in documents called RFCs (Requests for Comments)
-IEEE (Institute of Electrical and Electronics Engineers)  organization defines standards used on local area networks
# TCP/IP protocols

| Layer                | Function |
|-------               |----------|

| Application Layer  | Provides services to end-user applications such as web browsing, email, and file transfer. |

| Transport Layer    | Ensures reliable data transmission, flow control, and error recovery between hosts. |

| Internet Layer      | Handles logical addressing and routing of packets across networks. |

| Network Access (Local N/W) Layer | Manages data framing, MAC addressing, and communication over the local network. |

| Physical Layer       | Transmits raw bits over the physical medium such as cables, fiber optics, or wireless signals. |



# Encapsulation and Decapsulation 
-Encapsulation is the process in which headers and a trailer are added to a message before transmitting it
-Decapsulation (or de-encapsulation) is  the process in which headers and a trailer are removed from a message by the receiving host
# Protocol data Units 
-TCP creates Segments and UDP creates Datagram
-An L4PDU is called a segment or datagram
-The contents of each PDU (everything encapsulated by that layer’s header/trailer) are called the payload
-The payload of a packet (L3PDU) is a segment (TCP) or datagram (UDP) (L4PDU)
-The payload of a segment or datagram (L4PDU) is data (from the Application layer)
-An L2PDU is called a frame
-An L3PDU is called a Packet
-The payload of a frame (L2PDU) is a packet (L3PDU)
# Adjecent Layer Intercation
-Interaction between a layer and those above and below it is called adjacent-layer interaction
# Same Layer Interaction
-Interaction between a layer and the equivalent layer on another device is called  same-layer interaction
# The OSI model 

| Layer No.| OSI Layer | Primary Function |
|-----------|-----------|------------------|
| 7        | Application | Provides network services directly to end-user applications. |
| 6        | Presentation | Translates, encrypts, decrypts, and compresses data. |
| 5        | Session | Establishes, manages, and terminates communication sessions. |
| 4        | Transport | Ensures reliable end-to-end data delivery, flow control, and error recovery. |
| 3        | Network | Determines the best path for data using logical addressing (IP routing). |
| 2        | Data Link | Provides node-to-node communication, MAC addressing, and error detection. |
| 1        | Physical | Transmits raw bits over the physical transmission medium. |