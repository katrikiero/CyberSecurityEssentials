# CyberSecurityEssentials training program

Cybersecurity Essentials is a half year cybersecurity training program organised by a [Women4CyberFinland](https://www.women4cyberfinland.com/cse2024) and [Helsec](https://helsec.fi).

Purpose of this repo is to dive a bit deeper after each training session.

## 01 January

_Program kickoff -hosted by WithSecure_

## 02 February

_Security Operations Foundations -hosted by CGI_

The task was to analyze a security log in a [Pastebin](https://pastebin.com/faq) site, which is a text/code storage site. There are *locked pastes* that need password and *public pastes* that anyone can see. 

### IP analysis
- whois
- threat intel

**Internal/private networks (non-routable) are in range:**
- Class A: 10.0.0.0 to 10.255.255.255
- Class B: 172.16.0.0 to 172.31.255.255
- Class C: 192.168.0.0 to 192.168.255.255

Anything out of this range are public (external) IP´s and needs to be checked from IP-databases like:
- [AbuseIPDB](https://www.abuseipdb.com)
- [IBM X-Force Exchange](https://exchange.xforce.ibmcloud.com)
- [Project Honey Pot](https://www.projecthoneypot.org/search_ip.php)

### Process analysis
- signatures
- threat intel
- other footprints

Malicious actor used many techniques to gain access first to the Worpress site and than to the entire web server.

**Tools and tecniques used:**
- Wp-login: Bruteforce attack to the wordpress site
- 

**More to read:**
- [Wordpress penetration testing](https://www.getastra.com/blog/security-audit/wordpress-penetration-testing/)
- [Wordpress black box testing basics](https://wpscan.com/blog/wordpress-black-box-testing-basics/)

### User analysis
- logins
- Overview

**Glossary - Sanasto**

- **Whois** = Query and laguage protocol that searches database, there are domain names and other information related to to that. / FI: Kysely ja vastaus protokolla, jolla haetaan tietoa tietokannasta. Tiedoissa on yleensä esim. domain ja sen haltijan tiedot.
- **Threat intel** = Threat intelligence, gathering information to make analysis and understand the threat. / FI: Uhkatiedustelu (uhasta kerättävät tiedot ja analaysointi, jotta uhka opitaan tunnistamaan.)
- **Signature / Signature Analysis** = Signature is a unique digital signature/proof/verification like biometric (fingerpints, face recognition), file hashing, etc. "Signature analysis is looking for something that is already known to be suspicious or malicious."
- - **Signature / Signature Analysis** = Signature is a unique digital signature/proof/verification like biometric (fingerpints, face recognition), file hashing, etc. "Signature analysis is looking for something that is already known to be suspicious or malicious."


## 03 March

_Learn how to get started with penetration testing -hosted by Nixu_

## 04 April

_OSINT & Social Engineering -hosted by Elisa_

## 05 May

_Cloud Security for Beginners -hosted by Nordcloud_

##06 June
Digital Forensics and Incident Response + program wrap-up -hosted by Accenture Security
