# Phishing Email Analysis Report

## What is Phishing?

**Phishing** is a type of cyber attack where attackers try to trick people into giving away sensitive information like passwords, credit card numbers, or personal details. They usually do this by pretending to be a trusted source via email, messages, or fake websites.

## Common Types of Phishing

1. **Email Phishing**  
   Attackers send fake emails that look like they come from real companies, asking you to click links or provide information.

2. **Spear Phishing**  
   Targeted phishing aimed at a specific person or organization, often using personal information to seem more convincing.

3. **Whaling**  
   A type of spear phishing that targets high-profile individuals like CEOs or executives.

4. **Smishing**  
   Phishing done via SMS (text messages).

5. **Vishing**  
   Voice phishing done over phone calls.

---

## analyze my findings
- by analyzing headers of the email arc-authentication-results spf=none; dmarc=none; dkim=none; arc=none 
🚨 Red Flag:

    SPF, DKIM, and DMARC are email authentication protocols.

    When all three are missing (none), it's a big sign that the sender's domain could be spoofed.

    Legitimate mail servers should usually pass at least one of these.

- **screenshot added to proof**



## Phishing indicator found
- **extracted url from the email** `https://35000usdperwwekpodf.blogspot.sg?p=9swghttps://35000usdperwwekpodf.blogspot.co.il?o=0hnd` its suspicious url confirm with `virustotal`.
- **Sender Address:** The email appears from `Mail Delivery System <Mailer-Daemon@se7-syd.hostedmail.net.au>` .  
- **Email Headers:** SPF and DKIM checks failed, showing the email was not authorized by the claimed sender.  
- **Suspicious Links:** The displayed URLs do not match the actual link targets, which lead to a malicious website.  
- **Urgent Language:** Good earnings from $6500 per day.  


---

## Conclusion

Based on these findings, the email is highly likely a phishing attempt designed to steal user credentials or distribute malware. Recipients should avoid interacting with the links or attachments.
