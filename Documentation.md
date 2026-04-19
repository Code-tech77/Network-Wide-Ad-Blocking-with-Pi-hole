# Network Wide Ad Blocking with Pi-hole 🍇 🐧

A practical homelab project where I built and deployed a **network-level ad blocker** using Pi-hole on a Raspberry Pi.  
This solution filters DNS requests to block ads, trackers, and unwanted domains across all devices connected to the network.

---

## 📌 Project Overview

I created this project to solve a real problem, intrusive and inappropriate ads across devices.  
Instead of relying on browser extensions or paid services, I implemented a **centralised DNS filtering system** that works at the network level.

This project demonstrates hands-on experience with **networking, Linux systems, and security fundamentals**.

---

## 🧠 Key Learning Outcomes

- Understanding how **DNS resolution** works in real environments  
- Configuring **network-wide traffic filtering**  
- Hands-on experience with **Linux-based systems (Raspberry Pi)**  
- Practical knowledge of **DHCP and device management**  
- Exposure to **routing data traffic across a network**  
- Introduction to **VPN concepts and encryption basics**  
- Developing strong **problem-solving and troubleshooting skills**

---

## 🛠️ Tech Stack

- Raspberry Pi Zero 2W  
- Pi-hole (DNS sinkhole)  
- Raspberry Pi OS (Linux)  
- Cloudflare DNS (1.1.1.1)  
- MicroSD Card (16GB+)  

---

## ⚙️ Architecture
<img width="639" height="425" alt="Screenshot 2026-04-19 at 11 16 06 pm" src="https://github.com/user-attachments/assets/967b596b-9de4-42a0-b42f-d8d067ab3f33" />
----

## ⚙️ Setup Process (High Level)

1. Flash Raspberry Pi OS onto a microSD card  
2. Boot Raspberry Pi and enable SSH access  
3. Install Pi-hole on the system  
4. Configure upstream DNS (Cloudflare)  
5. Access Pi-hole Admin Dashboard  
6. Configure router DHCP to route traffic via Pi-hole  
7. Test and verify ad blocking across devices  

---

## 🧩 Challenges & Problem Solving

One of the biggest challenges I faced was writing the OS image to the microSD card.

- Spent **3 days troubleshooting flashing issues**  
- Learned about **disk partitions and storage handling**  
- Implemented a workaround by:
  - Installing the image on an external USB drive  
  - Transferring it to the microSD card  

This experience strengthened my ability to **think outside the box and persist under pressure**.

---

## 📸 Results

- Successfully blocked ads across all connected devices  
- Improved browsing experience (no intrusive ads)  
- Centralised control via Pi-hole Admin Dashboard  

---

## 🔐 Security Considerations

- DNS filtering helps reduce exposure to **malicious domains**  
- Centralised control improves **network visibility**  
- Can be extended with:
  - VPN integration for remote protection  
  - Advanced firewall rules  
  - Logging and monitoring  

---

## 📈 Why This Project Matters

This project goes beyond ad blocking, it demonstrates:
- Real-world **network security concepts**
- Ability to **build and deploy systems**
- Strong **problem-solving mindset**

---

### 👨‍💻 Author
Mohammed Zuoriki
Cybersecurity Student | Aspiring Cloud Security Engineer | Self-Driven Technologist
<br> LinkedIn: https://www.linkedin.com/in/mohammed-zuoriki-856133250/

------

### ⭐ Contributing

Contributions, feedback, and ideas are welcome.
Feel free to fork the repository or open an issue.
