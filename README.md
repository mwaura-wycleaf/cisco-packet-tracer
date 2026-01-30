
# Cisco Packet Tracer – Home / Office Network Simulation

## 📌 Project Overview
This project demonstrates a basic home/office network designed and simulated using **Cisco Packet Tracer**.  
The goal is to show correct device placement, cabling, IP addressing, and successful end-to-end connectivity.

---

## 🧱 Network Components
The network consists of the following devices:
- 1 × Router
- 1 × Switch
- 1 × Wireless Router
- 3 × PCs
- Copper straight-through cables

---

## 🗺️ Network Topology
- The **Router** is connected to the **Switch**
- The **Switch** connects to all **wired PCs**
- The **Wireless Router** is connected to the **Switch via a LAN port**
- All physical connections are active (green)

---

## 🌐 IP Addressing Scheme

| Device | IP Address | Subnet Mask | Default Gateway |
|------|-----------|-------------|----------------|
| Router | 192.168.10.1 | 255.255.255.0 | — |
| PC 1 | 192.168.10.2 | 255.255.255.0 | 192.168.10.1 |
| PC 2 | 192.168.10.3 | 255.255.255.0 | 192.168.10.1 |
| PC 3 | 192.168.10.4 | 255.255.255.0 | 192.168.10.1 |
| Wireless Router | 192.168.10.5 | 255.255.255.0 | 192.168.10.1 |

> All PCs use **static IP addressing**.

---

## ⚙️ Configuration Summary
- Router interfaces were enabled using `no shutdown`
- Correct copper straight-through cables were used
- Wireless Router connected via **LAN port (not Internet port)**
- DHCP disabled on the Wireless Router
- All devices configured within the same subnet

---

## 🧪 Testing & Verification
- Successful **ping** between all PCs
- Successful **ping** to the router
- Simulation mode confirms packet delivery
- All devices respond correctly without packet loss

---

## 📁 Project Files
- `.pkt` file containing the complete Packet Tracer simulation
- `README.md` explaining the network design and configuration

---

## 🎯 Conclusion
The network was successfully designed and simulated.  
All devices are properly connected, configured, and able to communicate, meeting the requirements of a basic home/office LAN.

---

## 🧠 Author
Created as part of a Cisco Packet Tracer networking assignment.
