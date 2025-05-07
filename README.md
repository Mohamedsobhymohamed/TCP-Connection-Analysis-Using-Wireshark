# TCP Connection Analysis with Wireshark

This project is a basic analysis of a TCP connection captured using **Wireshark**. It explains key TCP mechanisms such as the **3-way handshake**, **data transfer**, and **retransmissions**, using real captured packets from a file upload.

## 📁 Project Overview

The goal of this analysis is to:
- Understand how a TCP connection is established and closed.
- Analyze how data flows over TCP.
- Detect retransmissions and understand why they occur.

## 📘 What You'll Learn

- How TCP 3-way handshake works (SYN, SYN-ACK, ACK).
- How to recognize a successful TCP connection in Wireshark.
- How data transfer is done in segments with sequence and acknowledgment numbers.
- How to detect retransmissions using filters in Wireshark.

## 🛠 Tools Used

- **Wireshark** – to open and analyze the `.pcap` file.
## 🔍 How to Use

1. Open the `.pcap` file in Wireshark.
2. Use filters such as:
   - `tcp` – to see only TCP packets.
   - `tcp.analysis.retransmission` – to find retransmitted packets.
3. Read the attached PDF report for step-by-step explanations and packet references.

## 📄 Files
- `tcp_upload_capture.pcap` – Wireshark capture file of a TCP file upload.
- `README.md` – This file.

## ✅ Key Terms Explained

- **3-Way Handshake**: Connection setup using SYN, SYN-ACK, and ACK.
- **Retransmission**: Resending a lost or unacknowledged packet.
- **Sequence Number**: Tracks data byte positions in the stream.
- **Acknowledgment Number**: Confirms receipt of data.

## 👤 Author

**Mohamed Sobhy**  
Faculty of Engineering, Alexandria University  
Computer and Communication Department  
