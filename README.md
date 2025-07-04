 # 2/7/2025  Day-6 

Safe Mode

 when we start our computer , our computer go through the booting process. In the booting process , the computer loads the operating system to RAM .So during this phase, device drivers also get loaded and OS provide base for interaction between the hardware and drivers. So during this phase a lot of drivers get loaded even if not required.

 Safe mode is a feature that allow only the essential drivers to be loaded on the computer .Safe Mode is used when our OS encounters an issue especially it is crashing due to new update or has been infected with Boot Virus or other Malware. So when our computer enters safe mode it start troubleshooting the problem and loads only minimum drivers . During this phase diagnostic programs are used to check for troubles. Audio disabled, videos are at low resolution. IT is available in windows 7,  windows 8, windows 9 . 

 RECOVERY TOOLS:

 IT refers to software or process designed to restore data that has been lost, deleted or become inaccessible due to various reasons such as accident deletion , formatting , or system craches.

Built - in tools to repair or restore Windows. 
Example :

System Restore 

startup Repair 

System Image Recovery

Command Prompt

Reset this PC

OS REPAIR:

It refers to the process of fixing issue with an operating System that prevent it from functioning correct method to fix corrupted or missing OS files . 

Basic method :

sfc/scanner- Scan and restore system files.

DISM/ONLINE/Cleanup- Image 

RestoreHealth- Repairs Corrupted Windows images.

Bootable USB for repair and system reinstall.

Virus/Malware Symptoms:

signs your system may be infected

slow  performance

Random pop ups or ads.

Slow startup 

Programs crashing

Unexplained files or folders disappearing

Unusual network activity:

 Malware can send or receive data, causing increased network activity, especially when your devices is idle.

 # VIRUS REMOVAL STEPS:

1 Enter Safe Mood 

2. Run Antivirus Scan(e.g. Windows, Defender, Avast , Malwarebytes)

3. Clear Temp files.

4. Reset Web browser setting.

5. Update OS and antivirus.


Where to Keep Windows Backups?

Backups are essential for recovery in case of OS failure or data loss.

  External Drive: Recommended option for offline, safe backup storage.

  Separate Internal Drive: (e.g., D:,E:): Better than storage on the system drive(C:), but vulnerable if the whole disk fails.

Ethernet Cable

Ethernet cables are used to connect computers, routers, and switches for network communication.

RJ-45 (REGISTERED JACK-45)

Type: Connector used for Ethernet networking

Shape: 8-pin rectangular plug

Cable Used: Commonly with Cat5, Cat6 Ethernet cables

Use: Connects computers, routers, switches, etc., for LAN

Speed Support: Up to 10 Gbps (with Cat6/6a)

Looks Like: Slightly larger than a telephone (RJ-11) plug 

Colour Code

White-Orange, Orange, White-Green, Blue, White-Blue, Green, White-Brown, Brown
How to Make a RJ‐45 Cable:

Strip the cable to remove 1 inch of the outer sheath.

Untwist and straighten the wires inside of the cable

Arrange the wires into the right order.

Trim the wires into an even line 1⁄2 inch (13 mm) from sheathing

Insert the wires into the RJ-45 connector.

Stick the connector into the crimping part of the tool and squeeze twice.

Remove the cable from the tool and check that all of the pins are down & test the cable
 ![image](https://github.com/user-attachments/assets/08bbca81-f602-4edc-8be1-3f77b4d502ee)

 3/7/2025 Day 7

 Networking Basics

Host :

Host refers to any device that connects to a network and can send or receive data.This includes other networked devices like smartphones,Compurts(laptops, desktops),Server,Printer, tablets, and IoT(Internet of Things) devices.

Client: A client is a devices or software that initiates communication with a server to access services or resources.Example: A web Browser(like Chrome) requesting a web page.
       
 An email app checking your inbox.

A mobile app fetching data from a server.

SERVER:
A server is a device or program that waits for request and then responds with data or services.

Example:

A web server hosting a webstite.

A file server storing and sharing files.

A database server handling data queries.

 WHAT IS NETWORK?

 A network is a group of two or more computers or devices connected together so they can communicate and share resources.

 IP Address(Internal Protocol Address):

 An IP address is a unique numerical identifier assigned to every device connected to a computer network that uses the internet Protocol for communication. It enables devices to communicate with each other.

Protocol: Protocol is a set of rules governing how data is formatted , transmitted  and received between devices.

Properties:

Unique: Each device on a network must have a unique IP address.

Universal: IP address are a globally recognized standard for network communicatin.

       IP Type      Usage

       Publice      Used on the internet , these addresses are globally unique and rutable.

       private     Used within private networks(e.g., home or school networks), these addresses are not directly routable on the internet.

Dynamic Nature : IP address can change over time, especially for devices on dynamic IP  assignments. However, its fundamental properties (uniqueness and universality) remain constant.

IPv4( Internet Protocol Version 4): IPv4 is the fourth version of the internet Protocol.

       Length: 32 bits long.

       Address Space: Can theoretically support $2^{32}$ unique address.

       Notations:  Decimal Notation: Use base 10 number system (digit 0-9).
                   Most common in everyday life. Example: 192, 168, 1, 1 in IPv4 address 192.168.1.1.

                  Represented in dotted - decimal format

    Binary Notation:  Use base 2 number system (digits 0 and 1). 
                      Computers operate using binary internally.
                      Each decimal number  in an IPv4 address corresponds to an 8- bit binary number.

     Example:  Decimal: 192 = Binary 11000000

               Decimal: 168= Binary 10101000

               Decimal 1= Binary 00000001

Address Structure:

Network ID(prefix): Defines the network segment to which the device belongs. This part is common for all devices within the same network .

Host ID(Suffix): Uniquely identifies a specific device (host) within that network segment.

Example: An international phone number where the country code represent network and the phone number represent the "host."


IPv6( Internet Protocol Versin 6):

IPv6 is the latest version of the internet Protocol, designed to address the limitations of IPv4, primarily the exhaustion of available addresses.

          LENGTH: 128 Bits long 

          ADDRESS SPACE: Can support a vastly larger number of addresses , approximately $2^{128}$.

          Notation: Represented in hexadecimal, often with colons separating groups of 16 bits.

IPv4 and IPv6

    Feature	          IPv4                                 	IPv6

    Address Length	    32 bits                             	128 bits

    Address Format	    Dotted decimal (e.g., 192.168.1.1)  	Hexadecimal, colon-separated (e.g., 2001:0db8::1)

    Address Space	     ~4.3 billion addresses              	Vast (3.4×10^38 addresses)

    Header Complexity	  Simple                             	More complex, improved features

    Deployment        	Widely used                         	Growing adoption, future-proof

    
   Classful Addressing(IPv4)
   
   Classful addressing is an early way of dividing IPv4 addresses into fixed categories called classes based on the first few bits of the address.
   
     Class  Starting Bits	  IP Range   Length of Network (Bits)  	Reseved bits  	Number of Networks  	Number of Hosts         	Default Subnet Mask   	Purpose

     A      	0             	0 - 126          	8                      	First	        $2^{7}$=128          $2^{24}$=16 million      255.0.0.0            Very large organizations. exp: Indian                                                                                                                                                   railways
     
     B       10             128 - 191        16                      First2        $2^{14}$            $2^{16}$                  255.255.0.0          Medium-sized organizations

    C       110            192 - 223        24                     First3         $2^{21}$            $2^{8}$= 256              255.255.255.0          Small networks (like LANs)
   
    D       1110           224 -239         N/A(Multicast)          N/A             N/A                  N/A                        N/A                    Multicast groups

    E       1111          240 - 255         Reserved                N/A             N/A                  N/A                       N/A                 Experimental or research use only 

Network and Host

Network: The part of an IP address that identifies the specific network a device belongs to.

Host: The part of the IP address that identifies the specific device (computer, printer, etc.) on that network.

Example:

In the IP address 192.168.1.10 with subnet mask 255.255.255.0:

Network part: 192.168.1

Host part: 10

Prefix and Suffix

Prefix: Another name for the network portion of the IP address. Often expressed with CIDR notation, e.g., /24 means the first 24 bits are the network prefix.

Suffix: Refers to the host  portion of the IP address — the bits left over after the prefix that identify the device.

In clasful addressing, address space is divided into 5 classes: A, B, C, D, E. Each occupies some part of address space.

ASSIGNMENT

Broadcast vs. Multicast vs. Unicast

       Parameters        	Unicast                       	Broadcast                       	Multicast

         Basics         	There is only one                There are multiple            There are multiple
                         receiver and one sender.       receiver and one sender.        receiver and multiple senders.

       Meaning and      Unicast is used to transfer      Broadcast sends data from        Multicast sends data from one or   
       Definition       data from a single sender to a     one sender to all devices      more senders to a selected group of
                        single print                       on a network                    receivers
    
     SUBNETTING

Subnetting is the process of dividing a larger IP network into smaller, more manageable subnetworks (subnets).



Bandwidth: Capacity of network; data transmission rate (e.g., Mbps). Should be maximum.

Latency: Delay in data transmission. Should be minimum.

Host Bits: Denoted by '0's in subnet mask.

Network IP: First IP of a subnet (cannot be assigned to host).

Broadcast IP: Last IP of a subnet (cannot be assigned to host).

SUBNET MASK

A subnet mask is a 32-bit number used to divide an IP address into network and host parts.

Purpose

It determines which part of the IP address refers to the network and which part refers to the host.
Helps routers and devices identify the subnet to which an IP belongs.
Format

Written in the same format as an IPv4 address (four decimal octets).
Example: 255.255.255.0

Some other small concepts:

MAC (Media Access Control Address)

Nature: A unique, 12-character hexadecimal (alphanumeric) attribute used to identify individual electronic devices on a network.

Distinction from IP Address:

MAC Address: Identifies the physical location of a device within a local network. It's like your permanent home address. The manufacturer provides it.

IP Address: Signifies the device's global or internet-accessible identity. It's more like a temporary vacation rental address, changing depending on your network connection.

DNS (Domain Name System):

It is a naming system for computers, service etc connected to the Internet or a private network. It translates domain names (www.google.com) into machine-readable IP addresses (172.217.160.142).

Default Gateway:
Its a device (typically a router) that acts as a pathway for data to leave a local network and reach other networks, including the internet.

CIDR (Classless Inter-Domain Routing):
Modern method for IP allocation and routing, replacing classful addressing with more flexible network sizing (e.g., /24).

Types of Cables: 

Twisted Pair:

      Types: Shielded (STP) and Unshielded (UTP).

       Use: LANs (Ethernet).

      Coaxial:
      
      Use: TV networks, older computer networks.

      Fiber-Optic:

      Use: High-speed networks, long distances (most commonly used today).

   Numericals:

For 205.150.65.0/26.   Find:

Subset mask

Number of subsets

Number of hosts

Network IP

Broadcast IP.

Answer:  Here /26 is CIDR Class: Class C.

Subnet Mask: 255.255.255.192

In binary: 11111111.11111111.11111111.11000000

This means 26 bits are used for the network.

Convering 11000000 to decimal = 

$2^{7}$ + $2^{6}$ = 192

SO Subset mask is: 255.255.255.192

Number of Subnets:

26 network bits - 24 default network bits = 2 subnet bits

Number of subnets = 

$2^{\text{subnet bits}} = 2^2 = 4$

Number of Hosts

Host ID Bits: 32 - 26 = 6

Number of hosts = 

$2^{\text{host bits}} - 2 = 2^6 - 2 = 64 - 2 = 62$

Network IP:

Given IP AND (AND operation) Subset mask:
205.105.65.0

Broadcast IP:

As maximum number of hosts are 62:
205.105.65.63
 
      
      










   


   

   
                     
 


 
 
         





 
 
 



 
