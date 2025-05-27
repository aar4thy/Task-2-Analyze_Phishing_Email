 Task-2-Analyze_Phishing_Email

What is phishing?
Phishing is a cyberattack where attackers impersonate a trusted entity to trick individuals into sharing sensitive information (like login credentials or financial details) or clicking malicious links, often through deceptive emails, texts, or websites.

Objective:Identify phishing characteristics in a suspicious email sample.

Tools Used:Email Client (Gmail),Free Online Email Header Analyzer(MXToolbox)

 Sample Phishing Email Overview:
The email appears to be a Google Drive notification claiming that "goog__@protected-download.com" has shared a PDF document titled "CLICK HERE." It was sent at 3:06 PM IST on May 27, 2025, and includes a link to open the document.
(Screenshot of sample email is uploaded)

Phishing Indicators Found:

1.Sender’s Email Address (Spoofing):
The sender’s email address, "goog__@protected-download.com," is suspicious. Legitimate Google Drive notifications typically come from domains like "@google.com" or "@docs.google.com." The domain "protected-download.com" is not associated with Google and indicates potential spoofing.
2.Email Header Discrepancies:
While the email headers are not visible in the screenshot, the sender’s domain alone suggests spoofing. Using a free online header analyzer (e.g., MXToolbox) would likely reveal inconsistencies, such as the email originating from a non-Google server or a "Return-Path" that doesn’t match the sender’s address.
3.Suspicious Links or Attachments:
The email contains a link labeled "CLICK HERE" to access a PDF. The link’s destination is not visible in the screenshot, but the domain "protected-download.com" in the sender’s email suggests it may lead to a fraudulent site. Legitimate Google Drive links typically include "drive.google.com" in the URL. Hovering over the link (if possible) would likely reveal a mismatched URL.
4.Spelling or Grammar Errors:
The email appears grammatically correct, but the sender’s name "goog__" with underscores is unusual and not consistent with official Google communications, which typically use a full name or a standard "Google Drive" sender label.
5.Mismatched URLs:
Although the actual URL isn’t visible, the sender’s domain ("protected-download.com") strongly suggests the link does not lead to a legitimate Google Drive page. This mismatch between the expected Google Drive domain and the actual destination is a key phishing indicator.



