# Network Appliances & Infrastructure  
### Architecture, Protocols, and Security  


---

## 📌 Overview
This module explains how modern network infrastructure is built, how data moves across devices, and how security is enforced across different layers of the OSI model.

It covers:
- Network hardware appliances
- Routing & switching logic
- IP addressing (IPv4 / IPv6)
- Network security zones
- Common Layer 2 & Layer 3 attacks
- DDoS and mitigation strategies

---

## 🧠 Network Appliances

### 🔌 Switches (Layer 2)
![Network Switch](https://png.pngtree.com/png-vector/20250416/ourlarge/pngtree-a-networking-switch-positioned-on-plain-white-surface-clearly-defined-edges-png-image_16026897.png)
- Forward frames using MAC addresses
- Create VLANs to segment networks
- Reduce broadcast domains

### 📡 Wireless Access Points
![Wireless Access Point](https://static.mercusys.com/product-image/MAP80X_UN_1.0_Overview_normal20250810124759.png)
- Bridge wireless clients to wired networks
- Operate at Layer 2

### 🌐 Routers (Layer 3)
![Network Router](https://e.huawei.com/marketingcloud/pep/asset/2000000101/images/products/routers/ar5710-s/overview-v2.png)
- Forward packets between networks
- Use IP addresses and routing tables
- Enable internetwork communication

### 🔥 Firewalls
![Firewall Device](https://png.pngtree.com/png-vector/20250218/ourlarge/pngtree-firewall-hardware-png-image_15506567.png)
- Enforce security policies using ACLs
- Operate at Layer 3 and above
- Control inbound/outbound traffic

### ⚖️ Load Balancers
![Load Balancer](https://shop.netgate.com/cdn/shop/files/1537_EOS_1024×1024.png?v=1721661621)
- Distribute traffic across servers
- Improve availability & scalability
- Operate at Layer 4 and Layer 7

---

## 🔁 Routing & Switching

### Layer 2 (Switching)
- Uses MAC addresses
- Works inside the same broadcast domain
- VLANs define logical segmentation

### Layer 3 (Routing)
- Uses IP addresses
- Connects different networks
- Enables internetwork communication

---

## 📍 ARP Protocol
- Maps IP → MAC address
- Works via broadcast request + unicast reply

---

## 🌐 IP Addressing
![IPv4 vs IPv6](https://d2cestlyk6hx2d.cloudfront.net/uninets-001/store/3057/article%20images/ipv4-vs-ipv6-infographics.png)

### IPv4
Example: `172.16.1.101/16`
- Network ID: 172.16.0.0
- Host ID: specific device

### IPv6
Example: `2001:db8::abc:0:def0:1234`
- 128-bit addressing
- Designed for scalability

---

## 🏗️ Network Security Zones

- **Intranet:** Trusted internal network  
- **Extranet:** Partners & suppliers  
- **Internet:** Public untrusted access  
- **DMZ:** Controlled perimeter zone  

---

## 🛡️ Common Attacks

### Man-in-the-Middle (MITM)
- Intercepts traffic between two hosts
- Can modify or sniff data

### MAC Spoofing / Cloning
- Fake hardware identity
- Bypass MAC-based controls

### MAC Flooding
- Overloads switch MAC table
- Forces broadcast behavior

---

## 🚨 DDoS Attacks

### Goal
- Exhaust bandwidth and resources

### Mitigation
- Traffic monitoring
- Stateful firewalls
- Load balancing
- IP blocking & rate limiting

---

## ⚖️ Load Balancing

### Layer 4
- Based on IP + ports
- Fast and efficient

### Layer 7
- Application-aware routing
- Based on URL/content type

---

## 🙌 Conclusion
Understanding network infrastructure is essential for cybersecurity defense and offensive security analysis.
