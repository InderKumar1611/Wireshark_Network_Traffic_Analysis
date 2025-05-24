# 🧪 Network Protocol Analysis with Wireshark and Python

## 📌 Project Overview

This project explores network protocol analysis using **Wireshark** and **Python scripting**. The focus is on analyzing key network protocols — **ICMP (Internet Control Message Protocol)**, **MPLS (Multiprotocol Label Switching)**, and **IPv6 Neighbor Discovery Protocol (NDP)** — through real-world traffic captures.

By leveraging tools like **Wireshark** and the **pyshark** Python library, this project demonstrates how to extract, analyze, and visualize protocol behaviors to gain deeper insights into network communications.

---

## 🛠️ Tools & Technologies

* **Wireshark** – Network packet capture and analysis tool
* **Python 3.x** – For scripting and protocol parsing
* **pyshark** – A Python wrapper for Wireshark's tshark utility
* **matplotlib / seaborn** – For data visualization
* Optional: Interactive visualization tools or dashboard libraries (e.g., Plotly, Dash)

---

## 📋 Project Steps

### 1. Capture Network Traffic

* Use Wireshark to collect traffic related to ICMP, MPLS-Traceroute, and IPv6 NDP.
* Save the capture sessions as `.cap` files for analysis:

  * `icmp.fragmented.cap`
  * `traceroute_MPLS.cap`
  * `IPv6_NDP.cap`

---

### 2. ICMP Packet Analysis

* Open `icmp.fragmented.cap` in Wireshark and inspect ICMP packet structure and fragmentation.
* Write Python scripts using `pyshark` to:

  * Parse and extract ICMP packets
  * Identify fragmented packets
  * Calculate and display ICMP-related statistics (e.g., packet counts, types, fragmentation details)

---

### 3. MPLS Traceroute Analysis

* Load `traceroute_MPLS.cap` in Wireshark to observe how MPLS affects routing paths.
* Using `pyshark`:

  * Extract MPLS-labeled packets
  * Analyze label stack entries, TTL values, and traceroute hops
  * Output key MPLS-related metrics and patterns

---

### 4. IPv6 NDP Analysis

* Analyze `IPv6_NDP.cap` to identify Neighbor Solicitation and Advertisement messages.
* Use Python scripts to:

  * Parse NDP packet contents (e.g., source/target addresses, options)
  * Categorize and count different NDP message types
  * Summarize IPv6 network discovery behavior

---

### 5. Integration & Reporting

* Merge insights from ICMP, MPLS, and NDP analyses.
* Create a unified Python report:

  * Display protocol-specific stats and summaries
  * Generate visualizations (using matplotlib/seaborn) for easier interpretation
  * (Optional) Build interactive dashboards for deeper data exploration

---

## 📈 Example Outputs

* ICMP Type/Code distribution bar charts
* MPLS label stack visualizations
* IPv6 NDP message flow diagrams
* Fragmentation and hop-count statistics

---

## ✅ Conclusion

This project offers a practical hands-on experience in network protocol analysis, combining packet inspection with Python automation. By working with actual packet captures, you'll gain:

* A deeper understanding of protocol internals
* Experience in dissecting and interpreting network data
* The ability to automate network analysis for faster troubleshooting and reporting

Whether you're a network engineer, cybersecurity analyst, or learner, this project enhances your ability to investigate and understand real-world network behavior.

---

## 📁 File Structure (Example)

```
.
├── captures/
│   ├── icmp.fragmented.cap
│   ├── traceroute_MPLS.cap
│   └── IPv6_NDP.cap
├── analysis/
│   ├── icmp_analysis.py
│   ├── mpls_analysis.py
│   ├── ndp_analysis.py
│   └── report_generator.py
├── visualizations/
│   └── *.png
├── README.md
└── requirements.txt
```

---

## 🛆 Installation & Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/network-protocol-analysis.git
   cd network-protocol-analysis
   ```

2. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

3. Add your `.cap` files to the `captures/` directory and run the analysis scripts.

---

##
