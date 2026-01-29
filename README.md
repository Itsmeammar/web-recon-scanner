# Web Recon Scanner

**Author:** Ammar  
**License:** MIT

### Overview
A lightweight, Python-based web security scanner built with the help of **AI and prompt engineering** to support **basic reconnaissance and initial security assessment** of web applications.

This project focuses on understanding how reconnaissance workflows operate and how scan results should be interpreted manually.

### What it does
- 🔍 IP and domain discovery  
- 🌐 Basic network scanning (Nmap)  
- 🔒 Security headers analysis  
- 📁 Directory discovery  
- 🖥️ Server and technology fingerprinting  

### Purpose
This is a **learning project** designed to:  
- Practice web reconnaissance fundamentals  
- Explore common security misconfigurations  
- Improve interaction with AI models to design and refine security tooling  

### Requirements
- Python 3.x  
- nmap  
- curl  
- dig  

**Linux / Ubuntu**
```bash
sudo apt install nmap curl dnsutils
````

**macOS**

```bash
brew install nmap curl bind
```

### Installation

```bash
git clone https://github.com/Itsmeammar/web-recon-scanner.git
cd web-recon-scanner
chmod +x Scanner.py
```

### Usage

```bash
./Scanner.py example.com
```

Scan results are saved in the `scan_results/` directory.

### Disclaimer

⚠️ This tool is intended for **educational purposes only**.
Use it **only on systems you own or are authorized to assess**.
The author is not responsible for misuse.
