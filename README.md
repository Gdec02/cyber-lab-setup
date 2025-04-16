# Cybersecurity Home Lab Setup

This project documents my virtual lab environment using Kali Linux and Metasploitable 2 in VirtualBox. The lab allows me to safely practice ethical hacking, run network scans, and analyze system logs — all in an isolated environment.

## 🖥️ Virtual Machines Used

| VM             | OS                | Purpose             |
|----------------|-------------------|---------------------|
| Kali Linux     | Debian-based      | Attacker / Analyst  |
| Metasploitable | Ubuntu (vulnerable)| Target VM           |

## 🛠️ Network Configuration

- **VirtualBox Host-Only Adapter**: `vboxnet0`
- **Kali IP**: `192.168.56.101`
- **Metasploitable IP**: `192.168.56.102`
- Adapter type: Intel PRO/1000 MT Desktop
- Promiscuous Mode: Allow All

## 📸 Screenshots

### 🔹 Kali IP Address
![Kali IP](screenshots/kali_ip.png)

### 🔹 Metasploitable IP Address
![Metasploitable IP](screenshots/metasploitable_ip.png)

### 🔹 Ping Test
![Ping Test](screenshots/ping_test.png)


## 📝 Notes
See `notes.md` for interface details and setup steps.
