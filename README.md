## 📡 College Campus Network - Packet Tracer Simulation

### 🏫 **Overview**
This project represents a **College Campus Network** built using **Cisco Packet Tracer**. The network is segmented into multiple departments, ensuring efficient communication and security.

### 📌 **Network Topology**
The network consists of multiple subnets, each representing different departments:

| Department          | Subnet           | Devices Connected |
|--------------------|----------------|------------------|
| **Internet Lab** | `128.168.0.0/24` | PCs, Printer, Switch |
| **Computer Dept.** | `192.168.2.0/24` | PCs, Printer, Switch |
| **IT Department** | `192.168.1.0/24` | PCs, Printer, Switch |
| **Server Room** | `1.0.0.0/24` | FTP, DNS, Web Servers |
| **Other (Admin, Exam, Office, TPO, etc.)** | `192.168.3.0/24` | PCs, Printers, Switch |
| **Principal Room** | `192.168.4.0/24` | PC, Laptop, Switch |

### 🔧 **Network Devices & Configuration**
- **Routers (`Router0`, `Router2`)**: Handle inter-department communication.
- **Switches (`Switch1`, `Switch2`, `Switch3`, `Switch4`)**: Manage LAN connections.
- **Servers (`FTP, DNS, Web`)**: Located in the **Server Room**.
- **PCs & Printers**: Distributed across different departments.

### ⚡ **Routing & Connectivity**
- **Static / Dynamic Routing (RIP, OSPF, or EIGRP)**
- **Subnet-based segmentation for security and management**
- **VLANs (if configured) to separate departments logically**
- **Access Control Lists (ACLs) to control traffic flow between subnets**
- **NAT (if external internet access is required)**

### 🔍 **Possible Enhancements**
- ✅ Implement **VLANs** for better network segmentation.
- ✅ Use **ACLs** to restrict access to critical servers.
- ✅ Improve **fault tolerance** by adding redundant links.
- ✅ Configure **DHCP** to automatically assign IPs.

---

### 📂 **How to Use**
1. Open the **College Network.pkt** file in **Cisco Packet Tracer**.
2. Test connectivity using `ping` between devices.
3. Configure routers using **static or dynamic routing**.
4. Implement **security policies** as needed.

---

### 📜 **Author**
👤 **Korab Kanwar**  
📌 **NIT Jalandhar | Cybersecurity & Networking Enthusiast**  
