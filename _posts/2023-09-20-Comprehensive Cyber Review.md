---
title: Comprehensive Cyber Review Guide
categories: [Career Resources, Knowledge Training]
tags: [Career, Courses]
---
## __Summary__
This high-level guide consists of 11 distinct cybersecurity domains that are widely prevalent in general cyber practices. Together, these domains create a comprehensive framework for comprehending the various facets of cybersecurity. 

> These comprehensive domains are based on the "[Cybersecurity Domain Map](https://www.linkedin.com/pulse/cybersecurity-domain-map-ver-30-henry-jiang%3F)" constructed by Henry Jiang.
> <details><summary>Image: Cybersecurity Domain Map</summary><img src="/assets/cyber_domains_2021.png"></details>
{: .prompt-info }

## __Cybersecurity Domains__

### 1. **Application Security**: Explore techniques to secure software applications, from source code analysis to API security, ensuring robust protection against vulnerabilities.

- **Data-Flow Diagram**: Explaining the flow of data within an application for identifying security vulnerabilities.
- **Source Code Scan**: Techniques for scanning source code for vulnerabilities, including Static Application Security Testing (SAST) and Open Source Scan.
    - **SAST**: Static Analysis Security Testing.
    - **Open Source Scan**: Identifying vulnerabilities in third-party libraries.
- **API Security**: Ensuring the security of Application Programming Interfaces.
- **Security QA**: Quality assurance practices with a security focus.
- **Security UX**: Incorporating security into the user experience design.
- **S-SDLC** (Security Software Development Life Cycle): Integrating security throughout the software development process.
    - **“Shift Left”**: Early integration of security in development.
    - **CI/CD Integration**: Security in continuous integration and continuous delivery pipelines.

### 2. **Risk Assessment**: The cornerstone of cybersecurity. Master the art of identifying, evaluating, and mitigating cybersecurity risks, with a focus on vulnerability scanning and penetration testing.

- **Vulnerability Scan**: Identifying and assessing vulnerabilities in systems.
- **Assets Inventory**: Cataloging and managing digital assets.
- **Risk-Monitoring Services (Risk Score)**: Continuous monitoring of security risks.
- **3rd Party Risk**: Assessing security risks from third-party vendors.
    - **4th Party Risk**: Extending risk assessment to vendors' vendors.
- **Penetration Test**: Assessing security through simulated attacks.
    - **Infrastructure (Network and Systems)**: Testing network and system security.
    - **Social Engineering**: Assessing vulnerabilities related to human interactions.
    - **DAST** (Dynamic Application Security Testing): Assessing web application security in real-time.
    - **Application PenTests**: Focusing on application-level vulnerabilities.
    - **Red & Blue Teams**: Simulating attack and defense scenarios.

### 3. **Enterprise Risk Management**: Gain insights into enterprise-level risk management, including strategies for risk treatment, cyber insurance, and crisis management. How organizations can prepare for and respond to cybersecurity threats.

- **Risk Treatment Actions**: Strategies to mitigate identified risks.
- **Risk Acceptance Statement**: Formalizing the acceptance of certain risks.
- **Cyber Insurance**: Understanding and utilizing cyber insurance policies.
- **BCP/DR** (Business Continuity Planning/Disaster Recovery): Preparing for and recovering from disasters.
- **Crisis Management**: Responding to major security incidents.
- **Risk Appetite**: Defining the organization's tolerance for risk.
- **Risk Register**: Maintaining a comprehensive list of risks.
- **Lines of Defense**: Layers of protection, including Process Owners, Risk Management Groups, and Audit.
    1. **Process Owners**: 
    2. **Risk Mgmt Group**: 
    3. **Audit**: 
        1. **SOC1/SOC2**: Auditing standards for service organizations.

### 4. **Physical Security**: Physical security is often overlooked but crucial for comprehensive protection as it complements digital safeguards. Provides protection against theft, vandalism, and unauthorized physical access. 

- **IoT Security**: Securing Internet of Things (IoT) devices.
- **Physical Access control**: Restricting physical access to secure areas.
- **Surveillance**: Monitoring physical spaces for security threats.
- **Security guards**: Human resources for physical security.

### 5. **Frameworks and Standards**: Frameworks and standards provide guidelines and best practices for organizations to establish and maintain effective cybersecurity programs. Readers will learn how to align their security practices with industry standards.

- **MITRE ATT&CK Framework**: Understanding and countering adversary tactics.
- **OWASP Top 10 (WebApp & API)**: Identifying and mitigating top web application and API vulnerabilities.
- **NIST Cybersecurity Framework (CSF)**: Framework for managing cybersecurity risk.
- **CIS** (Center for Internet Security): Guidelines and benchmarks for security.
    - **CIS Top 20 Controls**: Prioritized security actions.
    - **CIS Benchmarks**: Configuration guidelines.
- **ISO** (International Organization for Standardization): International security standards.
    - **ISO 27001**: Information security management system.
    - **ISO 27017**: Cloud security.
    - **ISO 27018**: Personal data protection.

### 6. **Governance**: Effective governance is essential for compliance and security. Navigate the complex landscape of laws, regulations, and corporate governance to establish robust security policies and practices.

- **Laws and Regulations**: Legal and regulatory compliance.
    - **Regional**:
        - **CCPA**:
        - **NYS-DFS 23 NYCRR 500**:
    - **Central Government**:
        - **GDPR**:
        - **GLBA**:
    - **Industry Specific**:
        - **PCI**:
        - **HIPAA**:
- **Executive Management Involvement**: Leadership's role in security.
    - **Risk Informed**: Decision-making based on risk assessments.
    - **Reports and Scorecards**: Monitoring performance with KPIs/KRIs.
        - **KPIs/KRIs**:
- **Company’s Written Policies**: Establishing security policies, procedures, standards, and guidelines.
    - **Policy**:
    - **Procedure**:
    - **Standard**:
    - **Compliance & Enforcement**: Ensuring adherence to policies.
    - **Guideline**: Best practice recommendations.

### 7. **Threat Intelligence**: Learn how to gather, analyze, and leverage threat intelligence to proactively defend against emerging threats.

- **Internal and External**: Collecting and analyzing intelligence for proactive security measures.
    - **IOCs**: Identifying potential security breaches.
    - **Intelligence Sharing**: Collaborating with other organizations.
    - **Contextual**: Understanding the broader context of threats.

### 8. **User Education**: The human factor is often the weakest link in cybersecurity. Recognize the human element in cybersecurity and discover methods to educate and engage users in maintaining security.

- **Training (new skills)**: Developing cybersecurity skills.
- **Awareness (reinforcement)**: Reinforcing security awareness among employees.
- **Cybersecurity Table-top Exercise**: Simulating real-world security incidents for training.

### 9. **Security Operations**: Effective security operations are essential for threat detection and response. Explore the operational aspects of cybersecurity, from vulnerability management to incident response, optimizing security efforts.

- **Vulnerability Management**: Identifying and addressing vulnerabilities.
- **Threat Hunting**: Proactively searching for threats.
- **Active Defense**: Proactive security measures.
- **Security Operation Center** (SOC): Centralized security monitoring.
- **SIEM**: Event correlation and analysis.
    - **SOAR**: Automated response to security incidents.
- **Incident Response**: Responding to security incidents.
    - **Breach Notification**: Communicating security breaches.
    - **Detection**:
    - **Containment**:
    - **Eradication**:
    - **Investigation**: Gathering forensic evidence.
        - **Forensics**:

### 10. **Security Architecture**: Involves designing and implementing security controls and measures across various aspects of IT infrastructure, ensuring robust system defenses. Gain a comprehensive understanding of building and maintaining secure systems.

- **Cloud Security**: Security in cloud environments.
- **Security Engineering**: Building secure systems.
- **Endpoint Hygiene**: Securing end-user devices.
- **Container Security**: Security for containerized applications.
- **Data Protection**: Safeguarding sensitive data.
    - **Data Leakage Prevention**: Preventing data leaks.
- **Network Design**: Secure network architectures.
    - **DDoS Prevention**: Protection against distributed denial-of-service (DDoS) attacks.
- **Secure System Build**: Secure system development and maintenance.
    - **Patch Management**: Managing software updates.
    - **Baseline Configuration**: Standard system configurations.
- **Cryptography**: Encryption and key management.
    - **Certificate Management**: Managing digital certificates.
    - **Encryption Standards**:
    - **Key and Secret Management**: Securing cryptographic keys.
        - **Valuting**: Secure storage of cryptographic keys.
        - **HSM** (Hardware Security Module): Dedicated cryptographic hardware.
- **Access Control**: Controlling user access.
    - **MFA & SSO**: Strong authentication.
    - **Federated Identity**: Managing identities across systems.
    - **Identity Management**: Controlling user access.
        - **Privileged Access Management** (PAM): Securing administrative access.
        - **Identity & Access Management**: Managing user identities

### 11. **Career Development**: Cybersecurity professionals need ongoing development. Learn how to stay current and grow within the field of cybersecurity.

- **Conferences**: Networking and learning opportunities.
- **Certifications**: Professional certifications in cybersecurity.
- **Training**: Ongoing educational training (in-person or digital).
- **Peer Groups**: Collaborative learning and networking.
- **Self Study**: Independent learning.
- **Coaches and Role Models**: Mentoring and guidance.

