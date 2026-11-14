# hawkode.github.io

Source for my portfolio: **https://hawkode.github.io**

Projects, labs, tools and guides across IAM, security and infrastructure, written up with the attack, detection and hardening behind each one.

## What's on the site

**Identity and access**
- [IAM Lab in Microsoft Entra ID](https://hawkode.github.io/projects/entra-iam-lab/): dynamic groups, joiner-mover-leaver, Conditional Access, PIM, access reviews and SSO, built from an empty tenant.
- [Entra IAM Automation](https://github.com/Hawkode/entra-iam-automation): PowerShell and Microsoft Graph for cloud and hybrid lifecycle, reporting and access reviews.
- [Two-site domain consolidation](https://hawkode.github.io/projects/windows-server-2022-domain-migration/): two office domains merged into one, with 60+ accounts matched to their Entra ID identities.

**Windows endpoint security series**
1. [Attack: Windows Privilege Escalation](https://hawkode.github.io/projects/windows-privilege-escalation/)
2. [Detect: Privilege Escalation in Splunk](https://hawkode.github.io/projects/splunk-privesc-detection/)
3. [Harden: Windows Health Monitor](https://hawkode.github.io/projects/windows-health-monitor/) ([repo](https://github.com/Hawkode/Windows-Health-Monitor))

**Tools:** [MailGuard](https://github.com/Hawkode/MailGuard) (phishing triage) and [PasswordAnalyzer](https://github.com/Hawkode/PasswordAnalyzer) (password auditing with Have I Been Pwned).

**Guides:** [15 practical write-ups](https://hawkode.github.io/guides/), from Entra Connect sync troubleshooting and Windows security event IDs to patch and vulnerability management.

## How it's built

Plain HTML and one shared stylesheet (`style.css`), served by GitHub Pages. No framework, no build step, no tracking.

Diagrams are inline SVG. Console output on project pages is sanitised: no real host names, IP addresses, user names or tenant details.

## Contact

[LinkedIn](https://www.linkedin.com/in/hawkode) · [GitHub](https://github.com/Hawkode)
