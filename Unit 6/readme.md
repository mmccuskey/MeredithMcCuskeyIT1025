# Executive Summary
Include your executive summary here...

# Internet Architecture

## Internet Protocol
* What is an IP address and what is the difference between IPv4 and IPv6?
An IP address is a unique number assigned to a computer or device that is connected to the internet. IPv4 was the original internet protocol. It is a pool of unallocated addresses. IPv6 is the new internet protocol which has a bigger address space since all of the IPv4 unallocated addresses have been allocated to Internet Service Providers and users. IPv4 addresses are written as a string of four numbers between 0 and 255 seperated by dots. IPv6 addresses are much longer and are usually written using hexadecimals. Colons seperate segments of an IPv6 address instead of dots. 

* See ipconfig.png

* The Internet Corporation for Assigned Names and Numbers (ICANN) is coordinates the unique identifying numbers of computers and devices across the world. It is a non-profit dedicated to keeping the internet secure, connected, and operable. It develops policies on the internet protocols such as IPv4 and IPv6. 

## TCP/IP
* TCP/IP stands for Transmission Control Protocol / Internet Protocol. TCP/IP is responsible for defining the details of how data is sent and recieved through network adapters, hubs, switches, routers and other network communications hardware. IP addresses communicate over ports. A port number is a way to identify specific connections between one computer or device and another. TCP/IP protocol creates a virtual IP port that the network hardware and software use to route data in and out of each virtual port.

* TCP/IP utilizes the client-server model. The client would be a computer or device that connects to the server. The client needs to know the IP address of the server as well as the port number. The server then has to accept or reject the connection. Once a connection is made data can be sent back and forth between these two devices through a port. The connection between the client and the server remains open until either the client or server terminates the connection. 

* Layers are important to incorporate into technology because it allows changes to be made to a system relatively easily. Each layer performs a specific function. If someone wanted to go in and change an aspect of that function, being able to identify a single layer and just focus on changing that one or replacing it without affecting the other layers is extremely important.

* Some of the types of applications that run on the application layer of TCP/IP is HTTP (hypertext transfer protocol) as well as some email protocols like SMTP and POP3.

# Internet Security
* Hypertext Transfer Protocol (HTTP) is the protocol that is used to view web pages. HTTP supports the client-server because it is the protocol used by a computer (client) to access a web server. 

* HTTPS was created to protect data by encrypting the data being retrieved by HTTP. This secures data by scrabmling it rendering it unreadable to a hacker who might be trying to steal personal information. HTTPS uses two protocols to secure data. One of them is Secure Sockets Layer (SSL) which is a protocol that uses public key encryption. The client will ask the web server to identify itself and the server will send back an SSL certificate which authenticates the identity of a website. The client decides whether to trust the SSL certificate and if it does, the server and client can start sending encrypted data between each other. The other protocol used is Transport Layer Security (TLS) which is the latest cryptographic standard protocol. It is based on the specifications of SSL and authenticates the server before encrypting data. Many websites use HTTPS now, largely due to Google flagging sites as unsecure if they are not SSL protected and penalizes them in their search results.

* You should secure your web browser because an unsecure browser could lead to a variety of problems from spyware being installed to intruders taking control of your computer. Software attacks that take advantage of vulnerable web browsers have been increasing. In order to protect your computer and personal information, securing your web browser is a smart idea.

* One of the risks described in the article is the vulnerabilities associated with using ActiveX which is a technology used by Microsoft Internet Explorer on Microsoft Windows systems. ActiveX allows applications to be utilized by the web browser. While this increases functionality, it also introduces vulnerabilities that could be exploited through Internet Explorer. Using ActiveX in a web browser increases the attack surface of a system.

# Internet Programming
* See Unit6html.png, Unit6css.png, and Unit6webpage.png

* Tim Berners-Lee is the inventor of the World Wide Web. He wrote the first World Wide Web server and the first client program. He also wrote the first version of HyperText Markup Language (HTML). He created W3C to lead the world wide web to its full potential by developing protocols and guidelines that ensure the long-term growth of the web. 

* The standard that I chose is HTML & CSS. This standard is important because these two languages are used to develop web pages. By having an agreed upon standard, web developers are able to write, edit, view, and understand web pages. Everyone uses the same standards and it consolidates development.

* XML is a markup language similar to HTML. Although similar in many ways, XML and HTML were designed with different goals. XML was designed to carry data while HTML was designed to display data. It is also important to note that XML tags are not predefined like HTML tags are. 

# URLs and File Paths
#### Match the following terms / definitions:
* scheme - https
* domain - www.amazon.com
* top level domain - .edu
* default page - no file path provided
* parameters - result of search 
* anchor - specific location on a page

#### Answer these questions:
* Absolute file paths always include the domain name of a website including https://www. Relative file paths only point to a file or file path. A relative link will take the user to that location on the current site. Absolute links are used to navigate to a different website while relative links are used to navigate to another page or file on the current website. I would use relative file paths in my website because it makes it easier to do things like change my domain name without having to go through all my HTML pages and change the names on all the links. They also keep the website structure neat and organized.

* File compression is used to reduce the size of a file so that it takes up less storage. Compressed files can be transferred to other computers faster than the original uncompressed file. 

# Conclusion
Include your conclusion here...
