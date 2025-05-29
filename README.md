# Task 3: Basic Vulnerability Scan – Cyber Security Internship

## Objective
Use Nessus Essentials to perform a vulnerability scan on my local machine.

## Tool Used
- Nessus Essentials (free community version)

## Target
- Localhost (127.0.0.1)

## Steps Performed
1. Installed Nessus and activated with a free license.
2. Set up a basic scan targeting my machine.
3. Allowed the scan to run (~45 minutes).
4. Reviewed the report and documented critical vulnerabilities.
5. Took screenshots of the dashboard and results.

## Sample Vulnerabilities Found
| Vulnerability                  | CVSS Score | Mitigation                              |
|-------------------------------|------------|------------------------------------------|
| SSL Certificate Expired       | 7.5        | Renew/Replace Certificate                |
| SMBv1 Protocol Enabled        | 8.1        | Disable SMBv1                            |
| Weak Password Policy          | 6.5        | Enforce strong password requirements     |

## Outcome
This task gave me hands-on experience in basic vulnerability scanning, risk analysis, and using CVSS scores to assess threats.

## Report
See `report.pdf` for the complete scan result.
