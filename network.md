| [Home](README.md) | [1. Physical](physical.md) | [2. Data Link](dataLink.md) | [**3. Network**](network.md) | [4. Transport](transport.md) | [5. Session](session.md) | [6. Presentation](presentation.md) | [7. Application](application.md)

# 3. Network Layer
| | Coming from | Going to |
| ----------- | ----------- | ----------- |
| Sending| Transport layer | Data Link layer |
| Recieving| Data Link layer | Network  layer |

- establishes connections between devices
- routes data across a network and between networks
    -  routes data through intermediate devices (routers) to reach its destination on the network
- logical addressing of devices

![image][image1]
<br></br>
Process:
1. data arrives at the Network layer
2. check source and destination addresses in frame if data is at final destination
3. If final destination --> formats data into packets delivered to the Transport layer
4. If not final --> layer updates the destination address and pushes the frame back down to lower layers

[image1]: https://www.lifewire.com/thmb/TnAoUlDGWgixspJK2hM5CCcZhy4=/750x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/layers-of-the-osi-model-illustrated-818017-finalv1-4-ct-9ffde2c7142849819c3fcf5e305a242f.png