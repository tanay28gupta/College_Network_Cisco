# College Network Scenario

## Overview
The "College Network Scenario" project focuses on designing and implementing an efficient Local Area Network (LAN) for a college campus. The project aims to enhance network security, optimize performance, and ensure seamless communication between different departments. This network design is based on Cisco Packet Tracer and includes VLAN configurations, IP addressing, routing protocols, and network security measures.

## Objectives
- Upgrade the existing college network infrastructure.
- Improve network security and reliability.
- Minimize network downtime and optimize performance.
- Ensure seamless communication between different departments.
- Implement VLANs for better segmentation and management.
- Provide remote access capabilities.

## Network Requirements
- Internet speed should be maintained above 5 Mbps.
- Network scalability for future expansion.
- Secure data centers with enhanced security features.
- Remote access support for administrators and faculty.

## Existing Infrastructure
The college's current network has a basic setup with limited security and outdated switches. Some of the key issues include:
- Static IP assignment without dynamic allocation.
- Limited network segmentation, leading to security risks.
- Lack of remote access and monitoring capabilities.
- Outdated network devices.

## Proposed Network Design
The upgraded network will include:
- **IP-based switches** for better performance and traffic monitoring.
- **VLAN segmentation** for different departments to enhance security.
- **Cisco Aironet 1140 access points** for seamless wireless connectivity.
- **Unified Computing System (UCS)** for integrating computing, storage, and virtualization.
- **Routing Protocols (RIP, OSPF, BGPv4, EIGRP)** for efficient data transmission.

## Network Devices Used
- Cisco Catalyst 6509 switches with Cisco 720 supervisors.
- Cisco 4500 switches with 10 Gb/s bandwidth.
- Cisco firewall for enhanced security.
- Mobility Services Engine (MSE) for improved wireless networking.
- Cisco Aironet 1140 access points for wireless coverage.
- Unified Computing System (UCS) for integrating multiple network services.

## IP Addressing Plan
| Department | Subnet | Devices |
|------------|--------|---------|
| IT Department | 192.168.1.0 | HOD Cabin, IT Labs, Printers |
| CS Department | 192.168.2.0 | CS HOD Cabin, CS Labs, Printers |
| Office | 192.168.3.0 | Office, Exam Cell, Enquiry, TPO |
| Server Room | 1.0.0.0 | FTP Server, DNS Server, Web Server |
| Internet Lab | 128.168.0.0 | PCs, Printers |
| Principal Room | 192.168.4.0 | PC, Laptop |

## Routing Protocols Used
- **Routing Information Protocol (RIP)** is used as a dynamic routing protocol to determine the best path between networks based on hop count.
- **Open Shortest Path First (OSPF), Border Gateway Protocol (BGPv4), and Enhanced Interior Gateway Routing Protocol (EIGRP)** are available for improved routing efficiency.

## Network Implementation
- VLAN configurations were set up to segment traffic between departments.
- Routing tables were designed and implemented using Cisco Packet Tracer.
- Firewall settings were configured to enhance security and prevent unauthorized access.
- Testing included VLAN communication, FTP server access, and web hosting validation.

## Expected Outcomes
- A fail-safe backbone network infrastructure.
- Secure and efficient data transmission between departments.
- Scalable and future-ready network architecture.
- Optimized productivity with reliable telecommunication services.

## References
1. Sun, L., Wu, J., Zhang, Y., & Yin, H. (2013). "Comparison between physical devices and simulator software for Cisco network technology teaching." IEEE.
2. Roberto Minerva AbiyBiru, "Towards a Definition of the Internet of Things" IEEE IOT Initiative white paper.
3. "Design and Simulation of Local Area Network Using Cisco Packet Tracer." International Journal of Engineering and Science, 2017.
4. Qin, X. "Simulation Experimental Teaching of Computer Network Based on Packet Tracer."
5. Current, J. R., ReVelle, C. S., & Cohon, J. L. "The hierarchical network design problem." European Journal of Operational Research, 1986.



