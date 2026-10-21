# Automated-Threat-Analysis-of-Broken-Authentication-Controls-and-Local-Binary-Hijacking
A cybersecurity major project exploring web application security assessment, Nmap reconnaissance, directory enumeration, file-upload validation, reverse-shell testing, and Linux privilege escalation in the authorized TryHackMe RootMe lab, with a focus on evidence-based findings and defensive security recommendations.

# Automated Threat Analysis of Broken Authentication Controls and Local Binary Hijacking

**Organization:** Bitcrown Labs  
**Project Type:** Cybersecurity Major Project — 5th Semester  
**Lab Environment:** TryHackMe RootMe  
**Author:** Abhishek Bag Yadav

## Project Overview

This project documents a controlled cybersecurity assessment of the TryHackMe RootMe lab, focusing on exposed services, web application behavior, file-upload security, remote command-execution validation, and Linux privilege boundaries.

The assessment follows a structured penetration-testing workflow, beginning with network reconnaissance and directory enumeration, then examining the web application's upload functionality and reviewing host-level permissions where access was obtained. The project also identifies defensive measures that can reduce the risk of web application compromise and unauthorized privilege escalation.

## Objectives

- Identify the assigned lab target and discover exposed services using Nmap.
- Enumerate web directories and identify accessible application paths using Gobuster.
- Inspect file-upload functionality and document observed validation behavior.
- Record reverse-shell/session evidence where demonstrated in the authorized lab.
- Review Linux permissions and potentially unsafe SUID binaries.
- Document findings with screenshots, technical observations, and evidence.
- Recommend defensive controls for secure file uploads, Linux hardening, and network security.

## Methodology

1. **Reconnaissance:** Identify the assigned target and scan for reachable ports and services using Nmap.
2. **Directory Enumeration:** Use Gobuster to discover accessible paths and directories exposed by the web server.
3. **Web Application Inspection:** Examine the application and its upload functionality, recording actual responses.
4. **Upload Security Testing:** Assess how the application handles permitted and unexpected file types within the lab's rules.
5. **Session Validation:** Document command-execution or shell-session evidence only where it was actually demonstrated.
6. **Privilege-Escalation Review:** Examine relevant Linux permissions and SUID configuration to understand privilege-boundary risks.
7. **Defensive Analysis:** Recommend practical mitigations based on observed behavior and the risks being assessed.

## Tools and Technologies

- Kali Linux
- Nmap
- Gobuster
- Linux command-line utilities
- Netcat, where used in the authorized lab
- Metasploit Framework, where applicable
- TryHackMe RootMe

## Defensive Recommendations

The project highlights the importance of server-side file-type validation, safe upload storage, disabling script execution in upload directories, least-privilege service accounts, secure SUID permissions, regular patching, network access restrictions, and security monitoring.

## Evidence and Reporting

The project report includes the assessment workflow, screenshots, technical observations, findings documentation, attack-chain mapping, limitations, and defensive recommendations. Conclusions should be based on authentic lab evidence, and unverified stages should be clearly marked as not demonstrated.

## Scope and Disclaimer

This project was created for educational purposes within the assigned TryHackMe RootMe lab. All testing should remain within the authorized environment. The techniques and findings described here are intended to support cybersecurity learning, security validation, and defensive improvement.

## Learning Outcomes

- Understanding the penetration-testing lifecycle.
- Performing network and web directory reconnaissance.
- Evaluating web upload security controls.
- Understanding remote shell/session validation.
- Recognizing Linux privilege-escalation risks.
- Producing evidence-based security reports and remediation recommendations.
