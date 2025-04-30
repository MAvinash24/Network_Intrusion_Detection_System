# 🚀 Network Intrusion Detection System (NIDS)

## 🔍 Overview
The **Network Intrusion Detection System (NIDS)** is a GUI-based application that allows users to monitor network traffic for potential security threats using **Snort** or **Suricata**. The application provides an easy-to-use interface for selecting an NIDS executable and configuration file, starting and stopping monitoring, and displaying alerts in real-time.

## ✨ Features
- 🎛 **User-friendly GUI** built with **Tkinter**
- 📂 **Supports Snort & Suricata** for real-time network monitoring
- ⚙️ **Config file selection** for custom rule sets
- 🟢 **Start & Stop monitoring** with simple button clicks
- 📜 **Live output logs** with color-coded alerts

## 📌 Requirements
Ensure the following dependencies are installed:
- Python 3.x
- `tkinter` (built-in with Python)

Additionally, install **Snort** or **Suricata**:
- [Snort Installation Guide](https://www.snort.org/downloads)
- [Suricata Installation Guide](https://suricata.io/download/)

## 🚀 Installation & Usage
### 1️⃣ Clone the Repository
```bash
git clone https://github.com/MAvinash24/CodeAlpha_Network_Intrusion_Detection_System.git
```
```bash
cd CodeAlpha_Network_Intrusion_Detection_System
```

### 2️⃣ Run the Application
```bash
python nids.py
```

### 3️⃣ Select NIDS Executable & Config
- Click **📂 Select Snort/Suricata** and choose the executable file.
- Click **📂 Select Config File** and select the `.conf` file.

### 4️⃣ Start Monitoring
- Click **▶ Start Monitoring** to begin network analysis.
- The **log output** will display real-time alerts.

### 5️⃣ Stop Monitoring
- Click **⏹ Stop Monitoring** to terminate the process.

## 🛠 Example Output
```plaintext
🚀 Starting Network Monitoring...
[**] [1:1000001:0] Potential attack detected [Classification: Attempted Admin Privilege Gain]
🚨 Monitoring Stopped.
```

---
## Screeshot of GUI:

![image](https://github.com/user-attachments/assets/86602635-481e-4599-8650-518cf321a8fe)

---

## ⚠️ Disclaimer
This tool is intended for **educational and security research** purposes only. Use it responsibly and ensure you have permission to monitor any network traffic.

---
💡 Developed for enhancing **network security awareness & monitoring**.

