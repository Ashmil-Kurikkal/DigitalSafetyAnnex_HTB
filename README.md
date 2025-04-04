# 🛠️ DSA Nonce Brute-Forcer (CPU Multiprocessing)


## 🚀 Overview  
This script is designed to brute-force the **nonce (k)** used in a **DSA (Digital Signature Algorithm)** signing process, leveraging **multiprocessing** for faster computation.  The script expects a known p, q, g and a known (r,s) value.

It targets **weak nonce generation vulnerabilities** and attempts to recover the **private key** using a brute-force approach.  

---

## 🔍 Features  
- **Parallel brute-forcing** using Python's multiprocessing module.  
- **Optimized CPU usage** to speed up calculations.  
- **Supports large keyspaces** without requiring GPU acceleration.  
- **Interactive user input** for flexibility in testing different DSA parameters.  

---

## 🛠️ Requirements  
- Python 3.x  
- **Multiprocessing module** (built into Python)  
- `pyfiglet`
- `colorama`

---

## 📦 Installation
```bash
git clone https://github.com/k3yb0ard/DSA-Nonce-Bruteforcer.git  
cd DSA-Nonce-Bruteforcer  
pip install -r requirements.txt  
```
## 🔹Usage

1. Clone the repository:
   ```sh
   python brute_force.py

## 🔹 Performance Considerations
High CPU Usage: The script utilizes all available CPU cores, leading to 100% utilization.

Thermal Throttling: Extended usage may cause overheating on inadequately cooled systems.

Optimizing Performance:

Adjust the worker process count to balance speed and CPU load.

## 🔹 Disclaimer
This script is intended for educational and ethical hacking purposes only.
Unauthorized use against real-world systems is strictly prohibited.
