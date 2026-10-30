<img width="1358" height="648" alt="image" src="https://github.com/user-attachments/assets/f406d69d-d12e-499c-876b-bed0bf19bdc8" />Cybersecurity Lab Environment Setup – Week 1

Student: Ukatu Olisa Clinton  
Program: Networkwalks Cybersecurity Internship

Project Overview
This project focuses on setting up an isolated virtual cybersecurity and penetration-testing laboratory using VirtualBox and Kali Linux.

 Tools Used
- Oracle VirtualBox / Virtual machine 
- Kali Linux
- Windows 10/11 (optional target)

 Steps I Followed

1. Installed VirtualBox on my host machine
2. Downloaded Kali Linux ISO
3. Created a new Virtual Machine
4. Configured network (NAT / Host-Only)
5. Installed Guest Additions
6. Updated Kali Linux
7. Took a snapshot

 Screenshots

![Project Screenshot](https://github.com/user-attachments/assets/c9ec10e1-0d2f-4626-8e3d-4dd95a60efb8)
 Challenges Faced & Solutions
 
During the setup of my Kali Linux environment, I encountered a network connectivity issue where Kali Linux could not access the internet. I troubleshot the issue by checking the network adapter configuration, verifying the IP address using ip a, and restarting the network service. After correcting the adapter settings, internet connectivity was successfully restored.

 Result
Successfully created a working isolated lab environment ready for penetration testing practice.
