PROJECT BACKGROUND
As part of a cloud infrastructure modernization initiative, I was tasked with designing and securing the network layer for a web application hosted on Microsoft Azure.

The environment required:
Network isolation between application components
Granular control of inbound and outbound traffic
Centralized inspection of network communications
Controlled routing through security appliances
Reliable internal DNS services

To address these requirements, I implemented a hub-and-spoke Azure networking architecture using Virtual Networks, Network Security Groups, Azure Firewall, User Defined Routes, and Azure DNS.

OBJECTIVES
Design a hub-and-spoke network architecture
Segment application workloads using subnets
Secure traffic using Network Security Groups (NSGs)
Protect perimeter traffic using Azure Firewall
Control traffic flow using User Defined Routes (UDRs)
Implement private name resolution using Azure DNS
Solution Architecture
architecture/azure-network-architecture.png

TECHNOLOGY STACK
Technology	                          Purpose
Azure Virtual Network	                Network segmentation
Azure VNet Peering	                  Private connectivity
Azure Network Security Groups	        Traffic filtering
Azure Firewall	                      Centralized network security
Azure Route Tables	                  Traffic routing
Azure DNS Zones	                      Name resolution
Azure Portal	                        Resource deployment
PowerShell	                          VM deployment automation

PROJECT PHASES
Phase	  Description
Part 1	Create and Configure Virtual Networks
Part 2	Create and Configure Network Security Groups
Part 3	Create and Configure Azure Firewall
Part 4	Configure Network Routing
Part 5	Configure DNS Zones

Detailed Documentation
part-01-virtual-network/README.md
part-02-network-security-groups/README.md
part-03-azure-firewall/README.md
part-04-network-routing/README.md
part-05-dns-zones/README.md

Key Skills Demonstrated
Azure Network Design
Hub-and-Spoke Architecture
Virtual Network Peering
Network Traffic Filtering
Azure Firewall Administration
Route Table Configuration
DNS Administration
Infrastructure Documentation

Author
Chinedu Ukaegbu
Technology Support Officer | Azure Administrator | Cloud Engineer Aspirant
GitHub:   LinkedIn:  
