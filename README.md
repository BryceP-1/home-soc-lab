# home-soc-lab
Personal Home Security Operations Center Lab Using VirutalBox

This project is a cybersecurity project on my homelab built in VirtualBox.

It will represent a small-scale Security Operations Center(SOC) where logs montiored
from a kali-linux endpoint are analyzed and collected using Wazuh & OpenSearch on Ubuntu.

Tools & Technology Used:
VirtualBox: Virtualization platform
Ubuntu: Host for my SIEM
Kali Linux: Attacker endpoint
Wazuh: SIEM for log collection and rule dectection
OpenSearch: Data visualization engine


Steps:
1. Created two VM's (Ubuntu, Kali)
2. Configured network connection between the two VM's
3. Installed Wazuh manager on Ubuntu
4. Installed Wazuh agent on Kali
5. Generated tests (Brute-force, Privilege escalation)
6. Verified dectections in Wazuh

What I learned:
- How to set up and manage SOC architecture
- How to use Wazuh to monitor and analyze endpoint events
- Gained understanding of SIEM and detection rules
- Gained basic knowledge on blue-team monitoring and red-team simulation

Images:
- Screenshot of my endpoint connected to my SIEM
  
  <img width="1920" height="598" alt="wazuh-active-endpoint" src="https://github.com/user-attachments/assets/a6b0f99e-68a6-4050-96bf-db42c33b2b47" />
- Screenshot of brute force attempts
  
  <img width="817" height="539" alt="fail-auth-kali-endpoint" src="https://github.com/user-attachments/assets/dc93703f-bca1-4fdc-accd-a5d0e28efee2" />

- Screenshot of brute force detection on SIEM
  
  <img width="1920" height="879" alt="fail-auth-wazuh" src="https://github.com/user-attachments/assets/d00e4099-effd-48a1-85ba-4a4804af0ce5" />

- Screenshot of Wazuh manager dashboard on Host PC
  
  <img width="1919" height="924" alt="wazuh-on-hostpc" src="https://github.com/user-attachments/assets/28db9251-8156-49ae-ad82-ec84c99dc2f9" />




