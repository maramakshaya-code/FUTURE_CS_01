# vulnerability-assessment-report
## Target: scanme.nmap.org
## Date: 20-May-2026
## Tools Used
- Nmap 7.98
- OWASP ZAP 2.17.0

## Findings Summary
| Risk  | Count |
|------ |-------|
| Medium| 5     |
| Low   | 3     |
| Info  | 2     |

## Key Vulnerabilities
1. CSP Header Not Set
2. Directory Browsing
3. HTTP Only Site
4. Missing Anti-clickjacking Header
5. Server Version Leak

## Remediation
- Enable HTTPS/SSL
- Add security headers
- Hide server version info
- Disable directory browsing
