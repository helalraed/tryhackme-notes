# 🎨 Wireshark Notes

## 📊 Packet Colours

| Severity | Colour | Meaning                     |
| -------- | ------ | --------------------------- |
| Chat     | Blue   | Normal traffic              |
| Note     | Cyan   | Notable events              |
| Warn     | Yellow | Warnings / unusual activity |
| Error    | Red    | Errors / malformed packets  |

---

## 🔍 What is Wireshark?

Wireshark is a network protocol analyzer used to capture and inspect packets in real time.

---

## 🧠 Key Features

* Capture live network traffic
* Analyze packets in detail
* Apply filters to focus on specific traffic
* Follow streams (TCP/HTTP)
* Detect anomalies and attacks

---

## 🔧 Useful Filters

```plaintext
http
tcp.port == 80
ip.addr == 192.168.1.1
```

---

## 🔍 Important Features

### 🎯 Follow Stream

* Reconstructs full communication
* Can reveal:

  * usernames
  * passwords
  * data

---

### 🎨 Colouring Rules

* Helps identify traffic quickly
* Can create custom rules

---

### 📊 Columns

* Add specific fields (IP, Port, etc.)
* Helps analyze patterns

---

## 💡 Notes

* Used in:

  * Network troubleshooting
  * Incident response (SOC)
  * Malware analysis
* Unencrypted traffic (HTTP, Telnet) can expose sensitive data
* HTTPS traffic is encrypted

---

## 🚨 Security Insight

* Wireshark can capture credentials if traffic is not encrypted
* Always prefer secure protocols (HTTPS, SSH)

---

## 🎯 Takeaways

* Wireshark is essential for Blue Team
* Filtering is the most important skill
* Always check for unencrypted data
