# Phishing-email-analyzer
**Analyze a Phishing Email Sample**
### Phishing Email Analysis Report

**1. Sender Email:** banco.bradesco@atendimento.com.br (Spoofed domain)

**2. Header Analysis:**
- SPF: Fail
- DKIM: Missing
- IP from unknown country

## Phishing Indicators Found:
1. **Sender's Email**: Fake domain used.
2. **Header Analysis**: Discrepancy in return path and received domains.
  - SPF: Fail
  - DKIM: Missing
  - IP from other country(US)
3. **Suspicious Links**: Link leads to unrelated IP address.
4. **Language**: Email uses fear tactics
5. **Mismatched URLs**: Displayed vs actual URLs don't match.
    - Extracted Emails: https://blog1seguimentmydomaine2bra.me/
    - Extracted Domains: blog1seguimentmydomaine2bra.me
6. **Grammar Issues**: Several typos in the message.

## Tools Used
- MxToolbox Email Header Analyzer
- EML Analyzer
- VirusTotal
- Google Admin Toolbox
- Manual inspection in browser

## Conclusion
The email shows clear signs of phishing using spoofed sender identity, suspicious links, urgent tone, and poor grammar.

