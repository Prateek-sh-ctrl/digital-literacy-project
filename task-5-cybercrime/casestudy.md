# Case Study: Ransomware Attack – WannaCry (2017)

## What is Ransomware?
Ransomware is a type of malicious software that encrypts a victim's files or
locks them out of their system, then demands a ransom payment — usually in
cryptocurrency — in exchange for restoring access. It combines elements of
cryptography, social engineering, and network exploitation to cause maximum
disruption.

## How It Typically Happens (Step-by-Step)

1. **Initial Access** — The attacker delivers the ransomware through a phishing
   email containing a malicious attachment or link, or exploits an unpatched
   vulnerability in a network-facing system.
2. **Execution** — Once inside, the malware executes and begins scanning the
   system and connected network for files to encrypt.
3. **Encryption** — Files are encrypted using strong asymmetric cryptography.
   The decryption key is held only by the attacker.
4. **Ransom Demand** — A ransom note appears on screen demanding payment
   (often in Bitcoin) within a deadline, threatening permanent data loss.
5. **Propagation** — Advanced ransomware like WannaCry exploits network
   vulnerabilities (EternalBlue/SMB) to self-propagate across connected devices.

## Who is Usually Targeted?
- Hospitals and healthcare institutions (high urgency to restore access)
- Government agencies and public utilities
- Universities and educational institutions
- Small and medium businesses with outdated systems
- Individual users running unpatched operating systems

## Consequences
The WannaCry attack infected over 230,000 systems across 150 countries in May
2017. The UK's National Health Service (NHS) was severely impacted — operations
were cancelled, patient records became inaccessible, and emergency services were
diverted. Estimated global damages exceeded $4 billion USD. The attack exploited
a known Windows vulnerability (MS17-010) for which a patch had already been
released — making it largely preventable.

**Source:** Europol, NCSC UK — WannaCry Ransomware Campaign Report (2017)
