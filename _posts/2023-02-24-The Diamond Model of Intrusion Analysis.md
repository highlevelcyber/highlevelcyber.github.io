---
title: The Diamond Model of Intrusion Analysis
categories: [Security Frameworks, Attack Frameworks]
tags: [Security Frameworks]
---

## Introduction


The Diamond Model of Intrusion Analysis doesn’t follow a linear flow as the other intrusion models (MITRE ATT&CK, Kill Chain).  The creators of The Diamond Model (Sergio Caltagirone, Andrew Pendergrast and Christopher Betz) noticed the shared weaknesses of these linear models and decided to create a non-linear model to overcome this. 

## Structure

The Diamond Model is so named because of the shape formed by the relationship between the 4 core features of an intrusion event — [1] Adversary, [2] Infrastructure, [3] Capability, and [4] Target. 

1. **Adversary**: Where are attackers from? Who are the attackers? Who is the sponsor? Why attack? What is the activity timeline and planning?
2. **Infrastructure**: Infected computer(s), C2 domain names, location of C2 servers, C2 server types, mechanism and structure of C2, data management & control, and data leakage paths
3. **Capability**: What skills do the attackers have to do reconnaissance, deliver their attacks, attack exploits and vulnerabilities, deploy their remote-controlled malwares and backdoors, and develop their tools.
4. **Target**: Who is their target country/region, industry sector, individual, or data?

![DiamondModel.png](https://s3-us-west-2.amazonaws.com/secure.notion-static.com/2d91c97b-e11a-4ce5-87c8-f9232e56999d/DiamondModel.png)

The adversary uses its capabilities over some infrastructure against a victim.

## Using the model

The Diamond Model’s value for CTI analysts is in identifying relationships between events, and in analyzing events to learn about adversary behavior. In analytic pivoting, you start with one point on the diamond and pivot to discover and learn more about the other points. 

For example, learning about a victim can lead to learning more about the adversary’s capabilities and infrastructure.

The Diamond Model isn’t meant to be used to look at an intrusion event as a point in time; it’s meant to track adversaries over time.

An activity thread shows the chain of events and causal relationships between them as the adversary has acted against multiple victims. 

By correlating events across activity threads, you can identify adversary campaigns. You can also gain a fuller understanding of the adversary’s behavior, which helps plan mitigations.

An activity-attack graph goes beyond historical intel and predicts future paths the adversary could take. This helps you plan mitigations.

---

Source: [https://www.activeresponse.org/wp-content/uploads/2013/07/diamond.pdf](https://www.activeresponse.org/wp-content/uploads/2013/07/diamond.pdf)

---
