# 🛡️ My Cybersecurity Home Lab (Beginner Friendly)

Welcome to my first ever Cybersecurity Home Lab!  
This lab is designed for beginners like me to learn ethical hacking, penetration testing, and cybersecurity in a safe offline environment.

---

## 🚀 What This Lab Includes

- Kali Linux (Attacker Machine)
- Metasploitable 2 (Vulnerable Linux Target)
- OWASP Juice Shop / DVWA (Web Vulnerability Practice)
- Ubuntu/Windows VMs (Optional real-world simulation)
- Secure Host-Only networking
- Tools like Nmap, SQLMap, Hydra, Burp Suite, and Metasploit

---

## 🛠️ Tools & Requirements

| Tool/Hardware      | Description                                  |
|--------------------|----------------------------------------------|
| VirtualBox         | Free virtualization software                 |
| Kali Linux         | Penetration testing OS (attacker)            |
| Metasploitable 2   | Vulnerable target machine                    |
| OWASP Juice Shop   | Deliberately insecure web app                |
| RAM                | Minimum 8 GB (16 GB recommended)             |
| Disk Space         | 100+ GB free storage                         |

---

## 🧱 Step-by-Step Setup

### 1️⃣ Install VirtualBox
Download from: [https://www.virtualbox.org](https://www.virtualbox.org)  
Install and also add the VirtualBox Extension Pack.

### 2️⃣ Download and Import Kali Linux VM
- Visit: [https://www.kali.org/get-kali/](https://www.kali.org/get-kali/)
- Choose **Kali Linux VirtualBox Image**
- Import in VirtualBox:  
  File > Import Appliance > Select `.ova` file

### 3️⃣ Download and Import Metasploitable 2
- Download from: [https://sourceforge.net/projects/metasploitable/](https://sourceforge.net/projects/metasploitable/)
- Import into VirtualBox

### 4️⃣ Set Network Type (Important)
- Go to **VM Settings > Network**
- Set both Kali and Metasploitable to:
  `Host-Only Adapter` or `Internal Network`
- Boot both VMs and test connectivity using `ping`

---

## 🔍 Tools to Practice

| Tool        | Use Case                             |
|-------------|--------------------------------------|
| `nmap`      | Network scanning and enumeration     |
| `sqlmap`    | SQL Injection exploitation           |
| `hydra`     | Brute-force attacks (SSH, FTP, etc.) |
| `metasploit`| Exploitation framework               |
| `burpsuite` | Web app security testing             |
| `john`      | Password cracking                    |

---

## 🧠 My Learning Roadmap

| Week | Focus                                  | Topics/Tools                        |
|------|----------------------------------------|-------------------------------------|
| 1    | Lab Setup + Linux Basics               | Kali + Metasploitable, ping, nmap   |
| 2    | Web Vulnerabilities                    | DVWA, OWASP Juice Shop, sqlmap      |
| 3    | Exploitation & Password Attacks        | Metasploit, Hydra, John             |
| 4    | Real Labs & CTFs                       | TryHackMe beginner rooms            |

---

## 📚 Learning Platforms

- [TryHackMe](https://tryhackme.com) – Beginner-friendly hands-on labs
- [Hack The Box](https://hackthebox.com) – Realistic hacking simulations
- YouTube Channels:
  - [NetworkChuck](https://www.youtube.com/c/NetworkChuck)
  - [TheCyberMentor](https://www.youtube.com/@thecybermentor)

---

## 📸 Screenshots

> See the `screenshots/` folder for images of my setup and tools in action.

---

## 🗂️ Notes & Logs

I’m documenting everything I learn in the `notes/` folder:  
- Commands I used  
- Errors I encountered  
- What I learned from each tool

---

## 🔒 Safety Note

⚠️ This lab is for educational purposes only.  
All vulnerable machines are run locally and isolated from the internet.  
Never test tools on systems you don't own or have permission to test.

---

## 📜 License

MIT License – feel free to fork, clone, or build your own version!

---

