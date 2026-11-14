# Windows 7 VAPT Lab Report

An educational vulnerability assessment of my own Windows 7 virtual machine.
Only my own lab VM was tested. No third-party systems were involved.

## What I did
- Port and service scan with Nmap
- SMB checks with NetExec and enum4linux-ng
- MS17-010 and BlueKeep checks with Metasploit scanner modules (detection only)
- Public exploit lookup with searchsploit
- Missing patch analysis with WES-NG

## Result
11 findings: 2 Critical, 3 High, 2 Medium, 2 Low, 2 Informational.
Highest risk: MS17-010 (EternalBlue) and 180 missing security patches.

## Report
See VAPT_Report_Win7.pdf

## Notes
No exploitation was performed. OpenVAS was not completed. BlueKeep could not be tested because port 3389 was filtered.

## Author
Muhammad Arif Phulpoto, Cyber Security student
