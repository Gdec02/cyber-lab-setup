# Lab Setup Notes

## Network Adapter Settings (VirtualBox)
- Adapter 1: Host-Only Adapter (vboxnet0)
- Adapter Type: Intel PRO/1000 MT Desktop
- Promiscuous Mode: Allow All
- Cable Connected: ✅

## IP Addresses
- Kali Linux: 192.168.56.101
- Metasploitable: 192.168.56.102

## Ping Test
- Kali successfully pinged Metasploitable using:
  `ping 192.168.56.102`

## Commands Used
- `ip a` on Kali
- `ifconfig` on Metasploitable
- `ping` from Kali
