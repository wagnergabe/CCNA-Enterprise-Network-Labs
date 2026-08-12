# CCNA Enterprise Network Labs

Hands-on Cisco networking portfolio demonstrating enterprise network design, routing, switching, network services, security, and troubleshooting using Cisco IOS and Cisco Packet Tracer.

This repository contains a progression of networking labs ranging from individual routing and switching concepts to a multi-site enterprise network capstone. Each project includes the Packet Tracer topology, technical documentation, and configuration or verification evidence where applicable.

---

## Featured Project — Enterprise Network Infrastructure Capstone

![Enterprise Network Capstone](enterprise-capstone/topology.png)

Designed and configured a three-site routed enterprise network combining dynamic routing, centralized network services, traffic filtering, and secure remote administration.

### Architecture

- Three routed `/24` LANs
- Two point-to-point `/30` WAN networks
- Three Cisco routers
- Three access switches
- Centralized DHCP, DNS, NTP, and file services
- OSPF dynamic routing between sites

### Key Implementations

- Configured OSPF Area 0 across a multi-router WAN
- Implemented centralized DHCP with DHCP relay for remote networks
- Configured centralized DNS and NTP services
- Applied extended ACLs to restrict FTP access to centralized resources
- Configured SSH-only remote administration
- Verified OSPF adjacencies and dynamically learned routes
- Performed end-to-end connectivity and configuration troubleshooting

The capstone includes CLI verification screenshots demonstrating OSPF operation, DHCP configuration, DHCP relay, ACL policy, SSH configuration, and centralized network services.

[View Enterprise Capstone](enterprise-capstone/)

---

# Networking Projects

## VLAN & Inter-VLAN Routing

Built a segmented network using multiple VLANs and router-on-a-stick routing.

**Technologies:** VLANs • 802.1Q Trunking • Inter-VLAN Routing • IPv4

[View Project](vlan-routing/)

---

## DHCP & DNS Services

Configured centralized network addressing and name-resolution services for client systems.

**Technologies:** DHCP • DNS • IPv4 Addressing • Network Services

[View Project](dhcp-dns/)

---

## VLAN Segmentation & ACL Security

Implemented traffic-control policies between departmental networks while preserving required connectivity.

**Technologies:** Extended ACLs • Network Segmentation • Traffic Filtering • Cisco IOS

[View Project](acl-security/)

---

## OSPF WAN Routing

Built a three-router WAN using point-to-point links and OSPF dynamic routing.

The lab demonstrates neighbor formation, route advertisement, routing-table analysis, and connectivity between remote LANs.

**Technologies:** OSPF • Dynamic Routing • `/30` WAN Subnetting • IPv4 • Route Verification

[View Project](ospf-wan/)

---

## STP, Port Security & BPDU Guard

Built a redundant Layer 2 topology and implemented switching protections.

The lab includes CLI verification demonstrating STP root bridge selection and active port-security configuration.

**Technologies:** STP • Root Bridge Selection • Port Security • BPDU Guard • Layer 2 Switching

[View Project](stp-port-security/)

---

# Skills Demonstrated

### Routing & Switching

- Cisco IOS configuration
- IPv4 addressing and subnetting
- VLANs and 802.1Q trunking
- Inter-VLAN routing
- OSPF dynamic routing
- Point-to-point WAN networking
- Spanning Tree Protocol
- Port security
- BPDU Guard

### Network Services

- DHCP
- DHCP relay
- DNS
- NTP
- Centralized network services

### Network Security

- Standard and extended ACL concepts
- Traffic filtering
- Network segmentation
- SSH remote administration
- Access-layer security

### Troubleshooting & Verification

- Routing-table analysis
- OSPF neighbor verification
- Interface and addressing verification
- DHCP troubleshooting
- ACL verification
- Ping and traceroute
- Cisco IOS `show` commands
- End-to-end connectivity testing

---

# Repository Structure

```text
CCNA-Enterprise-Network-Labs/
│
├── enterprise-capstone/
│   ├── README.md
│   ├── Enterprise WAN.pkt
│   ├── topology.png
│   └── verification screenshots
│
├── vlan-routing/
├── dhcp-dns/
├── acl-security/
├── ospf-wan/
└── stp-port-security/
```

Each project directory contains its own README with implementation details, topology documentation, and relevant Packet Tracer files.

---

## About This Portfolio

These projects were built as hands-on implementations of networking concepts covered through CCNA study and certification.

The goal of this repository is to demonstrate practical configuration and troubleshooting ability beyond certification alone, including the ability to design networks, configure Cisco IOS devices, verify operation, identify connectivity problems, and document technical work.