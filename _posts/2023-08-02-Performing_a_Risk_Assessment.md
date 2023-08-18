---
title: Guide - Performing a Risk Assessment
categories: [Security Guides, Organizational Security Guides] 
tags: [Security Guides]
---

## Summary

A cyber risk assessment involves systematically identifying, evaluating, and prioritizing potential cybersecurity risks to the organization's information systems, data, and operations. This process helps organizations understand the cybersecurity threats they face and take appropriate measures to mitigate those risks.

## Risk Assessment Phases

A typical risk assessment process involves several phases to systematically identify, analyze, and evaluate potential risks to an organization. While different frameworks and methodologies might structure the phases slightly differently, here's a commonly used breakdown of the key phases of a risk assessment:

1. __Risk Identification__:
   In this phase, the goal is to identify and document all potential risks that could affect the organization. This includes both internal and external risks that could impact operations, assets, data, reputation, and objectives. Stakeholders, subject matter experts, historical data, and industry best practices are often used to identify risks.
   > Note: Prior to this phase, the _scope_ and _goal_ of this risk assessment have been pre-defined. It's also expected that an inventory of the organization's assets has been created, as well as the classification of the assets based on their sentisivity and criticality.
   {: .prompt-info }

2. __Risk Analysis and Calculation__:
  Once risks are identified, they need to be calculated to understand their potential impact and likelihood of occurrence. This phase involves assigning qualitative or quantitative values to impact and likelihood. The _Risk = Likelihood × Impact_ formula is often used to calculate a risk score for each risk, which helps ultimately prioritize these risks.
  For the example scenario below, we'll use a scale of 1 to 5 for both impact and likelihood (where 1 represents the lowest and 5 represents the highest):

     __Scenario: DDoS Attack Risk Assessment__
     1. Likelihood Assessment:
       * Likelihood of a DDoS attack: __4__ (based on historical trends and increased prevalence of DDoS attacks in the industry).
     2. Impact Assessment:
       * Financial impact of website outage: 3 (Moderate)
       * Operational impact: 5 (Severe)
     3. Quantitative Risk Calculation:
       * Likelihood: __4__ (out of 5)
       * Impact: 3 + 5 = __8__ (sum of financial and operational impact values)

     __Risk Calculation and Classification__
     * Calculated Risk Score: __4__ × __8__ = __32__
     * The calculated risk score of 32 indicates a significant risk level for this DDoS attack scenario. (Note: organizations may tailor the impact and likelihood scales to their specific needs, incorporating additional factors such as control effectiveness or regulatory compliance) 
    
3. __Risk Evaluation and Prioritization__:
  In this phase, the calculated risk scores are compared against predefined risk tolerance or acceptance criteria. This helps determine which risks are acceptable, which need further mitigation, and which may require additional analysis. The goal is to decide which risks are worth addressing and which can be managed within acceptable levels.
  Prioritize risks based on their calculated risk levels. Focus on high-priority risks that have significant potential impact and likelihood.

4. __Risk Treatment (Mitigation)__:
  Based on the risk evaluation, this phase involves developing and implementing strategies to manage, reduce, or eliminate the identified risks. Risk treatment strategies can include risk avoidance, risk reduction, risk sharing (e.g., insurance), and risk acceptance. Mitigation measures are designed to bring the risks within acceptable levels.
    Develop and recommend risk mitigation strategies and controls to address the identified vulnerabilities. These strategies may involve implementing technical controls, improving processes, providing training, and more.

   > Note: During this phase, a comprehensive risk analysis report is presented to stakeholders. This report will help guide the mitigation process. 
   {: .prompt-info }

5. __Risk Monitoring and Review__
   Some risk assessment models include a monitoring and review phase as the fifth step. In this phase, the implemented risk mitigation measures are continuously monitored to ensure their effectiveness. Regular reviews are conducted to assess changes in the organization's risk landscape, adapt to new risks, and update risk assessments accordingly. 

By following these phases, organizations can gain insights into their cybersecurity risks, develop informed strategies to address those risks, and create a more resilient and secure digital environment. Different organizations and industries might use variations of these phases based on their specific needs, risk management frameworks, and regulatory requirements. The key is to ensure that the assessment process is thorough, structured, and aligned with the organization's goals and risk appetite.

It's important to note that conducting a cyber risk assessment requires a combination of technical expertise, understanding of the organization's operations, and knowledge of cybersecurity best practices. Organizations may choose to engage internal teams or seek assistance from external cybersecurity experts to ensure a comprehensive and effective assessment.

## NIST Risk Management Framework (RMF)

It's also important to note the NIST Risk Management Framework (RMF), as it is a well-known and frequently-utilized framework for managing organizational risk. The NIST RMF is a systematic process developed by the National Institute of Standards and Technology (NIST) to assist organizations in managing cybersecurity risks and improving their overall security posture. It emphasizes a proactive and continuous approach to identifying, assessing, mitigating, and monitoring risks associated with information systems and data. 

NIST SP 800-37, titled "Risk Management Framework for Information Systems and Organizations", provides detailed guidance on implementing the NIST RMF. 

### The 6 RMF Steps

> Note: Each step also includes relevant NIST Special Publications (SP) that may be utilized. These SPs collectively provide the necessary guidance, control requirements, assessment methodologies, and best practices to implement the NIST RMF effectively. 
   {: .prompt-info }

1. __Categorize [[Information Systems]]__:
   Organizations identify and categorize information systems and data based on factors such as importance, sensitivity, and potential impact. This step lays the foundation for determining appropriate security controls.

   > Note: These publications help organizations categorize their information systems based on the types of information they handle and their corresponding security categories. This categorization is essential for determining appropriate security controls:
   > * NIST SP 800-60 Volume I: Guide for Mapping Types of Information and Information Systems to Security Categories
   > * NIST SP 800-60 Volume II: Appendices to Guide for Mapping Types of Information and Information Systems to Security Categories 
   {: .prompt-info }

2. __Select [[Security Controls]]__:
   Security controls are selected from NIST Special Publication 800-53 based on the categorized systems.
   Controls are chosen to address specific risks associated with the systems.

   > Note: These documents provide a comprehensive list of security controls and associated assessment procedures. Organizations use these controls to select measures that align with their systems' categorized risks:
   > * NIST SP 800-53: Security and Privacy Controls for Federal Information Systems and Organizations
   > * NIST SP 800-53A: Assessing Security and Privacy Controls in Federal Information Systems and Organizations 
   {: .prompt-info }

3. __Implement [[Security Controls]]__:
   Organizations implement the selected security controls by configuring hardware, software, policies, and procedures.
   The goal is to establish necessary security measures to protect confidentiality, integrity, and availability.

   > Note: These resources provide guidelines for using checklists to implement security controls (NIST SP 800-70), as well as ensures proper implementation of controls in specific products and solutions (vendor documentation):
   > * NIST SP 800-70 Rev. 4: National Checklist Program for IT Products - Guidelines for Checklist Users and Developers
   > * Vendor-specific guidelines and documentation - for implementing security controls in hardware, software, and systems
   {: .prompt-info }

4. __Assess [[Security Controls]]__:
   Security controls' effectiveness is assessed through security testing, reviews, and evaluations.
   Organizations ensure that controls are functioning as intended and providing the desired level of protection.

   > Note: NIST SP 800-53A outlines assessment procedures, SP 800-115 provides guidance on security testing, and SP 800-53B provides control baselines to assess against. These documents aid in evaluating the effectiveness of security controls:
   > * NIST SP 800-53A: Assessing Security and Privacy Controls in Federal Information Systems and Organizations
   > * NIST SP 800-115: Technical Guide to Information Security Testing and Assessment
   > * NIST SP 800-53B: Control Baselines for Information Systems and Organizations
   {: .prompt-info }

5. __Authorize [[Information Systems]]__:
   Based on assessment results, organizations make an authorization decision.
   This decision considers residual risks and determines if the system is authorized for operation.

   > Note: NIST SP 800-37 provides guidance on authorization decision-making, while SP 800-53A and SP 800-53B support the assessment of controls' effectiveness:
   > * NIST SP 800-37 Rev. 2: Risk Management Framework for Information Systems and Organizations
   > * NIST SP 800-53A: Assessing Security and Privacy Controls in Federal Information Systems and Organizations
   > * NIST SP 800-53B: Control Baselines for Information Systems and Organizations
   {: .prompt-info }

6. __Monitor [[Security Controls]]__:
   Continuous monitoring practices are established to track the security posture of the system over time.
   This involves ongoing assessment, anomaly detection, and proactive response to emerging threats.

   > Note: NIST SP 800-137 offers guidance on continuous monitoring, while SP 800-53A and SP 800-137A provide guidance on assessing controls and building effective assessment plans for continuous monitoring:
   > * NIST SP 800-37 Rev. 2: Risk Management Framework for Information Systems and Organizations
   > * NIST SP 800-53A: Assessing Security and Privacy Controls in Federal Information Systems and Organizations
   > * NIST SP 800-53B: Control Baselines for Information Systems and Organizations
   {: .prompt-info }

The NIST RMF emphasize a continuous and iterative approach to cybersecurity. It provides organizations with a structured and standardized methodology for managing risks, protecting information systems, and enhancing security practices. Following these guidelines helps organizations adapt to evolving threats and vulnerabilities while maintaining a robust cybersecurity posture.

---

References:
* [NIST Risk Management Framework](https://csrc.nist.gov/projects/risk-management/about-rmf)
