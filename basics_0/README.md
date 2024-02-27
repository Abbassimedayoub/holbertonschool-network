# OSI Model

The OSI (Open Systems Interconnection) Model is a conceptual framework that standardizes the functions of a telecommunication or computing system into seven distinct layers. These layers work together to facilitate communication between devices on a network, ensuring interoperability and efficient data transmission. 

## Layers of the OSI Model

1. **Physical Layer:**  
   - Deals with the physical connection between devices.
   - Specifies electrical, mechanical, and procedural aspects of transmission.
   - Defines characteristics such as voltage levels, data rates, and physical connectors.

2. **Data Link Layer:**  
   - Responsible for the reliable transfer of data across a physical link.
   - Handles error detection and correction.
   - Formats and frames data into frames.

3. **Network Layer:**  
   - Concerned with routing data packets between different networks.
   - Determines the optimal path for data transmission.
   - Manages network congestion.

4. **Transport Layer:**  
   - Ensures reliable end-to-end communication between devices.
   - Segments and reassembles data into smaller units.
   - Provides error checking, correction, and flow control.

5. **Session Layer:**  
   - Establishes, maintains, and terminates connections between devices.
   - Enables synchronization and coordination between communication endpoints.
   - Manages sessions such as login/logout and session checkpointing.

6. **Presentation Layer:**  
   - Deals with the formatting and syntax of exchanged data.
   - Translates data into a format understood by the receiving system.
   - Handles tasks such as data compression, encryption, and decryption.

7. **Application Layer:**  
   - Provides network services directly to end-users and application programs.
   - Enables communication between different applications.
   - Supports various network protocols such as HTTP, FTP, SMTP, and DNS.

Overall, the OSI Model organizes the functions of a network into a hierarchical structure, with each layer responsible for specific tasks related to data transmission and communication. This modular approach simplifies network design, troubleshooting, and interoperability between different systems and devices.
# LAN (Local Area Network)

A LAN (Local Area Network) is a network infrastructure confined to a small geographic area, such as a single building, office, or campus. It allows connected devices to communicate and share resources within the defined area.

## Typical Usage

LANs are commonly used in various settings, including:

- Offices: for sharing printers, files, and internet access among computers.
- Homes: for connecting multiple devices such as computers, smartphones, and smart home devices.
- Schools and universities: for providing networked resources to students and faculty, such as internet access and shared drives.

## Typical Geographical Size

LANs typically cover small areas, ranging from a single room to a few kilometers in size. They are designed for use within a confined space to provide high-speed and reliable communication between connected devices.

# WAN (Wide Area Network)

A WAN (Wide Area Network) is a network infrastructure that spans a large geographic area, connecting multiple LANs and other networks across cities, countries, or even continents. It enables long-distance communication between devices and facilitates access to remote resources.

## Typical Usage

WANs are commonly used for various purposes, including:

- Interconnecting branch offices: allowing communication and resource sharing between offices located in different cities or countries.
- Internet connectivity: providing access to the internet for users and organizations worldwide.
- Telecommunication networks: enabling the transmission of data, voice, and video across long distances.

## Typical Geographical Size

WANs cover extensive geographic areas, ranging from hundreds of kilometers to global coverage. They utilize various technologies such as leased lines, fiber optics, and satellite links to connect distant locations and provide reliable communication over long distances.
# What is the Internet?

The Internet is a global network of interconnected computers and devices that use standardized communication protocols to exchange data and information. It encompasses a vast array of networks, servers, and infrastructure worldwide, allowing users to access and share resources, communicate, and collaborate on a global scale.

# What is an IP Address?

An IP (Internet Protocol) address is a numerical label assigned to each device connected to a computer network that uses the Internet Protocol for communication. It serves as an identifier for that device, allowing other devices on the network to locate and communicate with it.

# What are the 2 types of IP Address?

The two main types of IP addresses are:

1. **IPv4 (Internet Protocol version 4):** This is the older and more widely used version of IP addressing. IPv4 addresses are 32 bits long, expressed as four sets of numbers separated by periods (e.g., 192.168.1.1).

2. **IPv6 (Internet Protocol version 6):** IPv6 was developed to address the limitations of IPv4, particularly the exhaustion of available IPv4 addresses. IPv6 addresses are 128 bits long and are expressed as a series of hexadecimal numbers separated by colons (e.g., 2001:0db8:85a3:0000:0000:8a2e:0370:7334).

# What is localhost?

Localhost refers to the loopback network interface of a device, typically assigned the IP address 127.0.0.1. It allows a device to communicate with itself, enabling testing and development of networked applications locally without the need for external connectivity.

# What is a Subnet?

A subnet, short for subnetwork, is a logical subdivision of an IP network. It divides a larger network into smaller, more manageable segments, each identified by a unique subnet address. Subnetting helps optimize network performance, improve security, and facilitate network management by grouping devices based on their location, function, or other criteria.

# Why IPv6 was created?

IPv6 was created to address the limitations of IPv4, primarily the exhaustion of available IPv4 addresses due to the exponential growth of the internet and the increasing number of connected devices. IPv6 provides a vastly expanded address space, allowing for trillions of unique IP addresses to accommodate the growing demand for internet-connected devices and services worldwide.
# TCP/UDP

TCP (Transmission Control Protocol) and UDP (User Datagram Protocol) are the two main transport layer protocols used for communication over IP networks.

# What are the 2 mainly used data transfer protocols for IP (transfer level on the OSI schema)

The two main protocols are:
1. **TCP (Transmission Control Protocol):** A connection-oriented protocol that provides reliable, ordered, and error-checked delivery of data.
2. **UDP (User Datagram Protocol):** A connectionless protocol that offers faster transmission but does not guarantee delivery or order of packets.

# What is the main difference between TCP and UDP

The main difference between TCP and UDP lies in their connection-oriented versus connectionless nature. TCP ensures reliable, ordered, and error-checked delivery of data, whereas UDP provides faster transmission with no guarantee of delivery or order.

# What is a port



A port is a logical endpoint on a computer where network communication is directed. It allows multiple services or applications to operate simultaneously on the same device. Ports are identified by numbers, and they facilitate communication between different applications or services on a network.

# Memorize SSH, HTTP, and HTTPS port numbers

- **SSH (Secure Shell):** Port 22
- **HTTP (Hypertext Transfer Protocol):** Port 80
- **HTTPS (Hypertext Transfer Protocol Secure):** Port 443

# What tool/protocol is often used to check if a device is connected to a network

The ICMP (Internet Control Message Protocol) protocol, specifically the ICMP Echo Request and Echo Reply messages, is commonly used to check if a device is connected to a network. This is often implemented through tools like Ping.
