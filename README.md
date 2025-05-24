# 🧪 Network Protocol Analysis using Wireshark and Python

## 📌 Project Overview

This project explores the behavior and structure of key network protocols through real traffic analysis using **Wireshark** and **Python**. The focus is on three core areas:

- **ICMP (Internet Control Message Protocol)**
- **MPLS Traceroute Traffic**
- **IPv6 Neighbor Discovery Protocol (NDP)**

By analyzing `.cap` files and automating the inspection process with Python and Pyshark, the project provides hands-on experience in protocol behavior, packet inspection, and data-driven reporting.

---

## 🛠 Tools & Technologies

- **Wireshark** – Network protocol analyzer
- **Python 3.x**
- **Libraries:**
  - [`pyshark`](https://github.com/KimiNewt/pyshark) – Python wrapper for Wireshark’s TShark
  - `matplotlib`, `seaborn` – For visualizations

---

## 🧭 Project Workflow

### 1. **Capture Network Traffic**
Use Wireshark to record traffic relevant to:
- ICMP communication
- IPv6 Neighbor Discovery
- MPLS-based traceroute

Save each capture as a `.cap` file.

---

### 2. **ICMP Protocol Analysis**
- Load and inspect `icmp.fragmented.cap` in Wireshark.
- Use Python + Pyshark to extract ICMP packet information.
- Analyze:
  - Packet types (e.g., Echo Request/Reply)
  - Fragmentation behavior
  - Packet statistics

---

###
