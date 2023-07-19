---
title: MITRE ATT&CK Framework
categories: [Security Frameworks, Attack Frameworks]
tags: [Security Frameworks]
---

## Introduction

(***A**dversarial **T**actics, **T**echniques, **&** **C**ommon **K**nowledge*)

The MITRE ATT&CK framework serves as an encyclopedia of previously observed tactics from threat actors. It helps security practitioners better-understand the behavior of these threat actors. 

Identifying adversary plans of attack can be challenging to embark on blindly. They can be understood through the behaviors, methods, tools and strategies established for an attack, commonly known as **Tactics**, **Techniques** and **Procedures** (TTPs). 

The MITRE ATT&CK framework is a knowledge base of TTPs, carefully curated and detailed to ensure security teams can identify attack patterns. The framework’s structure is similar to a periodic table, mapping techniques against phases of the attack chain and referencing system platforms exploited.

This framework highlights the detailed approach it provides when looking at an attack. It brings together environment-specific cybersecurity information to provide cyber threat intelligence insights that help teams develop effective security programs for their organizations. 

## The MITRE ATT&CK Matrix


The MITRE ATT&CK matrix contains a set of techniques used by adversaries to accomplish a specific objective. Those objectives are categorized as tactics in the ATT&CK Matrix. 

The objectives are presented linearly from the point of reconnaissance -to- the final goal of exfiltration (or "impact"). The following adversary tactics are categorized: 

1. **Reconnaissance**: gathering information to plan future adversary operations, i.e., information about the target organization.
2. **Resource Development**: establishing resources to support operations, i.e., setting up command and control infrastructure.
3. **Initial Access**: trying to get into your network, i.e., spear phishing.
4. **Execution**: trying the run malicious code, i.e., running a remote access tool.
5. **Persistence**: trying to maintain their foothold, i.e., changing configurations.
6. **Privilege Escalation**: trying to gain higher-level permissions, i.e., leveraging a vulnerability to elevate access.
7. **Defense Evasion**: trying to avoid being detected, i.e., using trusted processes to hide malware.
8. **Credential Access**: stealing accounts names and passwords, i.e., keylogging.
9. **Discovery**: trying to figure out your environment, i.e., exploring what they can control.
10. **Lateral Movement**: moving through your environment, i.e., using legitimate credentials to pivot through multiple systems.
11. **Collection**: gathering data of interest to the adversary goal, i.e., accessing data in cloud storage.
12. **Command and Control**: communicating with compromised systems to control them, i.e., mimicking normal web traffic to communicate with a victim network.
13. **Exfiltration**: stealing data, i.e., transfer data to cloud account.
14. **Impact**: manipulate, interrupt, or destroy systems and data, i.e., encrypting data with ransomware.

Within each tactic of the MITRE ATT&CK matrix there are adversary techniques, which describe the actual activity carried out by the adversary. Some techniques have sub-techniques that explain how an adversary carries out a specific technique in greater detail

---

Source: [https://attack.mitre.org/](https://attack.mitre.org/)

---
