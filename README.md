# 🚧 16-GPU Crypto Mining Rig (3-PC Distributed Build)

## 🛠️ Project Overview
This project documents the design, assembly, and operation of a custom-built GPU mining setup using three independent systems and a total of **16 GPUs**. It was designed to mine Ethereum and operated until the Ethereum merge in 2022.

---

## 💡 Goals
- Maximize GPU utilization across multiple systems  
- Ensure thermal and power efficiency  
- Create a stable, scalable, and remotely manageable mining environment  
- Gain real-world experience in hardware configuration, networking, and system monitoring  

---

## 🧱 Hardware Overview
Each system included:

- **Motherboard** with 4–6 GPU support via PCIe and risers  
- **GPUs**: Total of 16 GPUs — **12 NVIDIA** and **4 AMD** cards  
- **Risers**: Powered PCIe risers (USB 3.0 interface)  
- **PSUs**: Dual power supply configurations (Corsair, EVGA, etc.)  
- **Storage**: Basic SSDs for OS and mining software  
- **Open-air frames** for airflow and accessibility  
- **Cooling**: Fans and directional airflow setup  

---

## 🔧 System Configuration
- **Mining OS**: Windows and HiveOS  
- **Mining Software**: PhoenixMiner, lolMiner  
- **Pool**: [Ethermine](https://ethermine.org)  

### BIOS Optimization
- Enabled Above 4G Decoding  
- Disabled CSM  
- PCIe Gen settings tuned for riser compatibility  

### GPU Tuning
- Overclocking/Undervolting per GPU model  
- Managed mixed-driver configurations for NVIDIA and AMD cards  

### Power Draw
- ~3000–3500W peak, balanced across PSUs and circuits  

---

## 🌐 Networking & Monitoring
- Dedicated **Ethernet switch** connected to home router  
- Static/local IPs for each system  
- Centralized monitoring via **HiveOS dashboard** and **Ethermine web portal**  
- Real-time tracking of hashrates, payouts, stale shares, and uptime  

---

## 🧠 Skills Developed
- Hardware troubleshooting and component-level diagnostics  
- Mixed GPU environment management (NVIDIA + AMD)  
- BIOS configuration and multi-GPU system optimization  
- Power and thermal load management across multiple systems  
- Network setup and remote dashboard monitoring  
- Experience managing production-level uptime and performance  
