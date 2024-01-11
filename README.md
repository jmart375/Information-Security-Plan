![download](https://github.com/jmart375/Information-Security-Plan/assets/91294710/5dc2fb48-4dfb-4d19-94e9-d9fab186370c)
# Information Security Plan - Case Study "Acme Company"

## Table of Contents
1. [Introduction](#introduction)
2. [Scope](#scope)
3. [Organization of Information Security](#Organization-of-Information-Security)
   - 3.1 [Risk Management](#Risk-Management)
   - 3.2 [Access Control](#Access-Control)
   - 3.3 [Incident Management](#incident-Management)
   - 3.4 [Business Continuity](#Business-Continuity)
   - 3.5 [Compliance](#Compliance)
4. [Accountability of Assets](#Accountability-of-Assets)
5. [Information Security Classification](#Information-Security-Classifcation)
   - 5.1 [Confidential](#Confidential)
   - 5.2 [Internal/Private](#Internal/Private)
   - 5.3 [Public](#Public)
6. [Why are Identity and access management (IAM) important?]
7. [Why Do You Need IAM?](#Why-Do-You-Need-IAM?)
8. [Identity and Access Management Policy](#physical-security)
9. [Network Management & Security](#security-awareness-program)
10. [Operations Management](#review-and-updates)
11. [Security Monitoring](#Security-Monitoring)
12. [Data Storage](#Data-Storage)
13. [Change Control](#Change-Control)
14. [System Development Life Cycle and Mainteance](#System-Development-Life-Cycle)
15. [Threat Management](#Threat-Management)
16. [Incident Management](#Incident-Management)
17. [Business Continuity](#Business-Continuity)
## Introduction
This document outlines the information security plan for "Acme Company". The purpose of this plan is to safeguard the confidentiality, integrity, and availability of information assets.

## Scope
The information security plan applies to all employees, contractors, and third-party entities with access to Acme Company's information systems and data.The handling of information is an essential aspect of most business operations, including those of ACME. Information is often considered a valuable asset that organizations need to manage effectively to support their decision-making processes, improve efficiency, and gain a competitive advantage. As such, information handling is typically a critical component of an organization's overall business strategy. With the increasing volume of information being generated and processed by organizations, it is important to have a well-organized information handling system in place. This system should include measures to ensure information security, accountability of assets, and proper classification of information based on its sensitivity. The following will deep into ACME's information handling practices, examining three critical components in depth.

## Organization of Information Security
The organization of information security involves developing a framework for managing and protecting information assets. This framework should address the following areas: 
### Risk Management:
- Risk management: Identifying and assessing the risks to information assets and implementing controls to mitigate those risks.
- Access control: Ensuring that only authorized individuals have access to information assets.
- Incident management: Developing procedures to respond to security incidents and breaches. 
- Business continuity: Ensuring that critical information systems and processes are available and can be recovered in the event of a disruption.
- Compliance: Ensuring that information handling practices comply with legal and regulatory requirements. 

The organization of information security should be guided by policies, procedures, and controls that are developed and implemented with the involvement of all relevant stakeholders. This involves regular training and awareness campaigns to ensure that all employees understand their roles and responsibilities when it comes to information security. 
### Accountability of Assets
Accountability of assets for ACME involves tracking the movement and use of information assets. This includes identifying who has access to information, what they are doing with it, and when and where it is being used. Accountability is important for several reasons: 
- It allows organizations to detect and prevent unauthorized access or use of information assets.
- It provides a record of who accessed information, which can be useful in investigations or audits. It helps organizations identify areas where information handling processes can be improved.
- To ensure accountability of assets, organizations should develop and implement procedures for the collection, use, and disposal of information. This involves maintaining accurate records of information handling activities, including the use of information security technologies such as encryption, access control, and audit logs. It also involves regular monitoring of information handling activities to identify potential security incidents or breaches.

## Information Security Classification
At ACME Information security classification involves categorizing information based on its sensitivity. This classification helps organizations determine the appropriate level of protection for each type of information. Information can be classified into three categories:
### Confidential:
- Information that is sensitive and should be protected from unauthorized access, use, or disclosure. Examples include financial data, intellectual property, and personal information. 
### Internal/ Private:
- Information that is not publicly available and should be restricted to authorized personnel within an organization. Examples include employee records and internal memos.
### Public: 
- Information that is available to the general public and does not require any special protection. Examples include press releases and marketing materials.

The classification of information helps ACME to determine the appropriate security controls to apply to each type of information. For example, confidential information may require encryption and access control, while public information may only require basic access control measures. 
Effective information handling is critical for ensuring the confidentiality, integrity, and availability of information. This involves the organization of information security, accountability of assets, and the proper classification of information based on its sensitivity. Organizations must implement policies, procedures, and controls to ensure that information is collected, used, and disposed of securely. By following these best practices, organizations can better protect their information assets and minimize the risk of security incidents or breaches.


## Why are Identity and access management (IAM) important?
Identity and access management, or IAM, is the security discipline that makes it possible for the proper entities (people or software) to use the right resources (applications or data) when they need to, without interference, using the computers they want to use. Identity and access management is the set of software and policies that assigns a unique identifier to both people (employees/contractors) and software services. This is important as you want to limit access to specific files and resources. For example, uniqueness is crucial as you would like to avoid your new employee or contractor mirroring the permissions of your lead systems engineer, who is trusted and potentially has the keys to managing and operating your infrastructure. This allows us to authenticate specific users with specific resources and limit others with minimal permissions, like external customers looking at your furniture or the instructions on assembling the furniture. 

## Why Do You Need IAM?
As our digital lives evolve and we depend more on technology, the need for Identity and access management becomes increasingly important. Access privileges are based on policy; it helps ensure access is appropriately assigned. Authenticating and managing access is easier even as it facilitates maintaining data integrity, providing data when required for audits, and complying with government regulations. With an Identity and access management solution implemented, ACME Co. can and will avoid chain custody issues, and data access permissions. 

We recommend deploying an Identity and access management solution to help centralize user account predation and policy, policy enforcement, and multifactor authentication. The last one is significant as ACME Co. mentioned that 50 employees work from home, with an additional 30 employees coming on board within the next six months. This portion of Identity and access management will allow us to protect both company assets and personal employee access that may be used to gain access to the network. With the expansion of working from home, many employers are leveraging the bring your own device “BYOD.” Our Information Security Plan will allow us to empower our workforce to use any available computer, phone, or tablet with access to the internet to reach back to our office and have access to our resources like Office 365 and ServiceNow. 

## Identity and Access Management Policy
To successfully deploy Identity and access management, we need to build policies that help protect AMCE Co. Some policies include password requirements, so employees aren't using easily guessable passwords. Segregation of duties policies forces us to limit someone doing data entry to someone doing security audits. With policies like these created and enforced by the corporation, we can build a more secure information system.

Here are a series of recommendations that go hand in hand with the ISP that the IT team is proposing the CEO and the executives at ACME Company implement. Below is a list of best practices and technologies we believe fit ACME’s needs. This includes network management and security, operations management, and a system development life cycle.


## Network Management & Security
The team and I believe network management will help ensure ACME Company’s IT infrastructure is up and running. The availability of the network must be a top priority, especially since the company continues to grow. The network must always be available to provide access to data and resources. This would require ACME’s new cybersecurity program to proactively monitor and maintain its network in order to avoid issues that may cause downtime or interruptions. Network management will also safeguard reliability so that personnel on-premises and off-premises have their data and resources performing in a timely and consistent manner. It is essential that ACME rely on an effective network to operate and succeed. 

Network security is also critical because it ensures the protection of ACME’s data. This means implementing a range of security measures to protect against attackers and potential threats. We highly suggest ACME consider security controls such as firewalls, intrusion detection systems, and antivirus software. Fire walls and Intrusion Prevention Systems, for example, will prevent denial of service attacks and traffic that threatens systems within ACME Company. By ensuring the security of the network, ACME can protect sensitive data from theft or damage. 

## Operations Management
Operations management refers to implementing appropriate controls and protections on hardware, software, and resources (Knowles, 2022). It involves maintaining appropriate auditing, monitoring, and evaluating system threats and vulnerabilities. With employees potentially working remotely on unsecured networks and security protocols, ACME has a responsibility of keeping architectures and systems secure and compliant. Proper operations management safeguards all of ACME’s computing resources from loss or compromise, including main storage, storage media, communications software and hardware, processing equipment, and printers. 

## Security Monitoring
It is important that ACME implements security monitoring into its information security strategy. Security monitoring allows organizations to monitor network traffic, system logs, and other data so they can quickly identify any suspicious activity and ultimately take the necessary steps to mitigate the threats before causing more harm (Sanders & Smith, 2022). It helps detect and prevent incidents like unauthorized access and data breaches. ACME can also benefit greatly because it will help ACME Company meet compliance requirements and regulatory standards. There are several effective tools that can offer security monitoring and help identify patterns or security threats in data, such as intrusion detection systems and security information and event management (SIEM).

## Data Storage
The team believes securely storing ACME’s data is important for ACME’s continued success. Depending on how data is stored, it can have a profound impact on its security. Storage is the process of managing an organization’s data in a secure and reliable manner (Sheldon & Posey, 2022). Employees of ACME are urged to use a comprehensive data storage strategy, that includes both physical and virtual storage solutions. Physical solutions include on-premises servers and data centers. Virtual storage solutions, like a cloud-based platform, must be equipped with advanced encryption and authentication procedures. 

## Change Control
Change control is another suggestion we believe ACME will benefit from. This refers to the process of managing and documenting system changes (Young, 2021). To ensure that changes are documented, we believe a series of steps must be followed such as making sure changes are properly documented, reviewed, and approved. This will allow the company to maintain a clear record of changes and allow us to address any concerns that may arise, like unauthorized alteration and errors. This practice will also assist us in categorizing and prioritizing all requests from different departments that request a need for change in a controlled manner.

## System Development Life Cycle and Maintenance
It is the overall process of developing, implementing, and retiring information systems (Freeman, 2022). There are many SDLC methodologies that can be used by an organization to effectively develop an information system. SDLC is a methodology that ACME, more specifically the IT department, can use to design, develop, and maintain systems, especially as ACME continues to expand. It is a series of stages that ensure the delivery of high-quality systems that meet the needs of the company and its users. Security must be considered at all stages of the life cycle of an information system in order to: 1) protect sensitive information throughout its life cycle, 2) prevent new risks, and 3) ensure proper removal of data when the system is ultimately retired.
To ensure the ACME organization will thrive and recover from a threat or incident, there must be an effective way to manage each process to help prevent threats or respond when an incident occurs.  Along with managing the two processes, a business plan must be in effect for ACME to continue operation in the event of an emergency or threat. Since threats can be a broad range they can be grouped as natural disasters, system problems, cyber-attacks, and human-caused disasters.  

## Threat Management
Threat management is designed to proactively mitigate or prevent exploits by addressing them quickly and effectively to help reduce the chances of exploits. How will this help ACME? 
Five key steps are recommended which are: 
- Planning helps document asset inventory so anything valuable of ACME can be better managed from the risk of loss or damage.
- Discover helps monitor sources like the National Vulnerability Database (NVDB). Where information about known vulnerabilities is shared.
- Scanning ACME’s system regularly can help mitigate and address any issues ahead of time.
- Log and reporting can help documents to help rank any vulnerabilities from urgent to less time sensitive.
- Remediation is the next step in fixing any vulnerabilities found.
## Incident Management 
Incident Management helps manage security incidents by identifying them, responding to them, the recovery process, and reviewing information security incidents. This checklist of actions helps document thoroughly, so nothing is missed and to learn from security incidents. 

## Business Continuity
A business continuity plan will help ACME and your employees by taking appropriate steps when dealing with emergencies or threats promptly to resume normal operations. Since ACME is in New Orleans, which is hurricane-prone and a natural disaster it is vital to have an off-site backup server to help with the recovery process and minimize downtown. A proactive plan can help avoid and mitigate risks associated with a disruption of operations, and detailed steps to take before, during, and after an event to maintain the financial viability of an organization. 

![image](https://github.com/jmart375/Information-Security-Plan/assets/91294710/0f28c791-da8c-454b-b4e2-19285a03ee86)



The figure shown above describes the recovery time for an organization with a business continuity plan when implemented will improve the overall recovery time. So, ACME must establish a plan which will bring full operational capacity back sooner.    
