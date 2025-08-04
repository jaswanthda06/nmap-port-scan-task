# Port Scanning Task - Cyber Security Internship

## Objective:
Scanned my local network to identify active devices and their open ports using Zenmap (Nmap GUI).

## Tools:
- Zenmap
- Windows Command Prompt (for IP check)
- GitHub

## What I Did:
1. Found my IP range using `ipconfig` (got 192.168.56.X)
2. Opened Zenmap and scanned the range `192.168.56.1/24`
3. Selected "Intense Scan" profile
4. Waited for the scan to complete
5. Saved the results as a `.txt` file
6. Took a screenshot of the result
7. Uploaded everything here

## Summary:
One active host found at 192.168.56.1  
Open ports:
- 135 (MSRPC)
- 139 (NetBIOS)
- 445 (SMB)

These are commonly used for Windows services. If left unprotected, they can be misused in a network attack.

## Files Included:
- `scan_results.txt` - Text output from the scan
- `nmap_screenshot.png` - Screenshot from Zenmap
- `README.md` - This file

## Conclusion:
This task helped me understand how port scanning works and how to detect exposed services on a network.
