# Phishing_cybersecurity_class

# What phishing is (short)

Phishing is social-engineering: an attacker tries to trick people into revealing sensitive info (passwords, payment details, 2FA codes) or into executing actions (clicking a malicious link, opening an attachment) by pretending to be a trusted source.


---

# Typical attacker workflow (high level)

1. Reconnaissance – gather publicly available info about targets (names, job titles, contacts, company structure).


2. Crafting the lure – create a believable story (payment request, account alert, invoice, package delivery, HR memo). The lure will reference something plausible to the target.


3. Delivery – send the lure via email, SMS (SMiShing), voice calls (vishing), social media DM, or malicious websites.


4. Exploitation – the target follows the prompt: clicks a link, enters credentials on a fake page, or opens a malicious attachment.


5. Harvesting & escalation – attacker uses captured credentials or access to move laterally, escalate privileges, or monetize (sell credentials, wire money, extort).


6. Covering tracks – attacker deletes traces, forwards access to other fraudsters, or uses the access for long-term spying.




---

# Common phishing varieties (what to watch for)

Spear phishing — targeted messages tailored to a person or role (higher success rate).

Whaling — targeted at senior executives with pretended urgent business requests.

Credential harvesting — fake login pages that capture usernames/passwords.

Business Email Compromise (BEC) — impersonation of suppliers/partners/CEOs to request fund transfers.

Clone phishing — a copy of a legitimate message modified to include malicious links/attachments.

SMiShing and vishing — SMS or phone-based social engineering.

Malicious attachments — documents that ask you to enable macros or run scripts that lead to malware.



---

# Signs an email/message may be phishing

Sender address is similar but slightly altered (but display name looks normal).

Generic greetings instead of your name.

Urgent language demanding immediate action or secrecy.

Unexpected attachments or requests to enable macros.

Links that look right but the actual destination (hover to inspect) is different.

Requests for credentials, payment, or sensitive data via email.

Poor grammar/odd phrasing for supposedly professional senders.



---

# How to protect yourself and your organization

User-focused

Never enter credentials from an email link. Instead, open the service in a new tab or use a bookmark.

Enable multi-factor authentication (MFA) everywhere possible.

Don’t enable macros in documents from unknown senders.

Verify urgent requests through a separate channel (call the person on a known number).

Report suspicious messages to your IT/security team.


# Technical controls

Enforce MFA and strong password hygiene.

Deploy email authentication: SPF, DKIM, DMARC to reduce spoofing.

Use enterprise email filtering / anti-phishing solutions with URL rewriting and sandboxing for attachments.

Browser/endpoint protection: block known malicious domains, use up-to-date browsers and antivirus, and apply least-privilege for users.

Monitor for credential dumps and unusual login behavior (geographic anomalies, impossible travel).

Implement Data Loss Prevention (DLP) policies where appropriate.


# Organizational practices

Regular security awareness training with phishing simulation (ethically run by your security team or a vendor).

Clear incident response plan: how employees report suspected phishing, and how IT responds.

Restrict privileged access and use conditional access policies (e.g., require MFA from untrusted networks).

Keep software and OS patched.



---

# If you suspect you were phished

1. Change your password immediately (from a known-good device) and revoke sessions/tokens.


2. Enable or confirm MFA.


3. Notify your security/IT team and follow incident response steps.


4. If payment/identity fraud occurred, report to the bank and appropriate local authorities.


5. Scan your device for malware and consider a forensic review if sensitive systems were accessed.




---

## Legal & ethical note

Phishing is illegal and harmful. If you want to learn more technically, pursue defensive training: certified courses (e.g., CompTIA Security+, Certified Ethical Hacker, SANS), phishing simulation platforms used by security teams, or hands-on labs that focus on detection and mitigation.

----
# Aurthur
Abdulmuheez Qazeem 
@cyb3rflex
