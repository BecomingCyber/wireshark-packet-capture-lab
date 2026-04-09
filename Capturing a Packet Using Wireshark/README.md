# 🧪 Lab: Capturing a Packet Using Wireshark

---

## 📌 Objective

Capture and analyze network traffic to understand communication patterns and identify potential security risks.

---

## 🧰 Tools

- Wireshark
- Web Browser

---

## 🌐 Step 1: Interface Selection

![Interface](Screenshots/interface-selection.png)

Selected active network interface with live traffic.

---

## ▶️ Step 2: Start Capture

![Capture](Screenshots/capture-start.png)

Packet capture initiated.

---

## 🌍 Step 3: Generate Traffic

![Browser](Screenshots/browser-traffic.png)

Accessed website to generate network traffic.

---

## 📡 Step 4: Captured Packets

![Packets](Screenshots/captured-packets.png)

Packets successfully captured.

---

## 🔍 Step 5: HTTP Filter

![HTTP](Screenshots/http-filter.png)

Filtered traffic using `http`.

---

## 📋 Step 6: Packet List

![List](Screenshots/packet-list-pane.png)

Observed communication between client and server.

---

## 🧠 Step 7: Packet Details

![Details](Screenshots/packet-details-pane.png)

Inspected protocol layers: IP, TCP, HTTP.

---

## 🔎 Step 8: HTTP Fields

![Fields](Screenshots/expanded-http-fields.png)

Identified:
- GET request
- Host
- User-Agent

---

## 🔗 Step 9: TCP Stream

![TCP Option](Screenshots/tcp-stream-option.png)  
![TCP Window](Screenshots/tcp-stream-window.png)

Reconstructed session data.

---

## 🌐 Step 10: HTTP Stream

![HTTP Option](Screenshots/http-stream-option.png)  
![HTTP Window](Screenshots/http-stream-window.png)

Viewed full request/response.

---

## 💾 Step 11: Save Capture

![Save](Screenshots/save-capture-dialog.png)

Exported `.pcapng` file.

---

## 🚨 Key Findings

- HTTP traffic is unencrypted  
- Data visible in plaintext  
- Sessions can be reconstructed  
- Potential credential exposure  

---

## 🧠 SOC Insight

This demonstrates how attackers can intercept sensitive data over insecure protocols and how analysts detect it.

---

## 🎯 Conclusion

Wireshark is essential for packet analysis, incident response, and network forensics.
