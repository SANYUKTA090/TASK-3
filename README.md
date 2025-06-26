TASK-3 Basic Vulnerability Scan Using Nessus Essentials

1) Task Overview: basic vulnerability scan** on a personal computer using a free tool such as Nessus Essentials. The goal was to identify common vulnerabilities, understand their severity, and explore potential remediations.

2) Objective
Use Nessus Essentials to:
- Identify vulnerabilities in the local system.
- Understand the risk level using CVSS.
- Document the most critical findings.
- Learn the basics of vulnerability assessment and remediation.

3) Tools Used
Nessus Essentials by Tenable  
(Free vulnerability scanner: [https://www.tenable.com/products/nessus/nessus-essentials](https://www.tenable.com/products/nessus/nessus-essentials))
- Windows 11 (Host system)

4) Steps Performed
1. Installed Nessus Essentials and completed plugin compilation.
2. Configured scan with target IP range: `192.168.0.1 - 192.168.0.254`.
3. Discovered hosts on the local network.
4. Selected 5 active hosts for scanning.
5. Ran a basic network vulnerability scan on the detected hosts.
6. Analyzed results,focusing on critical and high vulnerabilities.
7. Captured screenshots at key stages of the scanning process.

5) Screenshots

-  Host Discovery (5 IPs detected)
-  Scan Summary with vulnerabilities per host
-  High and Critical vulnerabilities shown on dashboard
![Screenshot 2025-06-26 182522](https://github.com/user-attachments/assets/05219283-17df-423e-9167-8e8e5066143a)
![Screenshot 2025-06-26 182624](https://github.com/user-attachments/assets/d4266bd6-6414-43f1-8514-3a3c11c8348e)
![Screenshot 2025-06-26 185521](https://github.com/user-attachments/assets/ca4734fe-24ad-4248-9ae6-5e8b8d429c9a)


6) Key Findings

| Host IP        | Critical | High | Medium | Low | Info |
|----------------|----------|------|--------|-----|------|
| 192.168.0.107  | 6        | 0    | 0      | 0   | 103  |
| 192.168.0.1    | 2        | 2    | 0      | 0   | 19   |
| Others         | 0        | 0    | 1–4    | 0   | 3–4  |

7) Key Concepts Learned

- Vulnerability Scanning vs. Penetration Testing
- CVSS (Common Vulnerability Scoring System)
- False Positives
- Vulnerability Prioritization
- Remediation Suggestions (e.g., software updates, disabling vulnerable services)


