| [Home](README.md) | [1. Physical](physical.md) | [2. Data Link](dataLink.md) | [3. Network](network.md) | [4. Transport](transport.md) | [5. Session](session.md) | [6. Presentation](presentation.md) | [**7. Application**](application.md)

# 7. Application Layer
| | Coming from | Going to |
| ----------- | ----------- | ----------- |
| Sending| User on PC | Presentation layer |
| Recieving| Presentation layer | User on PC |

- topmost layer of the OSI model (closest to the user)
- ensures the application the user interact with can communciate with the applications that are on other computers/networks

![Application Layer Picture][image1]

*TDLR: the layer where the user interacts with the network, and it enables applications to access the network's resources and services*

Functions:
- can enable authentication between devices for an extra layer of network security;
- ensures interfaces between sending and receivng computers are there (ex. Ethernet, Wi-Fi)
- ensures agreement at both ends on error recovery procedures, data integrity and privacy
- determines protocol and data syntax rules for the application level
- presents the data on the receiving end to the user application

<br></br>
**Network services:** protocols that work with the user's data

Ptotocol Examples:
- Hypertext Transfer Protocol (HTTP): in a web browser application it packages the data needed to send and receive web page content
- File Transfer Protocol (FTP)
- Post Office Protocol (POP)
- Simple Mail Transfer Protocol (SMTP)
- Domain Name System (DNS)

<br></br>
Source: [techtarget.com](https://www.techtarget.com/searchnetworking/definition/Application-layer#:~:text=The%20application%20layer%20sits%20at,layer%20is%20not%20an%20application)




[image1]: https://www.lifewire.com/thmb/ibtZwvrxNPf2tdBI8wobKb2o5eQ=/750x0/filters:no_upscale():max_bytes(150000):strip_icc():format(webp)/layers-of-the-osi-model-illustrated-818017-finalv1-8-ct-089b2573bf47462d85f9343f50329f72.png