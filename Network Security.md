------------

----------------

# Module 1: Understand Computer Networking:-

----------------------

---------------

## 1.What is Networking

- A network is simply two or more computers linked together to share data, information or resources.

- To properly establish secure data communications, it is important to explore all of the technologies involved in computer communications. From hardware and software to protocols and encryption and beyond, there are many details, standards and procedures to be familiar with.

## Types of Networks

There are two basic types of networks:

- **Local area network (LAN)** - A local area network (LAN) is a network typically spanning a single floor or building. This is commonly a limited geographical area.
- **Wide area network (WAN**) - Wide area network (WAN) is the term usually assigned to the long-distance connections between geographically remote networks.

## Network Devices

- Hub:-Hubs are used to connect multiple devices in a network. They’re less likely to be seen in business or corporate networks than in home networks. Hubs are wired devices and are not as smart as switches or routers.
- Switch:-Rather than using a hub, you might consider using a switch, or what is also known as an intelligent hub. Switches are wired devices that know the addresses of the devices connected to them and route traffic to that port/device rather than retransmitting to all devices.
  Offering greater efficiency for traffic delivery and improving the overall throughput of data, switches are smarter than hubs, but not as smart as routers. Switches can also create separate broadcast domains when used to create VLANs, which will be discussed later.
- Router:-Routers are used to control traffic flow on networks and are often used to connect similar networks and control traffic flow between them. Routers can be wired or wireless and can connect multiple switches. Smarter than hubs and switches, routers determine the most efficient “route” for the traffic to flow across the network.
- Firewall:-Firewalls are essential tools in managing and controlling network traffic and protecting the network. A firewall is a network device used to filter traffic. It is typically deployed between a private network and the internet, but it can also be deployed between departments (segmented networks) within an organization (overall network). Firewalls filter traffic based on a defined set of rules, also called filters or access control lists.
- Server:-A server is a computer that provides information to other computers on a network. Some common servers are web servers, email servers, print servers, database servers and file servers. All of these are, by design, networked and accessed in some way by a client computer. Servers are usually secured differently than workstations to protect the information they contain.
- Endpoint:-Endpoints are the ends of a network communication link. One end is often at a server where a resource resides, and the other end is often a client making a request to use a network resource. An endpoint can be another server, desktop workstation, laptop, tablet, mobile phone or any other end user device.

## Other Networking Terms

### Ethernet!

Ethernet (IEEE 802.3) is a standard that defines wired connections of networked devices. This standard defines the way data is formatted over the wire to ensure disparate devices can communicate over the same cables.

### Device Address

- **Media Access Control (MAC) Address** - Every network device is assigned a Media Access Control (MAC) address. An example is 00-13-02-1F-58-F5. The first 3 [bytes](https://learn.isc2.org/content/enforced/9541-CC-SPT-GLOBAL-1ED-1M/build/chapter_04/module_01/ch04_m01-What_is_Networking.html?d2lSessionVal=CJ6sVeDzymb7UWTGXa1nid30D&ou=9541&d2l_body_type=3#) (24 bits) of the address denote the vendor or manufacturer of the physical network interface. No two devices can have the same MAC address in the same local network; otherwise an address conflict occurs.
- **Internet Protocol (IP) Address** - While MAC addresses are generally assigned in the firmware of the interface, IP hosts associate that address with a unique logical address. This logical IP address represents the network interface within the network and can be useful to maintain communications when a physical device is swapped with new hardware. Examples are 192.168.1.1 and 2001:db8::ffff:0:1.

-------------------------------

--------------

## 2.Networking at a Glance

- This diagram represents a small business network, which we will build upon during this lesson. The lines depict wired connections. Notice how all devices behind the firewall connect via the network switch, and the firewall lies between the network switch and the internet. 

- The network diagram below represents a typical home network. Notice the primary difference between the home network and the business network is that the router, firewall, and network switch are often combined into one device supplied by your internet provider and shown here as the wireless access point. 

--------------------------

---------

## 3.Networking Models

- Many different models, architectures and standards exist that provide ways to interconnect different hardware and software systems with each other for the purposes of sharing information, coordinating their activities and accomplishing joint or shared tasks.

- Computers and networks emerge from the integration of communication devices, storage devices, processing devices, security devices, input devices, output devices, operating systems, software, services, data and people.

- Translating the organization’s security needs into safe, reliable and effective network systems needs to start with a simple premise. The purpose of all communications is to exchange information and ideas between people and organizations so that they can get work done.

- Those simple goals can be re-expressed in network (and security) terms such as:

- Provide reliable, managed communications between hosts (and users)
- Isolate functions in layers
- Use [packets]
- Standardize routing, addressing and control
- Allow layers beyond internetworking to add functionality
- Be vendor-agnostic, scalable and resilient

-------------------

------------

## 4.Open Systems Interconnection (OSI) Model

- The OSI Model was developed to establish a common way to describe the communication structure for interconnected computer systems. The OSI model serves as an abstract framework, or theoretical model, for how protocols should function in an ideal world, on ideal hardware. Thus, the OSI model has become a common conceptual reference that is used to understand the communication of various hierarchical components from software interfaces to physical hardware.

- The OSI model divides networking tasks into seven distinct layers. Each layer is responsible for performing specific tasks or operations with the goal of supporting data exchange (in other words, network communication) between two computers. The layers are interchangeably referenced by name or layer number. For example, Layer 3 is also known as the Network Layer. The layers are ordered specifically to indicate how information flows through the various levels of communication. Each layer communicates directly with the layer above and the layer below it. For example, Layer 3 communicates with both the Data Link (2) and Transport (4) layers.

- The Application, Presentation, and Session Layers (5-7) are commonly referred to simply as data. However, each layer has the potential to perform encapsulation. Encapsulation is the addition of header and possibly a footer (trailer) data by a protocol used at that layer of the OSI model. Encapsulation is particularly important when discussing Transport, Network and Data Link layers (2-4), which all generally include some form of header. At the Physical Layer (1), the data unit is converted into binary, i.e., 01010111, and sent across physical wires such as an ethernet cable.  

- It's worth mapping some common networking terminology to the OSI Model so you can see the value in the conceptual model.

Consider the following examples: 

- When someone references an image file like a JPEG or PNG, we are talking about the Presentation Layer (6). 
- When discussing logical ports such as NetBIOS, we are discussing the Session Layer (5).
- When discussing TCP/UDP, we are discussing the Transport Layer (4).
- When discussing routers sending packets, we are discussing the Network Layer (3). 
- When discussing switches, bridges or WAPs sending frames, we are discussing the Data Link Layer (2). 

- Encapsulation occurs as the data moves down the OSI model from Application to Physical. As data is encapsulated at each descending layer, the previous layer’s header, payload and footer are all treated as the next layer’s payload. The data unit size increases as we move down the conceptual model and the contents continue to encapsulate.    
   
- The inverse action occurs as data moves up the OSI model layers from Physical to Application. This process is known as de-encapsulation or decapsulation. The header and footer are used to properly interpret the data payload and are then discarded. As we move up the OSI model, the data unit becomes smaller. The encapsulation/de-encapsulation process is best depicted visually below: 

----------------------

-------------

## 5.Transmission Control Protocol/Internet Protocol (TCP/IP)

- The OSI model wasn’t the first or only attempt to streamline networking protocols or establish a common communications standard. In fact, the most widely used protocol today, TCP/IP, was developed in the early 1970s. The OSI model was not developed until the late 1970s. The TCP/IP protocol stack focuses on the core functions of networking.  

|   |   |
|---|---|
|**TCP/IP Protocol Architecture Layers**|   |
|Application Layer|Defines the protocols for the transport layer.|
|Transport Layer|Permits data to move among devices.|
|Internet Layer|Creates/inserts packets.|
|Network Interface Layer|How data moves through the network.|

  

- The most widely used protocol suite is TCP/IP, but it is not just a single protocol; rather, it is a protocol stack comprising dozens of individual protocols. TCP/IP is a platform-independent protocol based on open standards. However, this is both a benefit and a drawback. TCP/IP can be found in just about every available operating system, but it consumes a significant amount of resources and is relatively easy to hack into because it was designed for ease of use rather than for security.

## Transmission Control Protocol/Internet Protocol (TCP/IP)

- At the Application Layer, TCP/IP protocols include Telnet, File Transfer Protocol (FTP), Simple Mail Transport Protocol (SMTP), and Domain Name Service (DNS).

- The two primary Transport Layer protocols of TCP/IP are TCP and UDP. TCP is a full-duplex connection-oriented protocol, whereas UDP is a simplex connectionless protocol. In the Internet Layer, Internet Control Message Protocol (ICMP) is used to determine the health of a network or a specific link. ICMP is utilized by ping, traceroute and other network management tools. The ping utility employs ICMP echo packets and bounces them off remote systems. Thus, you can use ping to determine whether the remote system is online, whether the remote system is responding promptly, whether the intermediary systems are supporting communications, and the level of performance efficiency at which the intermediary systems are communicating.

----------------

-------------

## 6. Internet Protocol (IPv4 and IPv6)

- IP is currently deployed and used worldwide in two major versions. IPv4 provides a 32-bit address space, which by the late 1980s was projected to be exhausted. IPv6 was introduced in December 1995 and provides a 128-bit address space along with several other important features. 

- IP hosts/devices associate an address with a unique logical address. An IPv4 address is expressed as four octets separated by a dot (.), for example, 216.12.146.140. Each octet may have a value between 0 and 255. However, 0 is the network itself (not a device on that network), and 255 is generally reserved for broadcast purposes. Each address is subdivided into two parts: the network number and the host. The network number assigned by an external organization, such as the Internet Corporation for Assigned Names and Numbers (ICANN), represents the organization’s network. The host represents the network interface within the network.  

- To ease network administration, networks are typically divided into subnets. Because subnets cannot be distinguished with the addressing scheme discussed so far, a separate mechanism, the subnet mask, is used to define the part of the address used for the subnet. The mask is usually converted to decimal notation like 255.255.255.0.  

- With the ever-increasing number of computers and networked devices, it is clear that IPv4 does not provide enough addresses for our needs. To overcome this shortcoming, IPv4 was sub-divided into public and private address ranges. Public addresses are limited with IPv4, but this issue was addressed in part with private addressing. Private addresses can be shared by anyone, and it is highly likely that everyone on your street is using the same address scheme.  

- The nature of the addressing scheme established by IPv4 meant that network designers had to start thinking in terms of IP address reuse. IPv4 facilitated this in several ways, such as its creation of the private address groups; this allows every LAN in every SOHO (small office, home office) situation to use addresses such as 192.168.2.xxx for its internal network addresses, without fear that some other system can intercept traffic on their LAN.

## Internet Protocol (IPv4 and IPv6)

- This table shows the private addresses available for anyone to use:

- Range 
- 10.0.0.0 to 10.255.255.254 
- 172.16.0.0 to 172.31.255.254 
- 192.168.0.0 to 192.168.255.254
- The first octet of 127 is reserved for a computer’s loopback address. Usually, the address 127.0.0.1 is used. The loopback address is used to provide a mechanism for self-diagnosis and troubleshooting at the machine level. This mechanism allows a network administrator to treat a local machine as if it were a remote machine and ping the network interface to establish whether it is operational.

- IPv6 is a modernization of IPv4, which addressed a number of weaknesses in the IPv4 environment:

- A much larger address field: IPv6 addresses are 128 bits, which supports 2128 or 340,282,366,920,938,463,463,374,607,431,768,211,456 hosts. This ensures that we will not run out of addresses.
- Improved security: IPsec is an optional part of IPv4 networks, but a mandatory component of IPv6 networks. This will help ensure the integrity and confidentiality of IP packets and allow communicating partners to authenticate with each other.
- Improved quality of service (QoS): This will help services obtain an appropriate share of a network’s bandwidth.
- An IPv6 address is shown as 8 groups of four digits. Instead of numeric (0-9) digits like IPv4, IPv6 addresses use the hexadecimal range (0000-ffff) and are separated by colons (:) rather than periods (.). An example IPv6 address is 2001:0db8:0000:0000:0000:ffff:0000:0001. To make it easier for humans to read and type, it can be shortened by removing the leading zeros at the beginning of each field and substituting two colons (::) for the longest consecutive zero fields. All fields must retain at least one digit. After shortening, the example address above is rendered as 2001:db8::ffff:0:1, which is much easier to type. As in IPv4, there are some addresses and ranges that are reserved for special uses:

- ::1 is the local loopback address, used the same as 127.0.0.1 in IPv4.
- The range 2001:db8:: to 2001:db8:ffff:ffff:ffff:ffff:ffff:ffff is reserved for documentation use, just like in the examples above.
- fc00:: to fdff:ffff:ffff:ffff:ffff:ffff:ffff:ffff are addresses reserved for internal network use and are not routable on the internet.

------------------

-------------------

## 7.What is WiFi?

- Wireless networking is a popular method of connecting corporate and home systems because of the ease of deployment and relatively low cost. It has made networking more versatile than ever before. Workstations and portable systems are no longer tied to a cable but can roam freely within the signal range of the deployed wireless access points. However, with this freedom comes additional vulnerabilities.

- Wi-Fi range is generally wide enough for most homes or small offices, and range extenders may be placed strategically to extend the signal for larger campuses or homes. Over time the Wi-Fi standard has evolved, with each updated version faster than the last.  

- In a LAN, threat actors need to enter the physical space or immediate vicinity of the physical media itself. For wired networks, this can be done by placing sniffer taps onto cables, plugging in USB devices, or using other tools that require physical access to the network. By contrast, wireless media intrusions can happen at a distance. 

------------

-------

## 8. Security of the Network 

TCP/IP’s vulnerabilities are numerous. Improperly implemented TCP/IP stacks in various operating systems are vulnerable to various DoS/DDoS aatcks, fragment attacks, oversized packet attacks, spoofing attacks, and man-in-the-middle attacks.

TCP/IP (as well as most protocols) is also subject to passive attacks via monitoring or sniffing. Network monitoring, or sniffing, is the act of monitoring traffic patterns to obtain information about a network. 

----------

---------------

## 9. Ports and Protocols (Applications/Services)

There are physical ports that you connect wires to and logical ports that determine where the data/traffic goes. 


Physical Ports:-

Physical ports are the ports on the routers, switches, servers, computers, etc. that you connect the wires, e.g., fiber optic cables, Cat5 cables, etc., to create a network.

Logical Ports:-

When a communication connection is established between two systems, it is done using ports. A logical port (also called a socket) is little more than an address number that both ends of the communication link agree to use when transferring data. Ports allow a single IP address to be able to support multiple simultaneous communications, each using a different port number. In the Application Layer of the TCP/IP model (which includes the Session, Presentation, and Application Layers of the OSI model) reside numerous application- or service-specific protocols. Data types are mapped using port numbers associated with services. For example, web traffic (or HTTP) is port 80. Secure web traffic (or HTTPS) is port 443. Table 5.4 highlights some of these protocols and their customary or assigned ports. You’ll note that in several cases a service (or protocol) may have two ports assigned, one secure and one insecure. When in doubt, systems should be implemented using the most secure version as possible of a protocol and its services.

- Well-known ports (0–1023): These ports are related to the common protocols that are at the core of the Transport Control Protocol/Internet Protocol (TCP/IP) model, Domain Name Service (DNS), Simple Mail Transfer Protocol (SMTP), etc.
- Registered ports (1024–49151): These ports are often associated with proprietary applications from vendors and developers. While they are officially approved by the Internet Assigned Numbers Authority (IANA), in practice many vendors simply implement a port of their choosing. Examples include Remote Authentication Dial-In User Service (RADIUS) authentication (1812), Microsoft SQL Server (1433/1434) and the Docker REST API (2375/2376).
- Dynamic or private ports (49152–65535): Whenever a service is requested that is associated with well-known or registered ports, those services will respond with a dynamic port that is used for that session and then released.

----------------

------------

-------

----------

# Module 2: Understand Network (Cyber) Threats and Attacks:-

------------

----------------

## 1.Types of Threats

- There are many types of cyber threats to organizations. Below are several of the most common types:

	1. Spoofing:-An attack with the goal of gaining access to a target system through the use of a falsified identity. Spoofing can be used against IP addresses, MAC address, usernames, system names, wireless network SSIDs, email addresses, and many other types of logical identification.
	2. Phishing:-An attack that attempts to misdirect legitimate users to malicious websites through the abuse of URLs or hyperlinks in emails could be considered phishing.
	3. DOS/DDOS:-A denial-of-service (DoS) attack is a network resource consumption attack that has the primary goal of preventing legitimate activity on a victimized system. Attacks involving numerous unsuspecting secondary victim systems are known as distributed denial-of-service (DDoS) attacks. 
	4. Virus:-The computer virus is perhaps the earliest form of malicious code to plague security administrators. As with biological viruses, computer viruses have two main functions—propagation and destruction. A virus is a self-replicating piece of code that spreads without the consent of a user, but frequently with their assistance (a user has to click on a link or open a file).
	5. Worm:-Worms pose a significant risk to network security. They contain the same destructive potential as other malicious code objects with an added twist—they propagate themselves without requiring any human intervention.
	6. Trojan:-Named after the ancient story of the Trojan horse, the Trojan is a software program that appears benevolent but carries a malicious, behind-the-scenes payload that has the potential to wreak havoc on a system or network. For example, ransomware often uses a Trojan to infect a target machine and then uses encryption technology to encrypt documents, spreadsheets and other files stored on the system with a key known only to the malware creator.
	7. On-path Attack:-In an on-path attack, attackers place themselves between two devices, often between a web browser and a web server, to intercept or modify information that is intended for one or both of the endpoints. On-path attacks are also known as man-in-the-middle (MITM) attacks.
	8. Side-channel:-A side-channel attack is a passive, noninvasive attack to observe the operation of a device. Methods include power monitoring, timing and fault analysis attacks.
	9. Advanced Persistent Threat(APT):-Advanced persistent threat (APT) refers to threats that demonstrate an unusually high level of technical and operational sophistication spanning months or even years. APT attacks are often conducted by highly organized groups of attackers.
	10. Insider Threat:-Insider threats are threats that arise from individuals who are trusted by the organization. These could be disgruntled employees or employees involved in espionage. Insider threats are not always willing participants. A trusted user who falls victim to a scam could be an unwilling insider threat.
	11. Malware:-A program that is inserted into a system, usually covertly, with the intent of compromising the confidentiality, integrity or availability of the victim’s data, applications or operating system or otherwise annoying or disrupting the victim.
	12. Ransomware:-Malware used for the purpose of facilitating a ransom attack. Ransomware attacks often use cryptography to “lock” the files on an affected computer and require the payment of a ransom fee in return for the “unlock” code.

-------------------

------------

## 2.Intrusion Detection System (IDS)

- An intrusion occurs when an attacker is able to bypass or thwart security mechanisms and gain access to an organization’s resources. Intrusion detection is a specific form of monitoring that monitors recorded information and real-time events to detect abnormal activity indicating a potential incident or intrusion. An intrusion detection system (IDS) automates the inspection of logs and real-time system events to detect intrusion attempts and system failures. An IDS is intended as part of a defense-in-depth security plan. It will work with, and complement, other security mechanisms such as firewalls, but it does not replace them. 

- IDSs can recognize attacks that come from external connections, such as an attack from the internet, and attacks that spread internally, such as a malicious worm. Once they detect a suspicious event, they respond by sending alerts or raising alarms. A primary goal of an IDS is to provide a means for a timely and accurate response to intrusions. 

- Intrusion detection and prevention refer to capabilities that are part of isolating and protecting a more secure or more trusted domain or zone from one that is less trusted or less secure. These are natural functions to expect of a firewall, for example.  

- IDS types are commonly classified as host-based and network-based. A host-based IDS (HIDS) monitors a single computer or host. A network-based IDS (NIDS) monitors a network by observing network traffic patterns. 

## Host-based Intrusion Detection System (HIDS)

- A HIDS monitors activity on a single computer, including process calls and information recorded in system, application, security and host-based firewall logs. It can often examine events in more detail than a NIDS can, and it can pinpoint specific files compromised in an attack. It can also track processes employed by the attacker. A benefit of HIDSs over NIDSs is that HIDSs can detect anomalies on the host system that NIDSs cannot detect. For example, a HIDS can detect infections where an intruder has infiltrated a system and is controlling it remotely. HIDSs are more costly to manage than NIDSs because they require administrative attention on each system, whereas NIDSs usually support centralized administration. A HIDS cannot detect network attacks on other systems.

## Network Intrusion Detection System (NIDS)

- A NIDS monitors and evaluates network activity to detect attacks or event anomalies. It cannot monitor the content of encrypted traffic but can monitor other packet details. A single NIDS can monitor a large network by using remote sensors to collect data at key network locations that send data to a central management console. These sensors can monitor traffic at routers, firewalls, network switches that support port mirroring, and other types of network taps. A NIDS has very little negative effect on the overall network performance, and when it is deployed on a single-purpose system, it doesn’t adversely affect performance on any other computer. A NIDS is usually able to detect the initiation of an attack or ongoing attacks, but they can’t always provide information about the success of an attack. They won’t know if an attack affected specific systems, user accounts, files or applications.

## Security Information and Event Management (SIEM)

- Security management involves the use of tools that collect information about the IT environment from many disparate sources to better examine the overall security of the organization and streamline security efforts. These tools are generally known as security information and event management (or S-I-E-M, pronounced “SIM”) solutions. The general idea of a SIEM solution is to gather log data from various sources across the enterprise to better understand potential security concerns and apportion resources accordingly.

- SIEM systems can be used along with other components (defense-in-depth) as part of an overall information security program.

---------------

----------------

## 3. Preventing Threats:-

## Antivirus

- The use of antivirus products is strongly encouraged as a security best practice and is a requirement for compliance with the Payment Card Industry Data Security Standard (PCI DSS). There are several antivirus products available, and many can be deployed as part of an enterprise solution that integrates with several other security products.

- Antivirus systems try to identify malware based on the signature of known malware or by detecting abnormal activity on a system. This identification is done with various types of scanners, pattern recognition and advanced machine learning algorithms.

- Anti-malware now goes beyond just virus protection as modern solutions try to provide a more holistic approach detecting rootkits, ransomware and spyware. Many endpoint solutions also include software firewalls and IDS or IPS systems.

## Firewalls

- In building construction or vehicle design, a firewall is a specially built physical barrier that prevents the spread of fire from one area of the structure to another or from one compartment of a vehicle to another. Early computer security engineers borrowed that name for the devices and services that isolate network segments from each other, as a security measure. As a result, firewalling refers to the process of designing, using or operating different processes in ways that isolate high-risk activities from lower-risk ones.

- Firewalls enforce policies by filtering network traffic based on a set of rules. While a firewall should always be placed at internet gateways, other internal network considerations and conditions determine where a firewall would be employed, such as network zoning or segregation of different levels of sensitivity. Firewalls have rapidly evolved over time to provide enhanced security capabilities. This growth in capabilities can be seen in Figure 5.37, which contrasts an oversimplified view of traditional and next-generation firewalls. It integrates a variety of threat management capabilities into a single framework, including proxy services, intrusion prevention services (IPS) and tight integration with the identity and access management (IAM) environment to ensure only authorized users are permitted to pass traffic across the infrastructure. While firewalls can manage traffic at Layers 2 (MAC addresses), 3 (IP ranges) and 7 application programming interface (API) and application firewalls), the traditional implementation has been to control traffic at Layer 4.

## Intrusion Prevention System (IPS)

- An intrusion prevention system (IPS) is a special type of active IDS that automatically attempts to detect and block attacks before they reach target systems. A distinguishing difference between an IDS and an IPS is that the IPS is placed in line with the traffic. In other words, all traffic must pass through the IPS and the IPS can choose what traffic to forward and what traffic to block after analyzing it. This allows the IPS to prevent an attack from reaching a target. Since IPS systems are most effective at preventing network-based attacks, it is common to see the IPS function integrated into firewalls. Just like IDS, there are Network-based IPS (NIPS) and Host-based IPS (HIPS).

------------

--------------

# Module 3: Understand Network Security Infrastructure:-

-----------------

------------

## 1.Redundancy

The concept of redundancy is to design systems with duplicate components so that if a failure were to occur, there would be a backup. This can apply to the data center as well. Risk assessments pertaining to the data center should identify when multiple separate utility service entrances are necessary for redundant communication channels and/or mechanisms.  

If the organization requires full redundancy, devices should have two power supplies connected to diverse power sources. Those power sources would be backed up by batteries and generators. In a high-availability environment, even generators would be redundant and fed by different fuel types. 


## 2.Memorandum of Understanding (MOU)/Memorandum of Agreement (MOA) 

- Some organizations seeking to minimize downtime and enhance BC (Business Continuity) and DR (Disaster Recovery) capabilities will create agreements with other, similar organizations. They agree that if one of the parties experiences an emergency and cannot operate within their own facility, the other party will share its resources and let them operate within theirs in order to maintain critical functions. These agreements often even include competitors, because their facilities and resources meet the needs of their particular industry. 

- For example, Hospital A and Hospital B are competitors in the same city. The hospitals create an agreement with each other: if something bad happens to Hospital A (a fire, flood, bomb threat, loss of power, etc.), that hospital can temporarily send personnel and systems to work inside Hospital B in order to stay in business during the interruption (and Hospital B can relocate to Hospital A, if Hospital B has a similar problem). The hospitals have decided that they are not going to compete based on safety and security—they are going to compete on service, price and customer loyalty. This way, they protect themselves and the healthcare industry as a whole.  

- These agreements are called joint operating agreements (JOA) or memoranda of understanding (MOU) or memoranda of agreement (MOA). Sometimes these agreements are mandated by regulatory requirements, or they might just be part of the administrative safeguards instituted by an entity within the guidelines of its industry. 

- The difference between an MOA or MOU  and an SLA is that a Memorandum of Understanding is more directly related to what can be done with a system or the information. 

- The service level agreement goes down to the granular level. For example, if I'm outsourcing the IT services, then I will need to have two full-time technicians readily available, at least from Monday through Friday from eight to five. With cloud computing, I need to have access to the information in my backup systems within 10 minutes. An SLA specifies the more intricate aspects of the services.  

- We must be very cautious when outsourcing with cloud-based services, because we have to make sure that we understand exactly what we are agreeing to. If the SLA promises 100 percent accessibility to information, is the access directly to you at the moment, or is it access to their website or through their portal when they open on Monday? That's where you'll rely on your legal team, who can supervise and review the conditions carefully before you sign the dotted line at the bottom.

----------

----------

- the concepts of Memorandum of Understanding (MOU) and Memorandum of Agreement (MOA) in an easy way.

- Think of an MOU or MOA as a kind of agreement between two or more parties who want to work together or collaborate on something. It's like a written document that outlines the terms and conditions of their collaboration or understanding.

- An MOU is usually used when the parties involved want to explore the possibility of working together or have a general understanding about a certain matter. It's like a preliminary agreement that sets the framework for their future relationship. It's often used when two organizations or governments want to start discussions or negotiations, or when they want to express their intent to work together.

- On the other hand, an MOA is used when the parties involved have already agreed upon the specific details of their collaboration. It's a more formal agreement that outlines the roles, responsibilities, and specific terms of the partnership. An MOA is usually used when the parties have reached a more concrete understanding and want to establish a binding commitment to work together.

- In simple terms, you can think of an MOU as a starting point, where the parties express their interest in working together and outline some general ideas. An MOA, on the other hand, is a more detailed document that comes later, when the parties have agreed on the specifics and are ready to make a formal commitment.

- Both MOUs and MOAs are written agreements, signed by the parties involved, and can be legally binding depending on the context and the language used. They provide clarity and help avoid misunderstandings between the parties involved in a collaborative effort.

- Remember, an MOU is more like a handshake agreement to explore a potential partnership, while an MOA is a detailed commitment that outlines the specific terms of the collaboration.

---------

----------

## 3.Cloud Characteristics

- Cloud-based assets include any resources that an organization accesses using cloud computing. Cloud computing refers to on-demand access to computing resources available from almost anywhere, and cloud computing resources are highly available and easily scalable. Organizations typically lease cloud-based resources from outside the organization. Cloud computing has many benefits for organizations, which include but are not limited to: 

- Usage is metered and priced according to units (or instances) consumed. This can also be billed back to specific departments or functions.
- Reduced cost of ownership. There is no need to buy any assets for everyday use, no loss of asset value over time and a reduction of other related costs of maintenance and support.
- Reduced energy and cooling costs, along with “green IT” environment effect with optimum use of IT resources and systems.
- Allows an enterprise to scale up new software or data-based services/solutions through cloud systems quickly and without having to install massive hardware locally.

---------------

-----------

## 4.Service Models

- Some cloud-based services only provide data storage and access. When storing data in the cloud, organizations must ensure that security controls are in place to prevent unauthorized access to the data. 

- There are varying levels of responsibility for assets depending on the service model. This includes maintaining the assets, ensuring they remain functional, and keeping the systems and applications up to date with current patches. In some cases, the cloud service provider is responsible for these steps. In other cases, the consumer is responsible for these steps. 

- Types of cloud computing service models include Software as a Service (SaaS) , Platform as a Service (PaaS) and Infrastructure as a Service (IaaS).

### Software as a Service (SaaS): 

- A cloud provides access to software applications such as email or office productivity tools. SaaS is a distributed model where software applications are hosted by a vendor or cloud service provider and made available to customers over network resources. SaaS is a widely used and adopted form of cloud computing, with users most often needing an internet connection and access credentials to have full use of the cloud service, application and data. SaaS has many benefits for organizations, which include but are not limited to: Ease of use and limited/minimal administration. Automatic updates and patch management. The user will always be running the latest version and most up-to-date deployment of the software release, as well as any relevant security updates, with no manual patching required. Standardization and compatibility. All users will have the same version of the software release.

### Platform as a Service (PaaS): 

- A cloud provides an environment for customers to use to build and operate their own software. PaaS is a way for customers to rent hardware, operating systems, storage and network capacity over the internet from a cloud service provider. The service delivery model allows customers to rent virtualized servers and associated services for running existing applications or developing and testing new ones. The consumer does not manage or control the underlying cloud infrastructure, including network, servers, operating systems or storage, but has control over the deployed applications and possibly application-hosting environment configurations. A PaaS cloud provides a toolkit for conveniently developing, deploying and administering application software that is structured to support large numbers of consumers, process very large quantities of data and potentially be accessed from any point on the internet. PaaS clouds will typically provide a set of software building blocks and a set of development tools such as programming languages and supporting run-time environments that facilitate the construction of high-quality, scalable applications. Additionally, PaaS clouds will typically provide tools that assist with the deployment of new applications. In some cases, deploying a new software application in a PaaS cloud is not much more difficult than uploading a file to a web server. PaaS clouds will also generally provide and maintain the computing resources (e.g., processing, storage and networking) that consumer applications need to operate. PaaS clouds provide many benefits for developers, including that the operating system can be changed and upgraded frequently, along with associated features and system services.

### Infrastructure as a Service (IaaS):

- A cloud provides network access to traditional computing resources such as processing power and storage. IaaS models provide basic computing resources to consumers. This includes servers, storage, and in some cases, networking resources. Consumers install operating systems and applications and perform all required maintenance on the operating systems and applications. Although the consumer has use of the related equipment, the cloud service provider retains ownership and is ultimately responsible for hosting, running and maintenance of the hardware. IaaS is also referred to as hardware as a service by some customers and providers. IaaS has a number of benefits for organizations, which include but are not limited to: Ability to scale up and down infrastructure services based on actual usage. This is particularly useful and beneficial where there are significant spikes and dips within the usage curve for infrastructure. Retain system control at the operating system level.

-------------

--------------

## 5.Deployment Models

- There are four cloud deployment models. The cloud deployment model also affects the breakdown of responsibilities of the cloud-based assets. The four cloud models available are Public, Private, hybrid and Community.

### Public:-

- Public clouds are what we commonly refer to as the cloud for the public user. It is very easy to get access to a public cloud. There is no real mechanism, other than applying for and paying for the cloud service. It is open to the public and is, therefore, a shared resource that many people will be able to use as part of a resource pool. A public cloud deployment model includes assets available for any consumers to rent or lease and is hosted by an external cloud service provider (CSP). Service level agreements can be effective at ensuring the CSP provides the cloud-based services at a level acceptable to the organization.

### Private:-

- Private clouds begin with the same technical concept as public clouds, except that instead of being shared with the public, they are generally developed and deployed for a private organization that builds its own cloud. Organizations can create and host private clouds using their own resources. Therefore, this deployment model includes cloud-based assets for a single organization. As such, the organization is responsible for all maintenance. However, an organization can also rent resources from a third party and split maintenance requirements based on the service model (SaaS, PaaS or IaaS). Private clouds provide organizations and their departments private access to the computing, storage, networking and software assets that are available in the private cloud.

### Hybrid:-

- A hybrid cloud deployment model is created by combining two forms of cloud computing deployment models, typically a public and private cloud. Hybrid cloud computing is gaining popularity with organizations by providing them with the ability to retain control of their IT environments, conveniently allowing them to use public cloud service to fulfill non-mission-critical workloads, and taking advantage of flexibility, scalability and cost savings. Important drivers or benefits of hybrid cloud deployments include: Retaining ownership and oversight of critical tasks and processes related to technology, Reusing previous investments in technology within the organization, Control over most critical business components and systems, and Cost-effective means to fulfilling noncritical business functions (utilizing public cloud components).

### Community:-

- Community clouds can be either public or private. What makes them unique is that they are generally developed for a particular community. An example could be a public community cloud focused primarily on organic food, or maybe a community cloud focused specifically on financial services. The idea behind the community cloud is that people of like minds or similar interests can get together, share IT capabilities and services, and use them in a way that is beneficial for the particular interests that they share.

------------

---------

## 6. Managed Service Provider (MSP)

- A managed service provider (MSP) is a company that manages information technology assets for another company. Small- and medium-sized businesses commonly outsource part or all of their information technology functions to an MSP to manage day-to-day operations or to provide expertise in areas the company does not have. Organizations may also use an MSP to provide network and security monitoring and patching services. Today, many MSPs offer cloud-based services augmenting SaaS solutions with active incident investigation and response activities. One such example is a managed detection and response (MDR) service, where a vendor monitors firewall and other security tools to provide expertise in triaging events. 

- Some other common MSP implementations are: 

- Augment in-house staff for projects
- Utilize expertise for implementation of a product or service
- Provide payroll services
- Provide Help Desk service management
- Monitor and respond to security incidents
- Manage all in-house IT infrastructure

----------

----------

## 7. Service-Level Agreement (SLA)

- The cloud computing service-level agreement (cloud SLA) is an agreement between a cloud service provider and a cloud service customer based on a taxonomy of cloud computing– specific terms to set the quality of the cloud services delivered. It characterizes quality of the cloud services delivered in terms of a set of measurable properties specific to cloud computing (business and technical) and a given set of cloud computing roles (cloud service customer, cloud service provider, and related sub-roles).

- Think of a rule book and legal contract—that combination is what you have in a service-level agreement (SLA). Let us not underestimate or downplay the importance of this document/ agreement. In it, the minimum level of service, availability, security, controls, processes, communications, support and many other crucial business elements are stated and agreed to by both parties.  

- The purpose of an SLA is to document specific parameters, minimum service levels and remedies for any failure to meet the specified requirements. It should also affirm data ownership and specify data return and destruction details. Other important SLA points to consider include the following:

- Cloud system infrastructure details and security standards
- Customer right to audit legal and regulatory compliance by the CSP         
- Rights and costs associated with continuing and discontinuing service use
- Service availability
- Service performance
- Data security and privacy
- Disaster recovery processes
- Data location
- Data access
- Data portability
- Problem identification and resolution expectations
- Change management processes
- Dispute mediation processes
- Exit strategy

------------

------------

## 8.Network Design

- The objective of network design is to satisfy data communication requirements and result in efficient overall performance.

### Network Segmentation:-

 - Network segmentation involves controlling traffic among networked devices. Complete or physical network segmentation occurs when a network is isolated from all outside communications, so transactions can only occur between devices within the segmented network.

### Demiltarized Zone (DMZ):-
  
  - A DMZ is a network area that is designed to be accessed by outside visitors but is still isolated from the private network of the organization. The DMZ is often the host of public web, email, file and other resource servers.

### Virtual Local Area Network(VLAN):-

- VLANs are created by switches to logically segment a network without altering its physical topology.

### Virtual Private Network:-

- A virtual private network (VPN) is a communication tunnel that provides point-to-point transmission of both authentication and data traffic over an untrusted network.

### Defense in Depth:-

- Defense in depth uses multiple types of access controls in literal or theoretical layers to help an organization avoid a monolithic security stance.

### Network Access Control:-

- Network access control (NAC) is a concept of controlling access to an environment through strict adherence to and implementation of security policy.

----------------

-----------

## 9.Defense in Depth

- Defense in depth uses a layered approach when designing the security posture of an organization. Think about a castle that holds the crown jewels. The jewels will be placed in a vaulted chamber in a central location guarded by security guards. The castle is built around the vault with additional layers of security—soldiers, walls, a moat. The same approach is true when designing the logical security of a facility or system. Using layers of security will deter many attackers and encourage them to focus on other, easier targets. 

- Defense in depth provides more of a starting point for considering all types of controls—administrative, technological, and physical—that empower insiders and operators to work together to protect their organization and its systems. 

- Here are some examples that further explain the concept of defense in depth: 

- Data: Controls that protect the actual data with technologies such as encryption, data leak prevention, identity and access management and data controls.
- Application: Controls that protect the application itself with technologies such as data leak prevention, application firewalls and database monitors.
- Host: Every control that is placed at the endpoint level, such as antivirus, endpoint firewall, configuration and patch management.
- Internal network: Controls that are in place to protect uncontrolled data flow and user access across the organizational network. Relevant technologies include intrusion detection systems, intrusion prevention systems, internal firewalls and network access controls.
- Perimeter: Controls that protect against unauthorized access to the network. This level includes the use of technologies such as gateway firewalls, honeypots, malware analysis and secure demilitarized zones (DMZs).
- Physical: Controls that provide a physical barrier, such as locks, walls or access control.
- Policies, procedures and awareness: Administrative controls that reduce insider threats (intentional and unintentional) and identify risks as soon as they appear. 


----------------

------------------

## 10. Zero Trust

- Zero trust networks are often microsegmented networks, with firewalls at nearly every connecting point. Zero trust encapsulates information assets, the services that apply to them and their security properties. This concept recognizes that once inside a trust-but-verify environment, a user has perhaps unlimited capabilities to roam around, identify assets and systems and potentially find exploitable vulnerabilities. Placing a greater number of firewalls or other security boundary control devices throughout the network increases the number of opportunities to detect a troublemaker before harm is done. Many enterprise architectures are pushing this to the extreme of microsegmenting their internal networks, which enforces frequent re-authentication of a user ID, as depicted in this image.  

- Consider a rock music concert. By traditional perimeter controls, such as firewalls, you would show your ticket at the gate and have free access to the venue, including backstage where the real rock stars are. In a zero-trust environment, additional checkpoints are added. Your identity (ticket) is validated to access the floor level seats, and again to access the backstage area. Your credentials must be valid at all 3 levels to meet the stars of the show.  

- Zero trust is an evolving design approach which recognizes that even the most robust access control systems have their weaknesses. It adds defenses at the user, asset and data level, rather than relying on perimeter defense. In the extreme, it insists that every process or action a user attempts to take must be authenticated and authorized; the window of trust becomes vanishingly small.  

- While microsegmentation adds internal perimeters, zero trust places the focus on the assets, or data, rather than the perimeter. Zero trust builds more effective gates to protect the assets directly rather than building additional or higher walls. 


---------------

-----------

- Zero trust is a cybersecurity concept that aims to enhance the security of computer networks and systems by assuming that no user or device should be automatically trusted, regardless of their location or previous access privileges. In simpler terms, it means that instead of assuming everything inside a network is safe, you should verify and authenticate every user and device before granting them access to any resources.

- Imagine you have a house with valuable items. In a traditional security model, once someone enters your house, they are trusted to move around freely and access different rooms. However, in a zero trust model, you would treat everyone as a potential intruder until they prove otherwise. You would require them to show identification, pass through security checks, and only then grant them access to specific areas.

- In the digital world, zero trust follows a similar principle. It means that even if a user or device is inside the network, they still need to verify their identity and prove that they are authorized to access certain resources. This verification can be done through various methods such as multi-factor authentication, strong passwords, device health checks, and encryption.

- By implementing zero trust, organizations can reduce the risk of unauthorized access, data breaches, and other security threats. It adds an extra layer of security by constantly verifying and monitoring user activities, regardless of their location or the network they are connected to.

--------------

----------

## 11. Network Access Control (NAC)

- An organization’s network is perhaps one of its most critical assets. As such, it is vital that we both know and control access to it, both from insiders (e.g., employees, contractors) and outsiders (e.g., customers, corporate partners, vendors). We need to be able to see who and what is attempting to make a network connection.

- At one time, network access was limited to internal devices. Gradually, that was extended to remote connections, although initially those were the exceptions rather than the norm. This started to change with the concepts of bring your own device (BYOD) and Internet of Things (IoT).

- Considering just IoT for a moment, it is important to understand the range of devices that might be found within an organization. They include heating, ventilation and air conditioning (HVAC) systems that monitor the ambient temperature and adjust the heating or cooling levels automatically or air monitoring systems, through security systems, sensors and cameras, right down to vending and coffee machines. Look around your own environment and you will quickly see the scale of their use.

- Having identified the need for a NAC solution, we need to identify what capabilities a solution may provide. As we know, everything begins with a policy. The organization’s access control policies and associated security policies should be enforced via the NAC device(s). Remember, of course, that an access control device only enforces a policy and doesn’t create one.

- The NAC device will provide the network visibility needed for access security and may later be used for incident response. Aside from identifying connections, it should also be able to provide isolation for noncompliant devices within a quarantined network and provide a mechanism to “fix” the noncompliant elements, such as turning on endpoint protection. In short, the goal is to ensure that all devices wishing to join the network do so only when they comply with the requirements laid out in the organization policies. This visibility will encompass internal users as well as any temporary users such as guests or contractors, etc., and any devices they may bring with them into the organization.

- Let’s consider some possible use cases for NAC deployment: 

- Medical devices
- IoT devices
- BYOD/mobile devices (laptops, tablets, smartphones)
- Guest users and contractors

- As we have established, it is critically important that all mobile devices, regardless of their owner, go through an onboarding process, ideally each time a network connection is made, and that the device is identified and interrogated to ensure the organization’s policies are being met. 

---------------------

-------------

## 12. Network Segmentation (Demilitarized Zone (DMZ))

- Network segmentation is also an effective way to achieve defense in depth for distributed or multi-tiered applications. The use of a demilitarized zone (DMZ), for example, is a common practice in security architecture. With a DMZ, host systems that are accessible through the firewall are physically separated from the internal network by means of secured switches or by using an additional firewall to control traffic between the web server and the internal network. Application DMZs (or semi-trusted networks) are frequently used today to limit access to application servers to those networks or systems that have a legitimate need to connect.

----------------------

--------------

- Network segmentation is a way to add extra layers of security to protect distributed or multi-tiered applications. It's like having different zones or areas within your network that have different levels of access.

- One common approach is to create a demilitarized zone (DMZ), which is like a secure middle ground between the internet and your internal network. In the DMZ, you place servers or systems that need to be accessible from the internet, like web servers. These systems are physically separated from the rest of your internal network using secure switches or an additional firewall.

- By doing this, you create a barrier between the internet and your internal network, making it harder for attackers to directly access sensitive information or systems. It adds an extra layer of protection.

- Another way to use network segmentation is by creating application DMZs or semi-trusted networks. This means limiting access to certain application servers only to networks or systems that genuinely need to connect to them. It helps minimize the risk of unauthorized access and potential vulnerabilities.

- In simple terms, network segmentation is like dividing your network into different areas with different levels of access. It's a way to protect critical systems and limit access to only those who really need it, making it more difficult for attackers to infiltrate your network and compromising your sensitive data.

----------------

---------------

## 13. Segmentation for Embedded Systems and IoT

- An embedded system is a computer implemented as part of a larger system. The embedded system is typically designed around a limited set of specific functions in relation to the larger product of which it is a component. Examples of embedded systems include network-attached printers, smart TVs, HVAC controls, smart appliances, smart thermostats and medical devices. 

- Network-enabled devices are any type of portable or nonportable device that has native network capabilities. This generally assumes the network in question is a wireless type of network, typically provided by a mobile telecommunications company. Network-enabled devices include smartphones, mobile phones, tablets, smart TVs or streaming media players (such as a Roku Player, Amazon Fire TV, or Google Android TV/Chromecast), network-attached printers, game systems, and much more. 

- The Internet of Things (IoT) is the collection of devices that can communicate over the internet with one another or with a control console in order to affect and monitor the real world. IoT devices might be labeled as smart devices or smart-home equipment. Many of the ideas of industrial environmental control found in office buildings are finding their way into more consumer-available solutions for small offices or personal homes.  

- Embedded systems and network-enabled devices that communicate with the internet are considered IoT devices and need special attention to ensure that communication is not used in a malicious manner. Because an embedded system is often in control of a mechanism in the physical world, a security breach could cause harm to people and property. Since many of these devices have multiple access routes, such as ethernet, wireless, Bluetooth, etc., special care should be taken to isolate them from other devices on the network. You can impose logical network segmentation with switches using VLANs, or through other traffic-control means, including MAC addresses, IP addresses, physical ports, protocols, or application filtering, routing, and access control management. Network segmentation can be used to isolate IoT environments. 

--------------

--------------

- An embedded system is like a small computer that is part of a bigger system. It is designed to perform specific functions within that larger product. For example, network-attached printers, smart TVs, HVAC controls, smart appliances, thermostats, and medical devices are all examples of embedded systems. They are built to do certain tasks as part of a larger device or system.

- Network-enabled devices are devices that can connect to a network, usually a wireless network provided by a mobile telecommunications company. These devices can be portable or nonportable. Examples include smartphones, tablets, smart TVs, game systems, and network-attached printers. They have the capability to connect to the internet and communicate with other devices.

- The Internet of Things (IoT) refers to a collection of devices that can communicate with each other or with a control console over the internet. These devices can affect and monitor the real world. They are often referred to as smart devices or smart-home equipment. For example, you might have IoT devices that control the temperature in your home or monitor security.

- Both embedded systems and network-enabled devices that communicate with the internet are considered IoT devices. It's important to pay special attention to the security of these devices because they can potentially cause harm if there is a security breach. Since these devices often have multiple ways to connect to a network (such as ethernet, wireless, Bluetooth), it's crucial to isolate them from other devices on the network.

- To enhance the security of IoT devices, one approach is network segmentation. This means dividing the network into different segments or parts using switches or other means. This isolation can be achieved through techniques like VLANs (Virtual Local Area Networks), where devices in one segment cannot directly communicate with devices in another segment. By segmenting the network, you can control and restrict access to IoT devices, protecting them from potential threats.

- In simpler terms, embedded systems are small computers in bigger devices, network-enabled devices can connect to the internet, and IoT devices are part of a network that communicates with each other. They all need special attention to ensure security, and one way to do that is by using network segmentation to separate and protect IoT devices from potential risks.

------------

--------------

## 14.Microsegmentation

- The toolsets of current adversaries are polymorphic in nature and allow threats to bypass static security controls. Modern cyberattacks take advantage of traditional security models to move easily between systems within a data center. Microsegmentation aids in protecting against these threats. A fundamental design requirement of microsegmentation is to understand the protection requirements for traffic within a data center and traffic to and from the internet traffic flows. 

- When organizations avoid infrastructure-centric design paradigms, they are more likely to become more efficient at service delivery in the data center and become apt at detecting and preventing advanced persistent threats.

----------------------

-----------

## 15. Virtual Local Area Network (VLAN)

- Virtual local area networks (VLANs) allow network administrators to use switches to create software-based LAN segments, which can segregate or consolidate traffic across multiple switch ports. Devices that share a VLAN communicate through switches as if they were on the same Layer 2 network. This image shows different VLANs — red, green and blue — connecting separate sets of ports together, while sharing the same network segment (consisting of the two switches and their connection). Since VLANs act as discrete networks, communications between VLANs must be enabled. Broadcast traffic is limited to the VLAN, reducing congestion and reducing the effectiveness of some attacks. Administration of the environment is simplified, as the VLANs can be reconfigured when individuals change their physical location or need access to different services. VLANs can be configured based on switch port, IP subnet, MAC address and protocols.

- VLANs do not guarantee a network’s security. At first glance, it may seem that traffic cannot be intercepted because communication within a VLAN is restricted to member devices. However, there are attacks that allow a malicious user to see traffic from other VLANs (so-called VLAN hopping). The VLAN technology is only one tool that can improve the overall security of the network environment.

-------

--------

- A Virtual Local Area Network (VLAN) is a way for network administrators to create separate virtual LAN segments using switches. It helps segregate or combine network traffic across different switch ports. Devices within the same VLAN can communicate with each other as if they were connected to the same physical network.

- Imagine you have different groups of devices in an office, like computers, printers, and phones. With VLANs, you can create separate virtual networks for each group. For example, devices in the red VLAN can communicate with each other, devices in the green VLAN can communicate with each other, and so on. This segmentation helps organize and control network traffic.

- VLANs offer several benefits. By isolating traffic within each VLAN, broadcast traffic is limited to the VLAN itself, reducing congestion and making some attacks less effective. It also simplifies network administration because VLANs can be reconfigured when people change their physical location or require access to different services. VLANs can be set up based on switch ports, IP subnets, MAC addresses, or protocols.

- However, it's important to note that VLANs alone don't guarantee network security. Although communication within a VLAN is restricted to member devices, there are techniques like VLAN hopping that can allow a malicious user to see traffic from other VLANs. VLANs are just one tool that can improve network security, and additional measures should be taken to protect the overall network environment.

- In simpler terms, VLANs are like creating virtual networks within a physical network using switches. They help separate and control traffic between different groups of devices. VLANs can improve network organization, reduce congestion, and simplify administration. However, VLANs alone are not enough for complete network security, and other measures should be implemented as well.

-------------

-------------

## 16. Virtual Private Network (VPN)

- A virtual private network (VPN) is not necessarily an encrypted tunnel. It is simply a point-to-point connection between two hosts that allows them to communicate. Secure communications can, of course, be provided by the VPN, but only if the security protocols have been selected and correctly configured to provide a trusted path over an untrusted network, such as the internet. Remote users employ VPNs to access their organization’s network, and depending on the VPN’s implementation, they may have most of the same resources available to them as if they were physically at the office. As an alternative to expensive dedicated point-to-point connections, organizations use gateway-to-gateway VPNs to securely transmit information over the internet between sites or even with business partners.

---------------

-------------

- **Application programming interface (API)** - A set of routines, standards, protocols, and tools for building software applications to access a web-based software application or web tool.
- **Bit** - The most essential representation of data (zero or one) at Layer 1 of the Open Systems Interconnection (OSI) model.
- **Broadcast** - Broadcast transmission is a one-to-many (one-to-everyone) form of sending internet traffic.
- **Byte** - The byte is a unit of digital information that most commonly consists of eight bits.
- **Cloud computing** - A model for enabling ubiquitous, convenient, on-demand network access to a shared pool of configurable computing resources (e.g., networks, servers, storage, applications, and services) that can be rapidly provisioned and released with minimal management effort or service provider interaction. NIST 800-145
- **Community cloud** - A system in which the cloud infrastructure is provisioned for exclusive use by a specific community of consumers from organizations that have shared concerns (e.g., mission, security requirements, policy and compliance considerations). It may be owned, managed and operated by one or more of the organizations in the community, a third party or some combination of them, and it may exist on or off premises. NIST 800-145
- **De-encapsulation** - The opposite process of encapsulation, in which bundles of data are unpacked or revealed.
- **Denial-of-Service (DoS)** - The prevention of authorized access to resources or the delaying of time-critical operations. (Time-critical may be milliseconds or it may be hours, depending upon the service provided.) Source: NIST SP 800-27 Rev A
- **Domain Name Service (DNS)** - This acronym can be applied to three interrelated elements: a service, a physical server and a network protocol.
- **Encapsulation** - Enforcement of data hiding and code hiding during all phases of software development and operational use. Bundling together data and methods is the process of encapsulation; its opposite process may be called unpacking, revealing, or using other terms. Also used to refer to taking any set of data and packaging it or hiding it in another data structure, as is common in network protocols and encryption.
- **Encryption** - The process and act of converting the message from its plaintext to ciphertext. Sometimes it is also referred to as enciphering. The two terms are sometimes used interchangeably in literature and have similar meanings.
- **File Transfer Protocol (FTP)** - The internet protocol (and program) used to transfer files between hosts.
- **Fragment attack** - In a fragment attack, an attacker fragments traffic in such a way that a system is unable to put data packets back together.
- **Hardware** - The physical parts of a computer and related devices.
- **Hybrid cloud** - A combination of public cloud storage and private cloud storage where some critical data resides in the enterprise’s private cloud while other data is stored and accessible from a public cloud storage provider.
- **Infrastructure as a Service (IaaS)** - The provider of the core computing, storage and network hardware and software that is the foundation upon which organizations can build and then deploy applications.  IaaS is popular in the data center where software and servers are purchased as a fully outsourced service and usually billed on usage and how much of the resource is used.
- **Internet Control Message Protocol (ICMP)** - An IP network protocol standardized by the Internet Engineering Task Force (IETF) through RFC 792 to determine if a particular service or host is available.
- **Internet Protocol (IPv4)** - Standard protocol for transmission of data from source to destinations in packet-switched communications networks and interconnected systems of such networks. CNSSI 4009-2015
- **Man-in-the-Middle** - An attack where the adversary positions himself in between the user and the system so that he can intercept and alter data traveling between them. Source: NISTIR 7711
- **Microsegmentation** - Part of a zero-trust strategy that breaks LANs into very small, highly localized zones using firewalls or similar technologies. At the limit, this places firewall at every connection point.
- **Oversized Packet Attack** - Purposely sending a network packet that is larger than expected or larger than can be handled by the receiving system, causing the receiving system to fail unexpectedly.
- **Packet** - Representation of data at Layer 3 of the Open Systems Interconnection (OSI) model.
- **Payload** - The primary action of a malicious code attack.
- **Payment Card Industry Data Security Standard (PCI DSS)** - An information security standard administered by the Payment Card Industry Security Standards Council that applies to merchants and service providers who process credit or debit card transactions.
- **Platform as a Service (PaaS)** - The web-authoring or application development middleware environment that allows applications to be built in the cloud before they’re deployed as SaaS assets.
- **Private cloud** - The phrase used to describe a cloud computing platform that is implemented within the corporate firewall, under the control of the IT department. A private cloud is designed to offer the same features and benefits of cloud systems, but removes a number of objections to the cloud computing model, including control over enterprise and customer data, worries about security, and issues connected to regulatory compliance.
- **Protocols** - A set of rules (formats and procedures) to implement and control some type of association (that is, communication) between systems. NIST SP 800-82 Rev. 2
- **Public cloud** - The cloud infrastructure is provisioned for open use by the general public. It may be owned, managed, and operated by a business, academic, or government organization, or some combination of them. It exists on the premises of the cloud provider. NIST SP 800-145
- **Simple Mail Transport Protocol (SMTP)** - The standard communication protocol for sending and receiving emails between senders and receivers.
- **Software** - Computer programs and associated data that may be dynamically written or modified during execution. NIST SP 80-37 Rev. 2
- **Software as a Service (SaaS)** - The cloud customer uses the cloud provider’s applications running within a cloud infrastructure. The applications are accessible from various client devices through either a thin client interface, such as a web browser or a program interface. The consumer does not manage or control the underlying cloud infrastructure including network, servers, operating systems, storage, or even individual application capabilities, with the possible exception of limited user-specific application configuration settings. Derived from NIST 800-145
- **Spoofing** - Faking the sending address of a transmission to gain illegal entry into a secure system. CNSSI 4009-2015
- **Transport Control Protocol/Internet Protocol (TCP/IP) Model** - Internetworking protocol model created by the IETF, which specifies four layers of functionality: Link layer (physical communications), Internet Layer (network-to-network communication), Transport Layer (basic channels for connections and connectionless exchange of data between hosts), and Application Layer, where other protocols and user applications programs make use of network services.
- **Virtual Local Area Network (VLAN)** - A logical group of workstations, servers, and network devices that appear to be on the same LAN despite their geographical distribution.
- **VPN** - A virtual private network (VPN), built on top of existing networks, that can provide a secure communications mechanism for transmission between networks.
- **Wireless Area Network (WLAN)** - A group of computers and devices that are located in the same vicinity, forming a network based on radio transmissions rather than wired connections. A Wi-Fi is network is a type of WLAN.
- **Zenmap** - The graphical user interface (GUI) for the Nmap Security Scanner, an open-source application that scans networks to determine everything that is connected as well as other information.
- **Zero Trust** - Removing the design belief that the network has any trusted space. Security is managed at each possible level, representing the most granular asset. Microsegmentation of workloads is a tool of the model.
