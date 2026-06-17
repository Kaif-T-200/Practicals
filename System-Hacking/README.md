# Windows System Hardening, Privilege Escalation Awareness & Persistence Detection Lab

## Overview

This repository documents an educational Windows system security lab that explores how attackers attempt to escalate privileges, establish persistence, and abuse remote access mechanisms within a controlled environment.

The lab focuses on understanding the attack lifecycle from a defensive perspective, including privilege escalation concepts, User Account Control (UAC) weaknesses, persistence mechanisms, remote access abuse, and post-compromise detection opportunities.

Modern attackers rarely stop after obtaining initial access. They often attempt to elevate privileges, maintain long-term access, and evade detection. Understanding these behaviors enables defenders to implement stronger security controls and reduce organizational risk.

The primary goal of this repository is to build practical blue-team awareness, improve Windows security knowledge, and demonstrate how multiple security layers work together to defend enterprise systems.

---

## Objectives

* Understand the Windows privilege escalation lifecycle.
* Learn how User Account Control (UAC) can be targeted.
* Analyze common persistence mechanisms.
* Identify risks associated with unauthorized remote access.
* Understand post-compromise attacker behaviors.
* Learn how to detect suspicious privilege changes.
* Strengthen Windows hardening practices.
* Develop defensive incident response awareness.

---

## Lab Environment

| Role                  | Platform   | IP Address  |
| --------------------- | ---------- | ----------- |
| Attacker Lab Machine  | Kali Linux | 20.20.11.32 |
| Target Lab Machine    | Windows 10 | 20.20.11.42 |
| Remote Desktop Client | xfreerdp   | N/A         |

---

## Tools Used

| Tool                 | Purpose                                                                          |
| -------------------- | -------------------------------------------------------------------------------- |
| Metasploit Framework | Study privilege escalation and persistence concepts in a controlled environment. |
| msfvenom             | Understand payload generation concepts for defensive analysis.                   |
| Python HTTP Server   | Simulate controlled file hosting scenarios.                                      |
| xfreerdp             | Analyze remote desktop access configurations.                                    |
| Windows Registry     | Study system configuration changes and security implications.                    |
| Windows Event Viewer | Monitor security-related activities and events.                                  |
| Command Prompt       | Examine administrative operations and system management tasks.                   |

---

## Tasks Performed

### Task 1: Initial Access Lifecycle Analysis

This task examined how attackers may establish an initial foothold within a compromised environment and why endpoint protection mechanisms are critical.

**Concepts Covered:**

* Initial access
* Endpoint security
* Threat detection

**Learning Outcome:**

Users learned how attackers attempt to execute malicious code and why application control policies are essential.

### Task 2: Privilege Escalation Awareness

This task analyzed how User Account Control weaknesses can be abused to obtain elevated privileges.

**Concepts Covered:**

* User Account Control
* Privilege escalation
* Administrative permissions

**Learning Outcome:**

Users learned why least privilege principles and proper UAC configurations are important defensive controls.

### Task 3: SYSTEM-Level Access Analysis

This task explored the risks associated with obtaining the highest privilege level on Windows systems.

**Concepts Covered:**

* SYSTEM privileges
* Access management
* Privileged accounts

**Learning Outcome:**

Users learned how elevated privileges significantly increase organizational risk.

### Task 4: Persistence Mechanism Analysis

This task examined how attackers attempt to maintain long-term access to compromised systems.

**Concepts Covered:**

* Startup persistence
* Registry modifications
* Unauthorized access retention

**Learning Outcome:**

Users learned where defenders should monitor for persistence indicators.

### Task 5: Remote Access Security Review

This task analyzed remote desktop configuration risks and account management practices.

**Concepts Covered:**

* Remote Desktop Protocol
* User account management
* Remote access security

**Learning Outcome:**

Users learned how improperly configured remote access services can become attack vectors.

---

## Techniques Demonstrated

| Technique                      | Description                                            |
| ------------------------------ | ------------------------------------------------------ |
| Privilege Escalation Awareness | Understanding how attackers seek elevated permissions. |
| UAC Analysis                   | Studying User Account Control weaknesses.              |
| Persistence Analysis           | Identifying methods used to retain access.             |
| Registry Monitoring            | Detecting suspicious configuration changes.            |
| Remote Access Review           | Evaluating RDP security risks.                         |
| Account Management Analysis    | Identifying unauthorized account creation.             |
| Security Monitoring            | Tracking suspicious system activity.                   |
| Post-Compromise Analysis       | Understanding attacker behavior after initial access.  |

---

## Key Findings

* Administrative privileges dramatically increase attack impact.
* Persistence mechanisms often rely on registry and startup modifications.
* Remote Desktop services require strong access controls.
* User Account Control should not be treated as a standalone defense.
* Continuous monitoring is necessary to detect suspicious activities.
* Least privilege principles significantly reduce risk.

---

## Defensive Recommendations

### Always:

* Enforce least privilege access policies.
* Monitor registry changes and startup locations.
* Enable logging and security monitoring for privileged activities.

### Never:

* Disable security controls for convenience.
* Expose Remote Desktop services without proper protections.
* Allow unnecessary administrative privileges.

---

## Skills Gained

* Windows security analysis
* Privilege escalation awareness
* Persistence detection
* Security monitoring
* Remote access security
* Incident response awareness
* Registry analysis
* Defensive system hardening

---

## Conclusion

This lab provided practical insight into how attackers attempt to escalate privileges, establish persistence, and maintain unauthorized access within Windows environments. Understanding these techniques is essential because defenders must recognize attacker behavior to implement effective security controls. Strong monitoring, least privilege enforcement, and proper system hardening significantly improve an organization's defensive posture.

---

## Disclaimer

This project is intended solely for educational, ethical hacking, and cybersecurity awareness purposes.

All activities were performed in a controlled lab environment. Do not use these techniques against systems, networks, or individuals without proper authorization.

---

## Metadata

**Author:** Kaif Tarasgar

**Topic:** Windows System Hardening, Privilege Escalation Awareness & Persistence Detection

**Focus Areas:** Windows Security, Privilege Escalation, Persistence Detection
