# 🔍 Nmap Notes

## 🎯 Host Discovery

```bash id="6a4y3c"
nmap -sn <target>
nmap -sL <target>
```

---

## 🚪 Port Scanning

| Option | Description        |
| ------ | ------------------ |
| -sT    | TCP Connect Scan   |
| -sS    | SYN Scan (Stealth) |
| -sU    | UDP Scan           |
| -F     | Fast scan          |
| -p-    | Scan all ports     |

---

## 🧠 Important

* Without sudo → -sT
* With sudo → -sS

---

## 🧬 Detection

```bash id="6m1yqk"
nmap -O <target>
nmap -sV <target>
nmap -A <target>
```

---

## ⚡ Timing

| Level | Name       |
| ----- | ---------- |
| T0    | paranoid   |
| T4    | aggressive |

---

## 💡 Notes

* Nmap uses ICMP, TCP SYN, ACK
* Not only ping
