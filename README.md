# Phishing Email Analysis

## Objective
This project analyzes a sample phishing email to identify common phishing characteristics and improve awareness of email-based threats.

## Tools Used
- Email client thunderbird (for reading the email)
- Free online email header analyzer (e.g., [Google Toolbox Email Header Analyzer](https://toolbox.googleapps.com/apps/emailheaders/))
- Terminal commands for Git and GitHub interaction

## Contents
- `PHISHING_REPORT.md`: Detailed analysis of the phishing email, highlighting suspicious indicators found.
- `sample/`: Folder containing the raw phishing email sample files (e.g., `.eml` or `.txt`).
- `README.md`: This overview document.

## How to Use
- Review the `PHISHING_REPORT.md` file for a step-by-step analysis of the phishing email.
- The `sample/` folder contains the original email files used for analysis.
- Use this repository as a reference to understand typical phishing tactics and red flags.

## Summary of Findings
The phishing email sample showed multiple suspicious traits including:
- Spoofed sender email address
- Discrepancies in email headers (SPF/DKIM/DMARC failures)
- Mismatched URLs where link text differs from the actual target URL
- Use of urgent and threatening language to prompt quick action
- Spelling and grammar errors indicative of phishing attempts

## References
- [Phishing email sample blue team labs](https://blueteamlabs.online/home/challenge/phishing-analysis-f92ef500ce)
