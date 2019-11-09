# Networks
Networks Notes

## Layers in Networking

Computer architectures are layered to simplify design and implementation

- L1 Physical Layer: Transfers bits across a link like Ethernet, Modem 
- L2 Data link layer: 

Time required to transmit a message depends on number of bits in image and how fast network can transfer. Information in blocks like images, text are measured in bits while information in streams like voice/video calls are measured in bits-per-second

## Transport Layer

L3 Network layer uses connectionless IP for transmission. L4 and higher protocols are expected to provide reliability and ordering

#### TCP
- Creates connection
- Provides acknowledgement of sent packets and resends lost
- Has flow control
- HTTP / FTP use TCP

#### UDP
- Connectionless protocol
- Doesn't acknowledge sent packets. Depends on higher layers.
- Used in video and voice streaming
- No flow control. Receiver might drop packets


#### Communication Delay
Communication delay = Transmission delay + Propagation delay

- Transmission delay: Time to get data into the wire = packet length / data rate
- Propagation delay: Time to transfer packet over network = distance / speed

Communication delay can be reduced by data compression, using higher bandwidth router.

Data compression
- NoiseLess: zip, GIF
- Noisy: JPEG
