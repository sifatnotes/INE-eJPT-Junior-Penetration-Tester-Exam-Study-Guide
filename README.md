# INE-eJPT-Junior-Penetration-Tester-Exam-Study-Guide
Prepare for the INE eJPT certification with penetration testing study notes, networking and web security concepts, practical lab ideas, exam preparation tips, and a structured 30-day study plan.

# INE eJPT Junior Penetration Tester Study Guide

A practical, beginner-friendly **INE eJPT exam guide** covering reconnaissance, network auditing, exploitation, and web application penetration testing.

## Introduction

This repository provides eJPT study notes, exam preparation guidance, revision topics, lab suggestions, and a 30-day study plan. It is intended for cybersecurity beginners, IT students, aspiring ethical hackers, and junior penetration testers.

Use it alongside INE's official training and exam objectives.

## Exam Overview

| Item | Details |
|---|---|
| Vendor | INE Security |
| Certification | Junior Penetration Tester (eJPT) |
| Exam code | eJPT |
| Purpose | Validate entry-level, practical penetration testing skills |
| Target candidates | Beginners with basic networking and system knowledge |
| Prerequisites | No mandatory prerequisite stated; foundational knowledge recommended |
| Format | Hands-on practical exam with questions |
| Duration | 48 hours |
| Question count | 45 questions, according to the March 2026 update |
| Passing score | Verify current requirements with INE |
| Certification validity | 3 years |

INE announced the updated exam in March 2026. Check the official certification page for current exam conditions.

## Who Should Take It?

The eJPT is suitable for:

- Students starting a cybersecurity career.
- IT support and system administration professionals.
- Aspiring penetration testers and ethical hackers.
- Security analysts developing offensive security skills.

A working knowledge of TCP/IP, Linux commands, Windows fundamentals, and basic web technologies will help.

## Exam Objectives / Domains

INE's published domains:

1. **Host and Network Penetration Testing — 35%**
   - Identify and modify exploits.
   - Use Metasploit.
   - Demonstrate pivoting, routing, and port forwarding.
   - Perform authorized password attacks and hash cracking.

2. **Assessment Methodologies — 25%**
   - Discover network endpoints, ports, services, and operating systems.
   - Perform passive and active reconnaissance.
   - Gather public company, email, and technical information.
   - Identify vulnerabilities and assess their impact.

3. **Host and Networking Auditing — 25%**
   - Enumerate system, user, and network information.
   - Review files and password/hash information.
   - Transfer files between systems.

4. **Web Application Penetration Testing — 15%**
   - Perform web reconnaissance and vulnerability identification.
   - Discover hidden files and directories.
   - Understand login testing and CMS security, including WordPress.

## Detailed Study Notes

### 1. Reconnaissance and Assessment

Reconnaissance builds an understanding of the authorized target before testing.

- **Passive reconnaissance:** Gather information without directly interacting with the target, such as reviewing public DNS records.
- **Active reconnaissance:** Interact with the target, such as scanning permitted hosts and services.
- **Port scanning:** Identify reachable TCP/UDP services. Understand what open, closed, and filtered ports indicate.
- **Service enumeration:** Determine service versions and configuration details.
- **Risk assessment:** Consider exploitability, exposure, and potential impact—not merely scanner output.

### 2. Host and Network Auditing

Practice collecting evidence systematically.

- Linux: users, groups, processes, interfaces, routes, files, and permissions.
- Windows: users, running services, network configuration, and accessible files.
- Understand password hashes and why hashing differs from encryption.
- Learn safe file transfer methods and document the source and destination.

### 3. Penetration Testing

Understand the relationship between vulnerability discovery, exploit selection, execution, and validation.

- Metasploit: modules, payloads, options, sessions, and result verification.
- Exploit modification: understand parameters and prerequisites; avoid blindly running code.
- Pivoting: use an authorized foothold to reach another permitted network segment.
- Password security: learn rate limits, password policy weaknesses, hash formats, and offline cracking concepts.

### 4. Web Application Testing

- Map application pages, parameters, technologies, and authentication flows.
- Understand common issues such as injection, broken access control, and weak authentication.
- Use directory enumeration tools such as Gobuster in authorized labs.
- Learn Nikto's role in web server and application scanning.
- Understand CMS and WordPress attack surfaces, outdated components, and configuration risks.

### 5. Responsible Use of AI

INE's updated learning content includes generative AI for pentesters. Understand basic LLM concepts, prompt engineering, and responsible use. Verify AI-generated technical advice and never allow it to expand the authorized scope.

## Important Concepts

- TCP/IP, subnetting, ports, DNS, routing, and common services.
- Passive versus active reconnaissance and target scoping.
- Nmap scanning and service enumeration.
- Linux and Windows host auditing.
- Metasploit workflow and exploit validation.
- Pivoting, port forwarding, hashes, and password security.
- Web reconnaissance, directory discovery, CMS testing, and vulnerability impact.
- Documentation, authorization, and scope control.

## Practical Examples / Labs

Use only systems you own or have explicit permission to test.

1. Build an isolated virtual lab with a penetration-testing machine and intentionally vulnerable targets.
2. Scan the lab network and record discovered hosts, ports, and services.
3. Enumerate Linux and Windows information in guided exercises.
4. Practice Metasploit against a deliberately vulnerable lab target.
5. Configure a lab route or port forward to understand pivoting.
6. Test a vulnerable web application for directory exposure and common flaws.
7. Write a short report with evidence, impact, and remediation for each finding.

## Study Strategy

- Follow the official INE eJPT learning path.
- Study one domain at a time and keep concise notes.
- Repeat hands-on labs until you can explain each step.
- Use legitimate practice questions and review why each answer is correct.
- Maintain a command reference and a checklist of weak areas.
- Revisit mistakes and repeat the relevant lab before moving on.

## 30-Day Study Plan

| Days | Focus |
|---|---|
| 1–3 | Networking, Linux, Windows fundamentals |
| 4–8 | Assessment methodologies and reconnaissance |
| 9–13 | Host and network auditing |
| 14–20 | Exploitation, Metasploit, pivoting, hashes |
| 21–24 | Web application testing and CMS fundamentals |
| 25–27 | Mixed practical labs and weak areas |
| 28 | Timed practice and review |
| 29 | Revise notes, commands, and reporting |
| 30 | Light revision; confirm exam setup and requirements |

Adjust the schedule to your experience and available study time.

## Common Mistakes

- Scanning outside the authorized scope.
- Rushing into exploitation without enumeration.
- Trusting scanner results without validation.
- Forgetting to record evidence, credentials, or discovered services.
- Ignoring web application objectives.
- Practicing commands without understanding their output.
- Leaving exam logistics and voucher expiration until the last minute.

## Exam-Day Tips

- Read the exam rules and scope carefully.
- Start with structured reconnaissance and keep organized notes.
- Prioritize findings that advance the authorized assessment.
- Verify results rather than assuming an exploit succeeded.
- Track time and avoid spending too long on one obstacle.
- Follow INE's rules for tools, assistance, and permitted resources.

## Final Checklist

- [ ] Reviewed all four official domains.
- [ ] Practiced host discovery, enumeration, and service scanning.
- [ ] Completed authorized exploitation and pivoting labs.
- [ ] Practiced web reconnaissance and vulnerability testing.
- [ ] Reviewed notes, commands, and weak areas.
- [ ] Confirmed exam format, access, and voucher validity.

## Official Resources

- [INE eJPT Certification](https://ine.com/security/certifications/ejpt-certification)
- [INE announcement: updated eJPT certification](https://ine.com/newsroom/ine-security-launches-updated-ejpt-certification-with-expanded-web-app-testing-recon-training-and-offensive-ai)
- [INE Security training](https://ine.com/)
- [Nmap Reference Guide](https://nmap.org/book/man.html)
- [Metasploit documentation](https://docs.metasploit.com/)
- [OWASP Web Security Testing Guide](https://owasp.org/www-project-web-security-testing-guide/)

Consult INE for the latest objectives, exam rules, and official practice resources.

## Voucher / Discount

Looking for an **eJPT exam voucher**? Learn SecByte provides certification voucher options and discounts where available.

Check current pricing, availability, and terms:

https://learn.secbyte.org/vouchers/ine-ejpt

Compare the available options and confirm that the voucher matches your exam and eligibility requirements before purchasing.

## Disclaimer

This is an independent community study guide and is not endorsed by INE. INE and eJPT trademarks belong to their respective owners. Verify all exam information with the official vendor before booking. Voucher pricing and availability may change. This repository contains educational notes and lab guidance, not exam dumps, leaked questions, or recalled exam questions.
