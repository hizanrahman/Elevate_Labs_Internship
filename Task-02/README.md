# Task 2: Analyze a Phishing Email Sample

## 🎯 Objective
Identify phishing characteristics in a suspicious email sample.

## 🛠 Tools Required
- Email client or saved email file (text format)
- Free online email header analyzer (e.g., [MXToolbox](https://mxtoolbox.com/EmailHeaders.aspx), [Google Admin Toolbox](https://toolbox.googleapps.com/apps/messageheader/))

## 📄 Deliverables
A detailed report listing all identified phishing indicators found in the email sample.

---


1. **Examine the Sender’s Email Address**  
    - The sender's email address is `banco.bradesco@atendimento.com.br` which is not heard as a common domain

3. **Check Email Headers**  
   - While analysing the header section, I have found **SPF & DKIM** Signatures are missing
     ![mxtool](https://github.com/hizanrahman/Elevate_Labs_Internship/blob/main/Task-02/mx.png)

4. **Identify Suspicious Links or Attachments**  
   Suspicious link: `https://blog1seguimentmydomaine2bra.me/`

  - I have checked in VirusTotal tool for malicious detection and found as no vendors have flagged as malicious.
    ![virustotal](https://github.com/hizanrahman/Elevate_Labs_Internship/blob/main/Task-02/virus.png)

**Summary**

- **Suspicious Sender Address**: The sender uses an unusual domain `banco.bradesco@atendimento.com.br`, which does not match the official domain of Bradesco Bank and raises authenticity concerns.

- **Missing Security Signatures**: The email header analysis revealed that **SPF** and **DKIM** signatures are missing, indicating potential spoofing or lack of sender validation.

- **Suspicious Link**: The email contains a suspicious hyperlink:  
  `https://blog1seguimentmydomaine2bra.me/`  
  Although VirusTotal shows **no vendors have flagged it**, the domain is highly suspicious and not aligned with legitimate banking URLs.

- **Overall Assessment**: The email demonstrates multiple phishing indicators, including domain spoofing, missing authentication headers, and a deceptive link. Despite no malware flag from VirusTotal, the email should be considered **phishing** based on the context and red flags.


    
