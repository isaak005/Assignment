# Assignment
## 1. Transistor

The discovery of the first transistor in 1948 by a team of physicists at the Bell Telephone Laboratories sparked an interest in solid-state research that spread quickly. The transistor, which began as a simple laboratory oddity, was rapidly developed into a semiconductor device of major importance. The transistor demonstrated for the first time in history that amplification in solids was possible. Before the transistor, amplification was achieved only with electron tubes. Transistors now perform numerous electronic tasks with new and improved transistor designs being continually put on the market. In many cases, transistors are more desirable than tubes because they are small, rugged, require no filament power, and operate at low voltages with comparatively high efficiency.
Semiconductor devices that have three or more elements are called TRANSISTORS. The term transistor was derived from the words TRANSfer and resISTOR. This term was adopted because it best describes the operation of the transistor – the transfer of an input signal current from a low-resistance circuit to a high resistance circuit. Transistors were first used as amplifiers, but their use in digital circuits to create logic gates has driven the computing age.

## 2. Moor’s law

is the observation that, over the history of computing hardware, the number of transistors on integrated circuits doubles approximately every two years. The law is named after Intel co-founder Gorden E. Moore who described the trend in his 1965 paper. His prediction has proven to be accurate, in part because the law is now used in the semiconductor industry to guide long term planning and to set targets for research and development. The period often quoted as “18month’ is due to intel executive David House, who predicted that period for doubling in chips performance (being the effect of more transistors and their being faster). 

## 3. Lambda calculus

Lambda-Calculus (LC) is the model (or language) of computation (i.e. programming).  It is a system that expresses functions as strings of symbols. Lambda-Calculus is about anonymous functions, called lambda expressions (λ-exprs).

## 4. How computers work?

A computer, a digital information-processing machine, works by changing information into binary numbers (ones and zeros) and then using simple mathematics to make decisions about how to rearrange those numbers into words or actions. A digital system stores and operates on information in a very specific way by storing information in a bit (or multiple collections of bits). A bit is a variable that can have only one of two values: it can either be a 1, or be a 0. There are two main things to understanding the basics of how a computer works: • A computer treats any type of information (not only numbers but also letters, words, dates) as if it consisted simply of binary ones and zeros. For example, a computer can translate the letter “A” typed into its keyboard into a string of ones and zeros, such as 1000001. One reason for this is that once it is in a binary form, the information can be stored and moved about more easily. On a hard disc, the “ones” could be stored as magnetized spots on the disc, while the zeroes can be stored as un-magnetized spots. Once information has been converted to ones and zeros, the computer can get to work.
 • The second point to consider is that the computer’s functions are based on the movement and transformation of electrical pulses (representing ones and zeroes) in electrical circuits. Inside the computer are electrical circuits that decode the zeros and ones, by adding and subtracting them. These circuits are called the logic of the computer, because the calculations they make are similar to simple logic decisions. For example, if you press the A key on the computer keyboard, circuits inside the computer receive pulses of electricity representing the A in binary form - 1000001. Those pulses are sent to logic circuits that make yes or no decisions based on the input they receive. A very simple example would be a circuit that determines whether the input send to it is a one or a zero. The output of the circuit is a new piece of information - a binary one or zero that is the result of the simple yes or no decision

## 5. What is DNS?

The DNS is a distributed database across a hierarchy of networks of 
servers and provide ways for devices and software (like browsers and 
email) to query the DNS to get an IP address.

● Domain names must be unique.

● Domain names are used for naming websites and email addresses
Let’s look at a typical domain name.
www.example.com

● “com” is the First Level Domain or Top Level Domain (TLD) 
● “example” is the Second Level Domain
● “www” is the Third Level Domain

## 6. How the Domain System work? 

What happens when I type www.example.com in my browser?
The domain name lookup processȀ
1. You type “www.example.com” into your browser’s address bar.
2. The DNS server queries the “root servers” for the information. N.B. The 
root zone only knows information about the zones they are responsible for 
which is the Top Level Domains (TLDs). There are 13 root servers which 
have copies distributed around the world.
3. The root server will refer the DNS server to the “.com” TLD nameservers . 
The TLD Name servers knows information of all second level domains 
under their zone. 
4. The Top Level Domain Name servers will refer us to the DNS servers 
responsible for “example.com”
5. The DNS servers authoritative for example.com will give us the IP address 
for www.example.com” and the web resource is displayed..
com. - .is the root server oot server 


Every time a DNS query is made, the root servers are the first servers to be 
contacted. However, there is no need to contact the root servers every time 
a query is made since results can be obtained from the DNS cache which 
stores information for recent previous queries. If the DNS server do not find 
the results in the cached copies it asks a series of servers through a process 
called recursion until it reaches the authoritative name servers for that 
domain.
## 7. What is SSL?

SSL, or Secure Sockets Layer, is an encryption-based Internet security protocol. It was first developed by Netscape in 1995 for the purpose of ensuring privacy, authentication, and data integrity in Internet communications. SSL is the predecessor to the modern TLS encryption used today.
A website that implements SSL/TLS has "HTTPS" in its URL instead of "HTTP."
How does SSL/TLS work?
•	In order to provide a high degree of privacy, SSL encrypts data that is transmitted across the web. This means that anyone who tries to intercept this data will only see a garbled mix of characters that is nearly impossible to decrypt.
•	SSL initiates an authentication process called a handshake between two communicating devices to ensure that both devices are really who they claim to be.
•	SSL also digitally signs data in order to provide data integrity, verifying that the data is not tampered with before reaching its intended recipient.
There have been several iterations of SSL, each more secure than the last. In 1999 SSL was updated to become TLS.

## 8.  What is Transport Layer Security (TLS)?
 
 Transport Layer Security, or TLS, is a widely adopted security protocol designed to facilitate privacy and data security for communications over the Internet. A primary use case of TLS is encrypting the communication between web applications and servers, such as web browsers loading a website. TLS can also be used to encrypt other communications such as email, messaging, and voice over IP (VoIP). In this article we will focus on the role of TLS in web application security.
TLS was proposed by the Internet Engineering Task Force (IETF), an international standards organization, and the first version of the protocol was published in 1999. The most recent version is TLS 1.3, which was published in 2018.
What is the difference between TLS and SSL?
TLS evolved from a previous encryption protocol called Secure Sockets Layer (SSL), which was developed by Netscape. TLS version 1.0 actually began development as SSL version 3.1, but the name of the protocol was changed before publication in order to indicate that it was no longer associated with Netscape. Because of this history, the terms TLS and SSL are sometimes used interchangeably.
## 9. What Is Firewall?
Firewalls prevent unauthorized access to networks through software or firmware. By utilizing a set of rules, the firewall examines and blocks incoming and outgoing traffic.
Fencing your property protects your house and keeps trespassers at bay; similarly, firewalls are used to secure a computer network. Firewalls are network security systems that prevent unauthorized access to a network. It can be a hardware or software unit that filters the incoming and outgoing traffic within a private network, according to a set of rules to spot and prevent cyberattacks. 
Firewalls are used in enterprise and personal settings. They are a vital component of network security. Most operating systems have a basic built-in firewall. However, using a third-party firewall application provides better protection.
Hardware firewalls allow you to protect your entire network from the outside world with a single physical device. A software firewall is installed on an individual computer and it protects that single device. If multiple computers need protection, the software must be installed on each device.

## 10. What Is DHCP

DHCP is one of the protocols in Internet Protocol Suite, which is a network management protocol utilized on Internet Protocol networks. What does DHCP stand for? DHCP stands for Dynamic Host Configuration Protocol.
DHCP is a protocol used for assigning dynamic IP addresses to devices on a network. By using dynamic addressing, a device can have a different IP address every time it connects to the network. They can use network services like DNS, NTP, as well as any communication protocol based on UDP or TCP.
 
 ## 11. What Is the OSI Model
 
The Open Systems Interconnection (OSI) model describes seven layers that computer systems use to communicate over a network. It was the first standard model for network communications, adopted by all major computer and telecommunication companies in the early 1980s

The modern Internet is not based on OSI, but on the simpler TCP/IP model. However, the OSI 7-layer model is still widely used, as it helps visualize and communicate how networks operate, and helps isolate and troubleshoot networking problems.

OSI was introduced in 1983 by representatives of the major computer and telecom companies, and was adopted by ISO as an international standard in 1984.
7 layers of the OSI model
What is the function of each layer of the OSI model? The seven Open Systems Interconnection layers are the following.

Layer 7. The application layer
The application layer enables the user -- human or software -- to interact with the application or network whenever the user elects to read messages, transfer files or perform other network-related tasks. Web browsers and other internet-connected apps, such as Outlook and Skype, use Layer 7 application protocols.

Layer 6. The presentation layer
The presentation layer translates or formats data for the application layer based on the semantics or syntax the application accepts. This layer also handles the encryption and decryption that the application layer requires.

Layer 5. The session layer
The session layer sets up, coordinates and terminates conversations between applications. Its services include authentication and reconnection after an interruption. This layer determines how long a system will wait for another application to respond. Examples of session layer protocols include X.225 and Zone Information Protocol (ZIP).

Layer 4. The transport layer
The transport layer is responsible for transferring data across a network and provides error-checking mechanisms and data flow controls. It determines how much data to send, where it gets sent and at what rate. TCP within the TCP/IP suite is the best-known example of the transport layer. This is where the communications select TCP port numbers to categorize and organize data transmissions across a network.

Layer 3. The network layer
The primary function of the network layer is to move data into and through other networks. Network layer protocols accomplish this by packaging data with correct network address information, selecting the appropriate network routes and forwarding the packaged data up the stack to the transport layer. From a TCP/IP perspective, this is where IP addresses are applied for routing purposes.

Layer 2. The data-link layer
The data-link, or protocol layer, in a program handles moving data into and out of a physical link in a network. This layer handles problems that occur as a result of bit transmission errors. It ensures that the pace of the data flow doesn't overwhelm the sending and receiving devices. This layer also permits the transmission of data to Layer 3, the network layer, where it's addressed and routed.

The data-link layer can be further divided into two sublayers. The higher layer, which is called logical link control (LLC), is responsible for multiplexing, flow control, acknowledgement and notifying upper layers if transmit/receive (TX/RX) errors occur.

The media access control sublayer is responsible for tracking data frames using MAC addresses of the sending and receiving hardware. It's also responsible for organizing each frame, marking the starting and ending bits and organizing timing regarding when each frame can be sent along the physical layer medium.

Layer 1. The physical layer
The physical layer transports data using electrical, mechanical or procedural interfaces. This layer is responsible for sending computer bits from one device to another along the network. It determines how physical connections to the network are set up and how bits are represented into predictable signals as they're transmitted either electrically, optically or via radio waves.
