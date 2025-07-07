# Web Server Hardening with ModSecurity & Fail2Ban on Kali Linux

This project explains how I secured a Nginx web server on Kali Linux using:

- **ModSecurity** – A Web Application Firewall (WAF) to stop threats like SQL injection, XSS, LFI, and RCE.
- **Fail2Ban** – An intrusion prevention tool that bans IPs after suspicious activity (e.g., brute-force attacks).

##  Project Highlights

✅ Compiled and configured **ModSecurity v3** from source  
✅ Enabled **OWASP CRS rules** for full WAF protection  
✅ Configured **Fail2Ban** with custom jails and filters for SSH, bad bots, and HTTP errors  
✅ Successfully tested rules and IP banning actions  
✅ Clean documentation of every step

##  Full Setup Guide

You can find the full configuration with commands and step-by-step instructions here:

 [Modsecurity_and_Fail2Ban_Configuration.pdf](Modsecurity_and_Fail2Ban_Configuration.pdf)

##  What’s Next?

I'm now integrating this setup with **Wazuh SIEM** to simulate a real-world Security Operations Center:
- Monitor alerts in real-time
- Analyze attack patterns
- Correlate logs from ModSecurity, Fail2Ban, and NGINX

##  Feedback

Feel free to fork the project, open issues, or suggest improvements. This setup is ideal for students, security learners, and DevSecOps enthusiasts.

##  Requirements

- Kali Linux
- Nginx installed
- Git, Make, GCC
- iptables for banning

##  License

Open source. Free for educational use.
