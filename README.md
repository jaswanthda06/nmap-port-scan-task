# nmap-port-scan-task
Cybersecurity internship task for port scanning.

# 🔍 Cyber Security Internship Task 1 - Port Scanning

##  Objective
Perform a port scan on the local network to identify open ports and understand basic network exposure using Nmap.

---

##  Tools Used
- Zenmap (Nmap GUI)
- Windows 10
- GitHub

---

## Steps Followed
1. Identified local network IP range using `ipconfig`
2. Opened Zenmap and scanned target: `192.168.56.1/24`
3. Selected "Intense Scan" profile
4. Waited for scan to complete
5. Saved scan result as `scan_results.txt`
6. Uploaded result + screenshot to GitHub

---

##  Scan Summary
- Active Host: 192.168.56.1
- Open Ports:
  - 135/tcp – msrpc
  - 139/tcp – netbios-ssn
  - 445/tcp – microsoft-ds

---

##  Security Insights
- These ports are related to Windows file sharing (SMB)
- If not secured, they can expose system to attacks (like WannaCry)
- Firewalls and port blocking help reduce risk

---

##  Files in this Repo
- `scan_results.txt` → Actual Nmap scan output
- `nmap_screenshot.png` → Screenshot from Zenmap (optional)

---

##  Task Outcome
✔ Understood basic port scanning  
✔ Learned about open port risks  
✔ Successfully completed and submitted the task
