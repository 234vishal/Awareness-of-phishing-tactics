# Phishing Email Analysis
This repository shows an example of a phishing email, explains why it is suspicious, and gives a short overview of phishing types.

## What is Phishing?
Phishing is when attackers trick people by pretending to be a trusted company or person. Their goal is to steal passwords, money, or personal information.

## Types of Phishing
* **Email Phishing** – Mass fake emails pretending to be from trusted companies to steal login details or money.

* **Spear Phishing** – Targeted phishing using personal/company details to trick specific people.

* **Whaling** – Phishing aimed at executives or high-value targets with fake urgent business requests.

* **Clone Phishing** – A real email is copied and resent with malicious links or attachments.

* **Smishing** – Phishing through SMS messages with fake links or phone numbers.

* **Vishing** – Phone call scams where attackers pose as support or banks to steal info.

* **Business Email Compromise (BEC)** – Hackers spoof or hijack company emails to trick employees into payments or data leaks.

* **Pharming** – Redirecting users to fake websites even when the correct URL is typed.

* **Angler Phishing** – Fake social media support accounts trick users with phishing links.

## Phishing Email Sample
**Screenshoot :** The provided screenshot is a phishing email sample pretending to be a "Windows Error Report" from Microsoft Team.
<img width="860" height="640" alt="pishing mail" src="https://github.com/user-attachments/assets/36961fd6-9cae-4284-92fa-7bea6be7504e" />

## Suspicious points:

### 1. Examine sender’s email address for spoofing

* Sender shown: Microsoft Team <no-reply.msteam2@outlook.com>

* Legitimate Microsoft alerts usually come from official domains like @microsoft.com, not from a free Outlook.com address.

* This is a red flag for spoofing.

### 2. Check email headers for discrepancies

* The full headers are not visible in the screenshot, but typically:

* The “From” domain does not align with Microsoft’s real domains.

* An email header analyzer would likely show inconsistencies in Sender Policy Framework **(SPF)**/DomainKeys Identified Mail **(DKIM)**/Domain-based Message Authentication, Reporting & Conformance **(DMARC)** authentication.

### 3. Identify suspicious links or attachments

* The email contains a button: "Review recent activity".

* It also includes a phone number (1-800-816-0380) and a link to https://www.microsoft.com/ (possibly mismatched when hovered).

* Clicking the button is likely to lead to a phishing site requesting credentials.

### 4. Look for urgent or threatening language

* Phrases used:

  * “We detected something unusual…”

  * “suspicious login attempt…”

  * “someone from foreign IP Address was trying…”

  * “malicious user might trying to access your network”

  * “mandatory email service announcement…”

*  This urgency and fear tactic is a common phishing method to make users act quickly.

### 5. Note any mismatched URLs

* The email shows https://www.microsoft.com/, but in phishing cases, hovering usually reveals a different malicious URL.

* The mismatch between displayed and actual links is a strong phishing sign .

### 6. Verify presence of spelling or grammar errors

* Errors spotted:

  * “malicious user might trying to access” (should be “might be trying”).

  * “an unknown source… someone from foreign IP Address was trying” (awkward phrasing).

  * “corrupt your windows license key” (not a realistic technical phrase from Microsoft).

* Poor grammar indicates non-professional source.

### 7. Summarize phishing traits found in the email

* **Suspicious sender address:** Free Outlook domain, not official Microsoft.

* **Urgency & scare tactics:** Claims of foreign login attempt and threat to license key.

* **Suspicious link/button:** “Review recent activity” likely leads to phishing site.

* **Fake phone support number:** Trick users into calling scammers.

* **Grammar errors:** Multiple awkward phrases.

* **Brand impersonation:** Pretends to be Microsoft to build trust.

* **Unusual details:** Invalid IP address format (293.09.101.9 is not valid).

### Safe Actions Against Phishing

* **Check the sender’s email address** – Look closely for spelling errors, extra characters, or free domains (e.g., microsoft-support@outlook.com instead of @microsoft.com).

* **Hover before you click** – Place your mouse over links to preview the real URL; don’t click if it looks suspicious.

* **Don’t download unknown attachments** – PDFs, Word docs, or ZIPs may contain malware.

* **Look for urgency or threats** – Be cautious if an email pressures you to act quickly (“Your account will be blocked in 24 hrs”).

* **Check spelling/grammar** – Many phishing emails have poor grammar or awkward language.

* **Verify with the source** – Contact the company/bank using official numbers or websites instead of replying or calling numbers in the email.

* **Report the phishing attempt** – Use your email provider’s “Report Phishing” button, or forward to your IT/security team.

* **Enable Multi-Factor Authentication (MFA)** – Even if credentials are stolen, MFA adds an extra lock.

* **Keep systems updated** – Ensure browsers, OS, and antivirus are up to date to block malicious links.

* **Trust your instincts** – If something feels “off” or too good to be true, pause and verify.
  
## Conclusion:
This email is a clear phishing attempt aimed at deceiving the recipient into clicking a malicious link or contacting a fake support number. It demonstrates classic phishing traits such as spoofed identity (using a free email domain instead of an official one), urgent and fear-inducing language, suspicious links, vishing elements, fake technical details, and noticeable grammar errors. Together, these indicators confirm that the email is fraudulent and should not be trusted.



