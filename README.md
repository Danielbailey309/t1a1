# Assignment 1: Workbook
## Question 1
The five key elements of the development of the internet since the 1980s are:

1. Arpanet computers switch to Transmission Control Protocols/Internet Protocols (TCP/IP) in 1983
1. The Domain Name System (DNS) is invented in 1984
1. The first commercial dial-up system is released in 1990
1. Tim Berners-Lee invents the world wide web in 1991
1. The first internet browser with a graphical interface, known as Erwise, is created in 1992 


### **Arpanet switches to TCP/IP**
Arpanet was the US government's network of computers created in the 1960s and the predecessor to the internet as we know it today. In 1983, the Arpanet switched to the **Transmission Control Protocols/Internet Protocols (TCP/IP)** proposed in the 70s. These protocols dictated how internet packets were moved over a network and how computers sent and received these packets.


### **The Domain Name System is invented**
The **Domain Name System (DNS)** is a system for allocating computers domain names, rather than simply IP addresses. These domain names were much more user friendly as they allowed users to type in easily remembered names rather than complex IP addresses in order to contact servers.


### **The first commercial dial-up system is released in 1990**
**Dial-up** is a system of internet access where internet users can connect to their service provider through a telephone line. This system provided internet access to people outside of the government network and, as the internet grew, people around the world had access to the internet.


### **Tim Berners-Lee invents the World Wide Web in 1991**
The **World Wide Web (WWW)** is a collection of webpages found on the internet. It allows the average user access to a vast amount of content, from videos to audio to information files. It was invented by Tim Berners-Lee as a way for multiple scientists to share their findings and is vital to the development of the internet because most internet users today use the internet to browse the web.


### **Erwise, the first internet browser with a graphical interface, is created in 1992**
**Internet Browsers** with graphical user interfaces (GUIs), provide navigation of the web through buttons, text boxes, clickable links and more. They first appeared in 1992 with the creation of Erwise. Though many internet browsers with GUIs would appear later and become more popular, the design prototyped by Erwise made the internet much more accessible to the average user.

## Question 2
In this section, the following terms will be defined, and their impact on the development of the internet will be explained
- Packets
- IP addresses (IPv4 and IPv6)
- Routers and routing
- Domain and DNS

### **Packets**
A packet is a segment of data travelling over a network, such as the internet. Within this packet is the address for the sender and receiver, the packet's position in terms of when it was sent (for example whether it was sent first, second, third etc.) as well as the contents of the packet itself. The invention of packets was important to the development of the internet because it allowed many packets to be sent at once with small amounts of information, to take any path to the destination and arrive out of order, but still allow the contents of the packets to be read when all have reached their destination. This takes up less bandwidth on the networks than sending all the information at once through the same network, and thus greatly increases the speed and accuracy that data can be sent along the internet.

### **IP addresses (IPv4 and IPv6)**
IP adresses provide the means for packets to be sent and arrive at their destinations. They tell the packets exactly where to go on any network, whether local or on the internet, in the form of a numerical address unique to each device on the network. These numerical addresses are either 32 bits, for IPv4 addresses, or 128 bits, in the case of IPv6 addresses. All of the 32 bit IPv4 addresses have already been allocated, and thus are slowly being replaced by the 128 bit IPv6 addresses to give each device a unique identifier even between servers and make it easier and smoother for packets to reach their destination. These addresses are essential to the development of the internet because they assist the packets in delivering data to a huge amount of unique devices all around the world at any given time.

### **Routers and routing**
Routers are devices that are used by computers in a local network, generally a home network, to connect to the internet. The router assigns an IP address to each computer on the network and any packets that are sent between the computers on the network and the internet have to pass through the router. The router therefore functions as a firewall of sorts, allowing trusted devices from within the network to communicate freely but blocking connections from outside the network without permission. Routers are essential to the development of the internet because they provide protection to users of the internet from other computers on the internet.

### **Domains and DNS**
As described in Question 1, domain names are names that correspond to IP addresses on a network, such as [www.google.com](https://www.google.com/) or [www.wikipedia.org](https://www.wikipedia.org/). The Domain Name System (DNS) is the computer's way of finding the IP address that corresponds to a given domain name, such as the IP address 8.8.8.8 for in the case of www.google.com. Domains and the Domain Name System were vital in the development of the internet in that they are a convenient and easy-to-remember way for the average internet user to access most web pages without having to lookup the IP addresses associated with them.

## Question 3
This section will define the following technologies and explain their contribution to the development of client and server communication over the internet
- Transmission Control Protocol (TCP)
- HyperText Transfer Protocol (HTTP) and HyperText Transfer Protocol Secure (HTTPS)
- Web browsers (requests, rendering and development tools)

### **TCP**
Transmission Control Protocol or TCP works in conjunction with Internet Protocols (IPs) to transfer packets over the internet. While IP tells packets where to go in terms of their source and destination, TCP controls the packets upon arrival at their destination. TCP makes sure that all packets are received and tells the sender when each packet is received. It checks the packets and puts them in order that the data should be opened, rather than the order they were received. This makes it easier for clients and servers to communicate because data can be separated into smaller packets to cause less stress on networks. Additionally, these packets can travel on any network depending on which is most effective at getting that specific packet to it's destination, rather than having to send all packets on the same network or risk the data being unusable if it's received out of order.

### **HTTP and HTTPS**
HyperText Transfer Protocol (also known as HTTP) is a network protocol standard created in the early 1990s that allows computers and servers to communicate by exchanging data. This protocol focuses on delivering information without concern for how the data travels over the network or whether it is accessed during transit. This means that the connection is vulnerable to others opening, reading and adjusting the data within.

HyperText Transfer Protocol Secure (HTTPS) is the same as HTTP but is secured by Transport Layer Security (TLS) allowing it to create a secure connection between the web server and the user's web browser. This connection ensures that the data can't be read or tampered with during transit.

The development of both of these technologies means that users can send their credentials to banks and online shopping websites over the internet and not have to worry about their data being read or altered (so long as the site is secured with a HTTPS connection).

### **Web Browsers**
A web browser is an application that is run on a user's desktop or mobile device to explore the internet. The web browser requests information from the URL input by the user, and the web browser renders the information using it's rendering engine. These web browsers also contain web development tools, that provide an interface to view the code run on the web page alongside the web page itself.

Web browsers have proven invaluable to the development of the internet because they provide the average web user with an interface for displaying web pages that is both easy to use and navigate. Additionally, it allows web developers a more detailed view of how their code runs and where errors are occurring, as well as letting them see how code works on any website and giving them the opportunity to adapt it to their own.