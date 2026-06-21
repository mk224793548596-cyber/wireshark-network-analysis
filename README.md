🦈 Wireshark Complete Commands (Kali Linux)

🔹 1. System Update (always first)

sudo apt update && sudo apt upgrade -y


---

🔹 2. Wireshark Install

sudo apt install wireshark -y


---

🔹 3. Check Wireshark Version

wireshark --version


---

🔹 4. Start Wireshark (GUI)

sudo wireshark


---

🔹 5. TShark (CLI Wireshark tool)

sudo apt install tshark -y

Capture packets (terminal)

sudo tshark -i eth0


---

🔹 6. Find Network Interface

ip a

OR

ifconfig


---

🔹 7. Save Packet Capture (.pcapng)

Wireshark GUI me:

File → Save As → filename.pcapng


---

🔹 8. Generate Traffic (Testing)

Ping traffic

ping google.com

Nmap scan traffic

nmap -sS 192.168.1.1


---

🔹 9. Filters Practice (MOST IMPORTANT)

ICMP (ping)

icmp

DNS traffic

dns

TCP traffic

tcp

Specific IP

ip.addr == 192.168.1.1


