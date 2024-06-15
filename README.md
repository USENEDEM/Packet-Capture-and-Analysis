# Packet Capturing and analysis.
---
### Project Overview
---

This project is a live simulation which aims to showcase procedures in packet capturing and analysis using wireshark in a lab enviroment.

### Skills *( Learned )*
---
*Bullet Points*


1. Packet sniffing / Capturing.
2. Packet analysis.
3. Familiarization with wireshark.

### Tools
---

1. Kali linux - Debian based operating system for penetration testing / ethical hacking [Download here](https://www.kali.org)
2. Wireshark - Network packet analyser (comes pre-installed on kali linux).


### Procedures
---

1. Start up kali linux machine and click on the applications icon at the top left corner and search for wireshark as it comes pre-installed on *kali linux* or run the command

```zhs
sudo wireshark
```
on the linux terminal to start up wireshark


<img width="1280" alt="Screenshot 2024-05-24 at 12 43 39" src="https://github.com/USENEDEM/Packet-Capture-and-Analysis/assets/169564406/a2bcde33-0264-4c88-adf6-0877886ee907">


*Peview 1* (wireshark in the kali linux pre-installed application list)


<img width="1280" alt="Screenshot 2024-05-24 at 13 06 26" src="https://github.com/USENEDEM/Packet-Capture-and-Analysis/assets/169564406/a7c380aa-5789-4342-af79-745fd08461d9">


*Preview 2* (starting up wireshark using the kali linux terminal)

2. Wireshark's application interface gives options for selection of different network protocols including *source(src)* and *destination (dst) ip address* 


<img width="1280" alt="Screenshot 2024-05-24 at 12 45 17" src="https://github.com/USENEDEM/Packet-Capture-and-Analysis/assets/169564406/1342fac1-c15c-4beb-b39b-ab653c91c377">


*preview 3* (wireshark application interface)


I selected *eth0* as my capturing interface.


<img width="1280" alt="Screenshot 2024-05-24 at 12 47 50" src="https://github.com/USENEDEM/Packet-Capture-and-Analysis/assets/169564406/fcb94d3c-dbc9-4d3c-8ab0-778732afda30">


*preview 4* (selecting *etho*)


<img width="1280" alt="Screenshot 2024-05-24 at 12 49 47" src="https://github.com/USENEDEM/Packet-Capture-and-Analysis/assets/169564406/0d3eef20-1ba4-45bd-b3e5-64ace4da4031">


*Preview 5* (captured packet on *eth0*)



I narrowed down my packet analysis by setting the *ip. address* for more insights on packets transmitted.



<img width="1280" alt="Screenshot 2024-05-24 at 13 17 08" src="https://github.com/USENEDEM/Packet-Capture-and-Analysis/assets/169564406/bd310238-11b0-4871-b2cd-67fb133a93b0">



*preview 6* (selected *ip. address*)



I analysed packet capture from *src.ip<192.168.43.150>* to *dest. ip<157.240.252.10>* via *TCP Protocol* as shown *below* in *Preview 6*.This packet capture details including *no.*  of captured packet including time stamp, *source Ip* etc.



<img width="1280" alt="Screenshot 2024-05-24 at 12 52 37" src="https://github.com/USENEDEM/Packet-Capture-and-Analysis/assets/169564406/81b03f4c-adf1-4964-a269-3bd9d15e60a6">

*Preview 7* (analysis of packet from source *src* *ip* via *TCP* protocol).

