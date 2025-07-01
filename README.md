# Wireshark_project
Wireshark project for vulnerability Analysis
# Wireshark Network Traffic Capture and Analysis

## 📌 Overview
This project demonstrates a basic network traffic capture using Wireshark. It includes generating traffic, filtering protocols, and exporting the capture to a `.pcap` file for further analysis.

---

## 🛠️ Steps Performed

1. **Installed Wireshark**
   - Downloaded and installed the latest version of Wireshark on my machine.

2. **Started Capturing**
   - Selected my active network interface (e.g., `eth0` or `wlan0`).
   - Began capturing live network packets.

3. **Generated Network Traffic**
   - Opened a web browser and visited multiple websites.
   - Ran a simple `ping` command to a known server to generate ICMP traffic.

4. **Stopped the Capture**
   - Captured packets for approximately 1 minute.
   - Stopped the capture to analyze the traffic.

5. **Filtered Packets by Protocol**
   - Applied display filters for `http`, `dns`, and `tcp` to inspect different protocols.

6. **Identified Multiple Protocols**
   - Verified that the capture included at least three protocols:
     - ✅ **HTTP** – Browsing websites.
     - ✅ **DNS** – Domain name resolutions.
     - ✅ **ICMP** – Ping packets.

7. **Exported the Capture**
   - Saved the filtered packets to a `.pcap` file for documentation and sharing.

8. **Summary of Findings**
   - Observed the clear-text nature of HTTP requests, including potential credentials.
   - Analyzed DNS queries to see domains being resolved.
   - Checked ICMP echo requests and replies to verify connectivity.

---

## 🔗 File
- **Output:** `network-capture.pcap`

---

## 📊 Key Takeaways
- Wireshark is a powerful tool for analyzing live network traffic.
- Using display filters (`http`, `dns`, `tcp`, `icmp`) helps isolate relevant packets.
- Exporting captures is essential for sharing and further offline analysis.

---

## ⚡ Skills Practiced
- Packet capturing
- Protocol analysis
- Filtering and exporting PCAP files

---
