# Botium Toys Mock Security Audit

# Table of contents

1. [Introduction](#introduction)
2. [Scenario](#scenario)
3. [General Steps](#general-steps)
4. [Information Provided](#information-provided)
5. [Scope and goals of the audit](#goals)
6. [Internal Security Audit Workflow](#workflow)
7. [Controls Assessment](#control-assessment)
8. [Compliance Checklist](#compliance-checklist)
9. [Stakeholder Memorandum](#stakeholder-memo)
10. [Conclusion](#conclusion)

-------

# Introduction <a name="introduction">

For this project I will conduct a simplistic audit on Botium Toys, a fictitious toy company, that is a part of Google's <a href='https://www.coursera.org/google-certificates/cybersecurity-certificate'>Cybersecurity Professional Certificate</a> on Coursera in the  <a href='https://www.coursera.org/learn/manage-security-risks?specialization=cybersecurity-certificate'> Play It Safe: Manage Security Risks </a> Course.


# Scenario  <a name="scenario">
Botium Toys is a small U.S. business that develops and sells toys. The business has a single physical location. However, its online presence has grown, attracting customers in the U.S. and abroad. Their information technology (IT) department is under increasing pressure to support their online market worldwide. 

The manager of the IT department has decided that an internal IT audit needs to be conducted. She expresses concerns about not having a solidified plan of action to ensure business continuity and compliance, as the business grows. She believes an internal audit can help better secure the company’s infrastructure and help them identify and mitigate potential risks, threats, or vulnerabilities to critical assets. The manager is also interested in ensuring that they comply with regulations related to accepting online payments and conducting business in the European Union (E.U.).   

The IT manager starts by implementing the **National Institute of Standards and Technology Cybersecurity Framework** (NIST CSF), establishing an audit scope and goals, and completing a risk assessment. The goal of the audit is to provide an overview of the risks the company might experience due to the current state of its security posture. The IT manager wants to use the audit findings as evidence to obtain approval to expand his department.

## General Steps <a name="gneral-steps">

To ensure the efficiency of this audit, we will adhere to the five steps imparted by the Google CyberSecurity Certificate.

1. Establishing the scope and goals
2. Conducting a Risk Assessment
3. Conducting the Audit
4. Creating a Mitigation plan
5. Communicate Results to Stakeholders

Considering this is my very first security audit, I am still familiarizing myself with the Cybersecurity vernacular. In this specific project, I will only be focusing on step 3, having already been provided with steps 1 and 2.

------------------------

# Information Provided <a name="information-provided">

## Scope and Goals of the Audit  <a name="goals">

The scope and goal for Botium Toys’ internal IT audit are:

**Scope**
- This audit is defined as the entire security program at Botium
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

## Conducting the Audit


Controls Assessment  <a name="control-assessment">
===================


### Administrative Controls 
 Control Name | Is this control in place? (Yes or No) | Explanation/Reasoning |
| --- | --- | --- |
| Least Privilege | No | All employees have access to customer data; rights to access data must be limited to reduce the risk of a breach. |
| Disaster recovery plans | No | For the sake of business continuity, there must be disaster recovery plans in place. | 
| Password policies | No | Requirements with passwords are minimal within the organization. This allows threat actors to easily access secure data |
| Separation of duties | No | This needs to be implemented to reduce the possibility of fraud/access to critical data since the company CEO currently runs day-to-day operations |

### Technical Controls
| Control Name | Is this control in place? (Yes or No) | Explanation/Reasoning |
| --- | --- | --- |
| Firewall | Yes | The organization already has a firewall that blocks traffic based on an appropriately defined set of security rules | 
| Intrusion Detection System (IDS) | No | An IDS must be put in place to help identify possible intrusions by threat actors |
| Backups | No | Without this control, the business lacks business continuity because, in case of a breach, critical data could be lost |
| Antivirus Software | Yes | Antivirus software is installed and monitored regularly by the IT department |
| Manual monitoring, maintenance, and intervention for legacy systems | No | Necessary to identify threats risks, and vulnerabilities in the systems. The risk assessment indicates that these systems are monitored and maintained, but there is not a regular schedule in place for this task, and procedures/ policies related to intervention are unclear, which could place these systems at risk of a breach The risk assessment states that these systems are monitored and maintained, but there is not a regular schedule in place for this task, and procedures/ policies related to intervention are unclear, which could place these systems at risk of a breach |
| Encryption | No | Encryption is not currently used; implementing it would improve confidentiality of sensitive information |
| Password management system | No | There is no password management system currently in place; implementing this control would improve the IT department/other employee productivity in the case of password issues | 

### Physical Controls
| Control Name | Is this control in place? (Yes or No) | Explanation/Reasoning |
| --- | --- | --- |
| Closed-circuit television (CCTV) surveillance | Yes | CCTV is installed and functioning at the physical location | 
| Locks | Yes | The store's location has physical locks to protect from break-ins |
| Fire detection and prevention (fire alarm, sprinkler system, etc.) | Yes | There is a functioning fire detection and prevention system |

Compliance checklist
====================

To review compliance regulations and standards, read the [controls, frameworks, and compliance](https://www.coursera.org/learn/foundations-of-cybersecurity/supplement/xu4pr/controls-frameworks-and-compliance) document.

**Does Botium Toys currently adhere to this compliance best practice?**

### Payment Card Industry Data Security Standard (PCI DSS)
| Yes/No | Best Practice | Explanation |
| --- | --- | --- |
| No | Only authorized users have access to customers’ credit card information. | All employees have access to internal data | 
| No | Credit card information is accepted, processed, transmitted, and stored internally, in a secure environment. | At Botium toys, Credit card information is not encrypted and all employees currently have access to internal data, including customers’ credit card information. This presents higher risks for data breaches. |
| No | Implement data encryption procedures to better secure credit card transaction touchpoints and data. | Botium toys does not use encryption. They lack confidentiality for their users |
| No | Adopt secure password management policies. | No password management system is in place. |

### General Data Protection Regulation (GDPR)
| Yes/No | Best Practice | Explanation |
| --- | --- | --- |
| No | E.U. customers’ data is kept private/secured | Botium toys does not currently use encryption to ensure confidentiality for their users |
| Yes | There is a plan in place to notify E.U. customers within 72 hours if their data is compromised/there is a breach | There is that plan in place |
| No | Ensure data is properly classified and inventoried | Current assets have not been classified but have been inventoried/listed | 
| Yes | Enforce privacy policies, procedures, and processes to properly document and maintain data | Privacy policies, procedures, and processes have been developed and enforced among IT team members and other employees |

### System and Organizations Controls (SOC type 1, SOC type 2)
| Yes/No | Best Practice | Explanation |
| --- | --- | --- |
| No | User access policies are established | All employees have access to internally stored data | 
| No | Sensitive data (PII/SPII) is confidential/private | Botium toys does not have encryption, leaving PII/SPII vulnerable |
| Yes | Data integrity ensures the data is consistent, complete, accurate, and has been validated. | Data integrity is in place | 
| No | Data is available to individuals authorized to access it | Data is available to employees in the organization, however authorization needs to be limited to only indivuduals who need to access it for their department |


**Recommendations:**

To conclude Botium Toys' security stance and safeguard sensitive data, a range of controls should be implemented. These include Least Privilege, disaster recovery protocols, robust password policies, separation of duties, an Intrusion Detection System (IDS), continual management of legacy systems, encryption capabilities, and a proficient password management system.

To bridge compliance shortfalls, Botium Toys should enact essential controls like Least Privilege, separation of duties, and encryption. Additionally, the company should diligently categorize assets to pinpoint any supplementary controls necessary for enhancing security posture and fortifying the defense of sensitive data.


# Conclusion  <a name="conclusion">
 This concludes my mock security audit writeup, I hope you found it useful and enlightening as I have. If there is any constructive feedback or  suggestions to improve and include, just let me know. 
 

**What I learned**: 
   
I learned and spent alot of time on this to be more concisely and to the point. I learned to use a list, have my writing proofread and ensure I didnt repeat anything and to filter out information.
   
   I also some trouble initially in explaining how the System and Organizations Controls standard relates to organizational user access policies, confidentiality, privacy, integrity, availability, security, and overall data safety and levels of risks, not just financial compliance while conducting the audit.
