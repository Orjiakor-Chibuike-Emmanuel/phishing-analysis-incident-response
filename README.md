# Phishing Email Analysis & Incident Response

**Project Overview**  
Conducted a full SOC-style investigation on a sophisticated phishing email impersonating the Microsoft Security Team.

**Tools Used**
- VirusTotal
- MXToolbox (DMARC/SPF check)
- WHOIS Lookup
- urlscan.io & TinyURL Preview

**Key Findings**
- Sender domain `libreriacies.es` belongs to a legitimate Spanish bookstore (compromised)
- No DMARC record found → enabled email spoofing
- Shortened URL (`tinyurl.com/ypu5kfts`) was terminated by TinyURL for abuse and flagged as malicious by 5 security vendors

**Skills Demonstrated**
- IOC extraction
- Domain reputation analysis
- Safe URL investigation
- Social engineering recognition

**Conclusion**: Confirmed phishing attempt with clear indicators of impersonation and credential harvesting intent.
