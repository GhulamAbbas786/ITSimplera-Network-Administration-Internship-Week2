# ITSimplera-Network-Administration-Internship-Week2
Technical documentation, network topologies, and lab configurations completed during my Network Administration Internship at ITSimplera Institute. Features advanced IP subnetting (FLSM/VLSM) designs, Layer 2 VLAN segmentation, and multi-platform simulation testing using Cisco Packet Tracer and GNS3.
# 🌐 ITSimplera Network Administration Portfolio

> **Network Administration Internship Project Milestone** • *Engineering scalable, secure, and optimized enterprise network infrastructures.*

---

## 🚀 Week 2 Milestone: Enterprise Subnetting & Layer 2 Segmentation

This phase focuses on shifting away from legacy network designs to construct optimized, highly secure network topologies using advanced subnets and virtual segregation across multiple industry-standard simulators.

### 🛠️ Tech Stack & Lab Environment
* **Simulators:** `Cisco Packet Tracer` 🛠️ & `GNS3` 🚀
* **Design Logics:** FLSM (Fixed-Length) & VLSM (Variable-Length) Subnetting
* **Protocols & OS:** Cisco IOS, IEEE 802.1Q (Dot1q) Trunking

---

## ⚡ Key Accomplishments

### 📊 1. IP Optimization Matrix
* **Precision Engineering:** Solved 10 FLSM foundational math problems and engineered 5 custom VLSM infrastructure scenarios.
* **Zero-Waste Allocation:** Designed an IP scheme tailored precisely to multi-department host requirements instead of defaulting to wasteful equal blocks.

### 🔒 2. VLAN Deployment & Traffic Isolation
* **Broadcast Containment:** Implemented Virtual Local Area Networks (VLANs) to enforce traffic boundaries independent of physical switch locations.
* **Trunking Architecture:** Established robust 802.1Q trunking to transport multi-VLAN traffic across distinct switch nodes.

### 🔧 3. Real-World Lab Troubleshooting
* **The "One-Sided Trunk" Fix:** Diagnosed and resolved a common enterprise misconfiguration where one side of a link was hardcoded to a trunk while the other side was stuck in `dynamic auto`.
* **Verification-First Mindset:** Abandoned "assuming it works" by using explicit IOS verification logic:
  ```bash
  Switch# show vlan brief
  Switch# show interfaces trunk
  Switch# show interfaces switchport
