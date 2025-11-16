📘 AuroraShield Enterprise Network — Cisco Professional Submission
🔍 Overview

AuroraShield Enterprise Network წარმოადგენს სრული მასშტაბის, მულტილეველ, უსაფრთხო და რედუნდანტულ კორპორატიულ ქსელს Dual–ISP Failover არქიტექტურით.
პროექტი შექმნილია Cisco-ს ოფიციალური სტანდარტების მიხედვით და მოიცავს:

Enterprise Core & Distribution Layer redundancy

Multilayer Switching (L2/L3 switching)

Dynamic Routing (OSPFv2, MD5 Authentication)

Dual-ISP Failover (Primary/Backup ISP)

Enterprise Security (ACL, Port-Security, DHCP Security)

VLAN segmentation (Management, IT, Web, DB, Accounting, HR, Admin)

Servers Integration (Web, FTP, IC-Server, Admin)

Full DHCP Infrastructure across all Access Networks

High-Availability Topology across entire campus

🏗 Architecture Highlights

3-Layer Architecture: Core → Distribution → Access

Dynamic Routing: OSPF Area 0

Point-to-Point routed links: /30 and /31 subnets

3-level department structuring: HR, IT-Service, Accounting, Management

High-Availability ISP Redundancy: ISP1 (primary), ISP2 (backup)

Complete Server Room Integration

Enterprise-Level Security Policies

🗂 Repository Structure
AuroraShield_Enterprise_Network/
│
├── Configurations/              
│     └── Full-Device-Configs.pdf
│
├── Diagrams/
│     └── Enterprise-Topology.png
│
├── Documentation/
│     └── AuroraShield-Enterprise-Campus.pdf
│
├── Presentation/
│     └── AuroraShield-Enterprise-Campus.pptx
│
├── Submission/
│     └── AuroraShield-Enterprise-Network.7z
│
└── README.md

🧩 Folder Descriptions
📁 Configurations/

შეიცავს ყველა Router/Switch-ის სრული კონფიგურაციების PDF-ს
IOS 15.2+ და L2/L3 IOU/VIOS მოწყობილობების სრული output:

Interface Configuration

OSPF MD5 Authentication

DHCP Pools

NAT Overload

ACL Rules

VLAN & Trunking

Port Security

Server Network Integration

📁 Diagrams/

📌 High-Resolution PNG Enterprise Topology Diagram
შეიცავს:

Full network map

Distribution layer interconnects

Server room layout

ISP failover scheme

Routed interlinks (/30)

VLAN Segments Diagram

📁 Documentation/

📘 AuroraShield Enterprise Campus – Full Documentation (PDF)
შეიცავს:

Network Overview

Functional Description

IP Addressing Plan

VLAN Table

Routing Design

Server Architecture

Security Architecture

Failover Mechanisms

📁 Presentation/

🎤 PowerPoint Presentation როგორც ოფიციალური Cisco-სთვის შესათავაზებელი:

Architecture Summary

Technical Breakdown

Topology Flow

Security Overview

Failover Testing Results

📁 Submission/

📦 Final 7z/ZIP package for Cisco Review
