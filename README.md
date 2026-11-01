<<<<<<< HEAD
niversity Campus Network Design

An enterprise-grade campus network architecture simulated in **Cisco Packet Tracer**, spanning two campuses located 20 miles apart. This repository contains the complete network topology, configuration scripts, and documentation fulfilling all coursework requirements.

## 🌐 Network Architecture & Scope

* **Main Campus:**
  * **Building A:** Administrative staff (Management, HR, Finance) and Faculty of Business[cite: 5]. Features VLAN segmentation and dynamic IP allocation via a router-based DHCP server[cite: 5].
  * **Building B:** Faculty of Engineering & Computing and Faculty of Art & Design[cite: 5].
  * **Building C:** Student computer labs and the central IT department hosting internal services (University Web server)[cite: 5].
* **Smaller Campus (Remote Site):**
  * **Faculty of Health and Sciences:** Located 20 miles away with staff offices and student labs distributed across separate floors[cite: 5].
* **External Services:** 
  * Cloud-hosted external email server connected via wide-area routing[cite: 5].

## ⚙️ Technical Implementation

* **VLAN Segmentation & Security:** Switches configured with specific VLAN IDs and port security policies to isolate departmental traffic[cite: 5].
* **Inter-VLAN Routing:** Implemented via Layer 3 switching or Router-on-a-Stick configurations[cite: 5].
* **Dynamic Addressing:** Centralized router-based DHCP server automating address assignment for Building A[cite: 5].
* **Routing Protocols:** **RIPv2** routing deployed across internal network routers, supplemented by static routing for external cloud server reachability[cite: 5].

## 📊 IP Addressing & VLAN Summary Table

| VLAN ID | Department / Faculty | Network Address | Subnet Mask | Default Gateway |
| :--- | :--- | :--- | :--- | :--- |
| **10** | Administration (Mgmt/HR/Finance)[cite: 5] | `192.168.10.0` | `255.255.255.0` | `192.168.10.1` |
| **20** | Faculty of Business[cite: 5] | `192.168.20.0` | `255.255.255.0` | `192.168.20.1` |
| **30** | Engineering, Computing & Art/Design[cite: 5] | `192.168.30.0` | `255.255.255.0` | `192.168.30.1` |
| **40** | Student Labs & IT Services[cite: 5] | `192.168.40.0` | `255.255.255.0` | `192.168.40.1` |
| **50** | Health and Sciences (Remote Campus)[cite: 5] | `192.168.50.0` | `255.255.255.0` | `192.168.50.1` |

## 📁 Repository Structure

```text
albion-campus-network/
├── README.md                  # Project documentation
├── topology/
│   └── albion-network.pkt     # Cisco Packet Tracer simulation file
├── configs/                   # Device CLI running configurations (.txt)
└── docs/                      # Detailed technical report and evaluation document

=======
# University_Network_Design
This project plans, simulates, and evaluates an enterprise campus network architecture for the university, spanning two campuses 20 miles apart. It supports four faculties (Health/Sciences, Business, Engineering/Computing, Art/Design), admin departments, student labs, and centralized IT services with routing, VLANs, and security.
>>>>>>> 4cc1f8a8494545a28c0aef376199a974d79496ed
