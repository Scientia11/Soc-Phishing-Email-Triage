# SOC Phishing Email Triage

**Junior SOC Analyst Portfolio**  
Hands-on phishing investigation labs

## About
I am building real-world SOC skills. This repository documents my phishing email triage work — the exact process used in SOC teams.

Every sample includes:
- Header analysis (SPF, DKIM, DMARC, Received lines etc)
- Content analysis (MIME headers, typos, urgency etc)
- URL/link analysis (redirects, domain squatting etc)
- Attachment analysis (file type, VirusTotal, sandbox etc)

## Skills Demonstrated
- Email header forensics & authentication checks
- Phishing detection using free tools
- IOC collection and verdict writing
- Structured incident response reporting
- Safe analysis without clicking malicious links/files

## Tools Used
- whois.domaintools.com
- mxtoolbox.com
- gchq.github.io/CyberChef/
- github.com/MalwareCube/Email-IOC-Extractor
- url2png.com
- urlscan.io
- virustotal.com
- hybrid-analysis.com
- Manual raw header inspection

## Phishing Samples Analyzed
| Sample | Type | Verdict | Link |
|--------|------|---------|------|
| Sample-01 | Bank Alert | Malicious (SPF fail + malicious URL) | [View Report](./Phishing-Samples/Sample-01/) |
| Sample-02 | Invoice Attachment | Suspicious (macro + double extension) | [View Report](./Phishing-Samples/Sample-02/) |
*(Add more rows as you complete samples)*

## How to View
1. Browse the `Phishing-Samples` folder
2. Each sample has screenshots + markdown reports
3. All analysis done safely in browser tools

## Future Additions
- SIEM log analysis
- Full incident response playbooks


**Connect with me**  
Open to junior SOC roles. Feel free to reach out!

Last updated: March 2026
