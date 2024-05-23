# Botium Toys Mock Security Audit

# Table of contents

1. [Introduction](#introduction)
2. [Scenario](#scenario)
3. [Scope and goals of the audit](#goals)
4. [Internal Security Audit Workflow](#workflow)
5. [Controls Assessment](#control-assessment)
6. [Compliance Checklist](#compliance-checklist)
7. [Stakeholder Memorandum](#stakeholder-memo)
8. [Conclusion](#conclusion)

-------

# Introduction <a name="introduction">

Botium Toys, a fictitious toy company, was used to test the cybersecurity portfolio and as part of Google's <a href='https://www.coursera.org/google-certificates/cybersecurity-certificate'>Cybersecurity Professional Certificate</a> on Coursera in the  <a href='https://www.coursera.org/learn/manage-security-risks?specialization=cybersecurity-certificate'> Play It Safe: Manage Security Risks </a> Course.


# Scenario  <a name="scenario">
Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location. However, its online presence has grown, attracting customers in the U.S. and abroad. Their information technology (IT) department is under increasing pressure to support their online market worldwide. 

The manager of the IT department has decided that an internal IT audit needs to be conducted. She expresses concerns about not having a solidified plan of action to ensure business continuity and compliance, as the business grows. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to accepting online payments and conducting business in the European Union (E.U.).   

The IT manager starts by implementing the **National Institute of Standards and Technology Cybersecurity Framework** (NIST CSF), establishing an audit scope and goals, and completing a risk assessment. The goal of the audit is to provide an overview of the risks the company might experience due to the current state of its security posture. The IT manager wants to use the audit findings as evidence to obtain approval to expand his department.

## General Steps <a name="workflow">

To ensure the efficiency of this audit, we will adhere to the five steps imparted by the Google CyberSecurity Certificate.

1. Establishing the scope and goals
2. Conducting a Risk Assessment
3. Conducting the Audit
4. Creating a Mitigation plan
5. Communicate Results to Stakeholders

I've performed a very basic security audit, considering this is new in my cybersecurity journey I will only be focusing on step 3, having already been provided with steps 1 and 2.

------------------------

## Internal Security Audit Workflow  <a name="workflow">
The internal security audit can be broken down into two parts each with its steps to follow.

### Part 1
1. Analyze the audit scope, audit goals, and risk assessment given above
2. Conduct the Audit
   - Complete Controls assessment 
     - Select controls needing to be implemented.
     - Rate each selected control on priority (i.e. needing to be implemented immediately or in the future).
   - Complete Compliance checklist
     - Explain why selected compliance regulations and standards need to be adhered to.
### Part 2
1. Review results and deliverables completed in Part 1, Step #2
   - make note of findings
   - consider how to summarize your recommendations clearly and concisely to stakeholders. 
2. Send findings and recommendations to stakeholders in a concise format

## Scope and Goals of the Audit  <a name="goals">

The scope and goal for Botium Toys’ internal IT audit are:

**Scope**
- The scope of this audit is defined as the entire security program at Botium
Toys
- This includes their assets like employee equipment and devices, their internal
network, and their systems.
- Conducting this audit requires a full review of the assets Botium Toys has and the
controls and compliance practices they have in place

**Goals**
- Assess existing assets and complete the controls and compliance checklist to
determine which controls and compliance best practices that need to be implemented
to improve Botium Toys’ security posture.

## Assets and risk assessment

report

Current Assets 
--------------

Assets managed by the IT Department include:
- On-premises equipment for in-office business needs
- Employee equipment: end-user devices (desktops/laptops, smartphones),
remote workstations, headsets, cables, keyboards, mice, docking stations,
surveillance cameras, etc.
- Storefront products available for retail sale on site and online; stored in the
company’s adjoining warehouse
- Management of systems, software, and services: accounting,
telecommunication, database, security, e-commerce, and inventory
management
- Internet access
- Internal network
- Data retention and storage
- Legacy system maintenance: end-of-life systems that require human
monitoring

Risk assessment
--------------

**Risk description**

Currently, there is inadequate management of assets. 

Additionally, Botium Toys does not have all of the proper controls in place and may not be fully compliant with U.S. and
international regulations and standards.

**Control best practices**

The first of the five functions of the NIST CSF is **Identify**. 
Botium Toys will need to dedicate resources to identify assets so they can appropriately manage them.

Additionally, they will need to classify existing assets and determine the impact of the
loss of existing assets, including systems, on business continuity.

**Risk score**
On a scale of 1 to 10, the risk score is 8, which is fairly high. This is due to a lack of
controls and adherence to compliance best practices.

**Additional comments**
The potential impact from the loss of an asset is rated as medium because the IT
department does not know which assets would be at risk. The risk to assets or fines
from governing bodies is high because Botium Toys does not have all of the necessary
controls in place and is not fully adhering to best practices related to compliance
regulations that keep critical data private/secure. Review the following bullet points for
specific details:
- Currently, all Botium Toys employees have access to internally stored data and
may be able to access cardholder data and customers’ PII/SPII.
- Encryption is not currently used to ensure confidentiality of customers’ credit
card information that is accepted, processed, transmitted, and stored locally in
the company’s internal database.
- Access controls about least privilege and separation of duties have not
been implemented.
- The IT department has ensured availability and integrated controls to ensure
data integrity.
- The IT department has a firewall that blocks traffic based on an appropriately
defined set of security rules.
- Antivirus software is installed and monitored regularly by the IT department.

- The IT department has _not_ installed an intrusion detection system (IDS).
- There are no disaster recovery plans currently in place, and the company does
not have backups of critical data.
- The IT department has established a plan to notify E.U. customers within 72
hours if there is a security breach. Additionally, privacy policies, procedures, and
processes have been developed and are enforced among IT department
members/other employees, to properly document and maintain data.
- Although a password policy exists, its requirements are nominal and _not_ in line
with current minimum password complexity requirements (e.g., at least eight
characters, a combination of letters and at least one number; special
characters).
- There is no centralized password management system that enforces the
password policy’s minimum requirements, which sometimes affects
productivity when employees/vendors submit a ticket to the IT department to
recover or reset a password.
- While legacy systems are monitored and maintained, there is no regular
schedule in place for these tasks and intervention methods are unclear.
- The store’s physical location, which includes Botium Toys’ main offices, store
front, and warehouse of products, has sufficient locks, up-to-date
closed-circuit television (CCTV) surveillance, as well as functioning fire
detection and prevention systems.


Controls Assessment  <a name="control-assessment">
===================


### Administrative Controls 
 Control Name | Does Botium Toys currently have this control in place? (Yes or No) | Explanation/Reasoning |
| --- | --- | --- |
| Least Privilege | No | All employees have access to customer data; rights to access data must be limited to reduce the risk of a breach. |
| Disaster recovery plans | No | For the sake of business continuity, there must be disaster recovery plans in place. | 
| Password policies | No | Requirements with passwords are minimal within the organization. This allows threat actors to easily access secure data |
| Separation of duties | No | This needs to be implemented to reduce the possibility of fraud/access to critical data since the company CEO currently runs day-to-day operations |

### Technical Controls
| Control Name | Does Botium Toys currently have this control in place? (Yes or No) | Explanation/Reasoning |
| --- | --- | --- |
| Firewall | Yes | The organization already has a firewall that blocks traffic based on an appropriately defined set of security rules | 
| Intrusion Detection System (IDS) | No | An IDS must be put in place to help identify possible intrusions by threat actors |
| Backups | No | Without this control, the business lacks business continuity because, in case of a breach, critical data could be lost |
| Antivirus Software | Yes | Antivirus software is installed and monitored regularly by the IT department |
| Manual monitoring, maintenance, and intervention for legacy systems | No | Necessary to identify threats risks, and vulnerabilities in the systems. The risk assessment indicates that these systems are monitored and maintained, but there is not a regular schedule in place for this task, and procedures/ policies related to intervention are unclear, which could place these systems at risk of a breach The risk assessment states that these systems are monitored and maintained, but there is not a regular schedule in place for this task, and procedures/ policies related to intervention are unclear, which could place these systems at risk of a breach |
| Encryption | No | Encryption is not currently used; implementing it would improve confidentiality of sensitive information |
| Password management system | No | There is no password management system currently in place; implementing this control would improve the IT department/other employee productivity in the case of password issues | 

### Physical Controls
| Control Name | Does Botium Toys currently have this control in place? (Yes or No) | Explanation/Reasoning |
| --- | --- | --- |
| Closed-circuit television (CCTV) surveillance | Yes | CCTV is installed and functioning at the physical location | 
| Locks | Yes | The store's location has physical locks to protect from break-ins |
| Fire detection and prevention (fire alarm, sprinkler system, etc.) | Yes | There is a functioning fire detection and prevention system |

Compliance checklist
====================

To review compliance regulations and standards, read the [controls, frameworks, and compliance](https://www.coursera.org/learn/foundations-of-cybersecurity/supplement/xu4pr/controls-frameworks-and-compliance) document.

Does Botium Toys currently adhere to this compliance best practice?

### Payment Card Industry Data Security Standard (PCI DSS)
| Yes/No | Best Practice | Explanation |
| --- | --- | --- |
| No | Only authorized users have access to customers’ credit card information. | All employees have access to internal data | 
| No | Credit card information is accepted, processed, transmitted, and stored internally, in a secure environment. | At Botium toys, Credit card information is not encrypted and all employees currently have access to internal data, including customers’ credit card information. This presents higher risks for data breaches. |
| No | Implement data encryption procedures to better secure credit card transaction touchpoints and data. | Botium toys does not use encryption. They lack confidentiality for their users |
| No | Adopt secure password management policies. | No password management system is in place. |



   

-   Payment Card Industry Data Security Standard (PCI DSS)

    - PCI DSS is an international security standard meant to ensure that organizations storing, accepting, processing, and transmitting credit card information do so in a secure environment. 

       - Botium Toys must adhere to PCI DSS as it accepts payments online and in person and They also store and process customer credit cards on an international scale. Its requirements and compliance need to be taken seriously based on possible consequences. The consequences of not complying with this standard are more severe in impact: Monetary fines monthly (ranging from 5,000-100,000 USD), costs of forensic audits upon a data breach, payment brand restrictions, damage to brand reputation, and possibility of lawsuit costs in the event of data breaches. 


-   System and Organizations Controls (SOC type 1, SOC type 2)
   - The SOC1 and SOC2 are a series of reports that focus on an organization's user access policies at different organizational levels. They are used to assess an organization's financial compliance and levels of risk. They also cover confidentiality, privacy, integrity, availability, security, and overall data safety. Control failures in these areas can lead to fraud.

      - Botium Toys needs to establish and maintain appropriate user access for internal and external (third-party vendor) personnel to mitigate risk and ensure data safety.
      - Both of these standards evaluate the effectiveness of a company's internal controls. While SOC1 I focused on financial reporting controls, SOC2 is concerned with information security controls, including customer data safety. 
----------------










   


**Summary/Recommendations:**

It is recommended that the critical findings relating to compliance with PCI and GDPR be promptly addressed as Botium Toys accepts online payments is expanding to offer services and handle the data of customers abroad including the European Union. SOC1 and SOC2 guidance related to user access policies should be used to align to the audit goal to adapt to the concept of least permissions to develop the policies and procedures needed to be compliant.

Disaster recovery plans and backups are recommended as they will support business continuity in the event of an incident occuring ranging from a physical disaster such as a fire, or worse case scenario of a cyber attack or technical issue impacting business productivity  as a part of a data and system resilience strategy. A method of fire detection and prevention systems is worth consideration for protecting against physical attacks.

Integrating an IDS and AV software into current systems will give the ability to assist with intrusion detection and spot and mitigate potential risks while taking into account the existing legacy systems that need manual monitoring and intervention. 

To secure assets at Botium Toys' phyiscal location, locks and CCTV should be used to secure physical assets and to monitor for potential threats. Having a time-controlled safe, adequate lighting, and signage indicating alarm service provider will further improve Botium Toys' security posture.
   
# Conclusion  <a name="conclusion">
 This concludes my mock security audit writeup, I hope you found it useful and enlightening as I have. If there is any constructive feedback or  suggestions to improve and include, just let me know. 
 

**What I learned**: 
   
   The part I struggled with mostly was using much details in my findings in the stakeholder's memorandum. I learned and spent alot of time on this to be more concisely and to the point. I learned to use a list, have my writing proofread and ensure I didnt repeat anything and to filter out information.
   
   I also some trouble initially in explaining how the System and Organizations Controls standard relates to organizational user access policies, confidentiality, privacy, integrity, availability, security, and overall data safety and levels of risks, not just financial compliance while conducting the audit.
