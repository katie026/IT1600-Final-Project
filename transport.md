| [Home](README.md) | [1. Physical](physical.md) | [2. Data Link](dataLink.md) | [3. Network](network.md) | [**4. Transport**](transport.md) | [5. Session](session.md) | [6. Presentation](presentation.md) | [7. Application](application.md)

# 4. Transport Layer
| | Coming from | Going to |
| ----------- | ----------- | ----------- |
| Sending| Session Layer | Network layer |
| Recieving| Network layer | Session Layer |

- provides reliable, end-to-end communication between devices on a network
- establishes/maintains connections between devices
    - delivers data across those connections
- ensures  data is delivered reliably and in the correct order
- divides data into smaller units (segments)
    - pass segments down to network layer for routing
    - reassembles incoming segments back into the original data
- TCP (Transmission Control Protocol) and UDP (User Datagram Protocol) are the most common protocols
    - Different protocols support a range of optional capabilities (ex. error recovery, flow/congestion control, re-transmission, error detection/correction)

![image][image1]
<br></br>
## TCP vs. UDP
|  | Reliable | Best-Effort |
| ----------- | ----------- | ----------- |
| Connection Type | Conection-oriented | Connectionless |
| Protocol | TCP | UDP |
| Sequencing | Yes | No |
| Uses | Email, file sharing, downloading | Voice/video streaming |
<br></br>

| TCP | UDP |
| ----------- | ----------- |
| Small packet sizes | Larger packet sizes |
| 8-byte header | 20-byte header |
| No connection | 3-way handshake |
| More control when data is sent | Less contorl when data is sent (due to retransmission and congestion control) |
| Primitive error-detection, unreliable checksum | Delivery acknowledgements, error-detection, retransmission, in-order delivery |
| no congestion control | congestion control |
| no corruption recovery | corruption recovery |
| blocked by some firewalls |  |

[image1]: https://www.lifewire.com/thmb/HKAzCXrgywQyF6xWNCjL5df3yGU=/750x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/layers-of-the-osi-model-illustrated-818017-final-5-ct-373fc5a9edc74359819021555f37467d.png