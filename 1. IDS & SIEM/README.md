# SOC SIEM Monitoring Attacks

<h1>SIEM - Monitoring Live Attacks From the Web</h1>

<h2>Description</h2>
In this project we start with nothing and set up a basic home SOC in Azure. I utilize a free Azure subscription to create a virtual machine (VM), set it up as a honeypot open and accessible to the internet, and forward logs to a central repository. I then integrate Microsoft Sentinel to analyze real-world attack data.

This project covers:
- Creating an Azure subscription and setting up a VM
- Configuring Log Analytics Workspace
- Forwarding logs and integrating with Sentinel
- Querying failed login attempts and visualizing attack sources
- Building an attack map to track real-time hacker activity

This project was a great learning experience for me as a cybersecurity beginner looking to practice log analysis, threat detection, and SOC operations in a real-world cloud environment.
<br />

<h2>Languages and Utilities Used</h2>

- <b>KQL</b> 
- <b>Log Analytics Workspace</b>
- <b>Microsoft Sentinel</b>

<h2>Environments Used </h2>

- <b>Microsoft Azure</b> 

<h2>Program walk-through:</h2>

<p align="center">
Create Resource Group in Microsoft Azure <br/>
<img src="https://github.com/Tony-72/Cybersecurity-Portfolio/blob/main/1.%20IDS%20&%20SIEM/Images/Create%20Resource%20Group.png?raw=true" alt="Create Virtual Machine" width="80%" height="80%">
<br />
<br />
Create Virtual Network: <br/>
<img src="https://github.com/Tony-72/Cybersecurity-Portfolio/blob/main/1.%20IDS%20&%20SIEM/Images/Create%20Virtual%20Network.png?raw=true" alt="Create Virtual Machine" width="80%" height="80%">
<br />
<br />
Create Virtual Machine <br/>
<img src="https://github.com/Tony-72/Cybersecurity-Portfolio/blob/main/1.%20IDS%20&%20SIEM/Images/Create%20Virtual%20Machine.png?raw=true" alt="Create Virtual Machine" width="80%" height="80%">
<br />
<br />
<img src="https://github.com/Tony-72/Cybersecurity-Portfolio/blob/main/1.%20IDS%20&%20SIEM/Images/Create%20Virtual%20Machine2.png?raw=true" alt="Create Virtual Machine" width="80%" height="80%">
<br />
<br />
Review Resource Group to verify all resources available <br/>
<img src="https://github.com/Tony-72/Cybersecurity-Portfolio/blob/main/1.%20IDS%20&%20SIEM/Images/Review%20Resource%20Group.png?raw=true" alt="Create Virtual Machine" width="80%" height="80%">
<br />
<br />
Log into VM <br/>
<img src="https://github.com/Tony-72/Cybersecurity-Portfolio/blob/main/1.%20IDS%20&%20SIEM/Images/Log%20into%20Windows%20VM..png?raw=true" alt="Create Virtual Machine" width="80%" height="80%">
<br />
<img src="https://github.com/Tony-72/Cybersecurity-Portfolio/blob/main/1.%20IDS%20&%20SIEM/Images/Log%20into%20Windows%20VM2..png?raw=true" alt="Create Virtual Machine" width="80%" height="80%">
<br />
<br />
Open Event Viewer to analyse Windows security logs <br/>
<img src="https://github.com/Tony-72/Cybersecurity-Portfolio/blob/main/1.%20IDS%20&%20SIEM/Images/Event%20viewer.png?raw=true" alt="Create Virtual Machine" width="80%" height="80%">
<br />
<img src="https://github.com/Tony-72/Cybersecurity-Portfolio/blob/main/1.%20IDS%20&%20SIEM/Images/Event%20viewer2..png?raw=true" alt="Create Virtual Machine" width="80%" height="80%">
<br />
