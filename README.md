# Task 2: Phishing Email Analysis

## Objective
Identify phishing characteristics in a suspicious email sample to understand potential security risks.

## Tools
- Email client (Gmail, Outlook, etc.) or saved email file (.eml/.txt)  
- Free online email header analyzer (e.g., [https://toolbox.googleapps.com/apps/messageheader/](https://toolbox.googleapps.com/apps/messageheader/))

## Sample Email

**Screenshot:**

<p align="center">
  <img src="https://github.com/Tanya0xCyber/Phishing_email_analysis_task-/blob/main/Screenshot/phishing_email.png" width="80%">
</p>


---

## Steps

### 1. Examine the Sender
- **Observation:** `human[.]resources@alerting-services[.]com` is suspicious.  
- **Reason:** Unusual domain, does not match official company email.  
 

### 2. Analyze Email Headers
- Copy the email headers.
- Use an online header analyzer to check:
  - Origin IP 
  - Mail server path 
  - SPF/DKIM/DMARC results 
- **Observation:** Discrepancies may indicate spoofing.  
- **Note:** Full email headers were not available for this sample.  
- (Header analysis could not be performed.)  
- Phishing assessment will focus on sender address, links, and content.  

### 3. Check Links and Attachments
- Hover over the link `[View Fraudulent Expense Details]` to see the actual URL.  
- **Observation:** URL does not match the company’s domain or is shortened/obfuscated.  


### 4. Look for Urgent or Threatening Language
- Phrases like “Failure to promptly address this matter” and “respond urgently” indicate social engineering.  


### 5. Identify Spelling and Grammar Errors
- Minor inconsistencies may be present; professional phishing emails often minimize errors.  


### 6. Summarize Phishing Traits
| Trait | Observation |
|-------|------------|
| Spoofed sender | Email address does not match official company domain |
| Header inconsistencies | Analyzed via header tool; shows unusual mail route |
| Suspicious link | Link points to unknown/malicious domain |
| Urgent language | Pressures recipient to act immediately |
| Spelling/grammar | Minor or none; still suspicious |

---

## Notes
- Always treat unknown emails with caution.
- Hover over links and analyze headers before interacting.( you can use virustotal)
- This analysis helps improve awareness and prevents falling victim to phishing attacks.
