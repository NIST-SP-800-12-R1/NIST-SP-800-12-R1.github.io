---
layout: default
title: 1 Introduction 
nav_order: 20 
---

# 1 Introduction
{: .no_toc }

1. TOC
{:toc}

## 1.1 Purpose

This publication serves as a starting-point for those new to information security as well as those unfamiliar with NIST information security publications and guidelines. The intent of this special publication is to provide a high-level overview of information security principles by introducing related concepts and the security control families (as defined in NIST SP 800-53, Security and Privacy Controls for Federal Information Systems and Organizations) that organizations can leverage to effectively secure their systems(1) and information. To better understand the meaning and intent of the security control families described later, this publication begins by familiarizing the reader with various information security principles.

`(1) System is defined in SP 800-53 as any organized assembly of resources and procedures united and regulated by interaction or interdependence to accomplish a set of specific functions.`

After the introduction of these security principles, the publication provides detailed descriptions of multiple security control families as well as the benefits of each control family. The point is not to impose requirements on organizations, but to explore available techniques for applying a specific control family to an organization’s system and to explain the benefit(s) of employing the selected controls.

Since this publication provides an introduction to information security, detailed steps as to how security controls are implemented or how to check for security control effectiveness are not included. Rather, separate publications that may provide more detailed information about a specific topic will be noted as a reference.

## 1.2 Intended Audience

The target audience for this publication are those new to the information security principles and tenets needed to protect information and systems in a way that is commensurate with risk. This publication provides a basic foundation of concepts and ideas to any person tasked with or interested in understanding how to secure systems.

For that reason, this publication is a good resource for anyone seeking a better understanding of information security basics or a high-level view on the topic. The tips and techniques described in this publication may be applied to any type of information or system in any type of organization. While there may be differences in the way federal organizations, academia, and the private sector process, store, and disseminate information within their respective systems, the basic principles of information security are applicable to all.

## 1.3 Organization

This publication is organized as follows:

* Chapter 1 describes the purpose, target audience, important terms, the legal foundation for information security, and a list of NIST publications related to information security and information risk management.
* Chapter 2 lists eight major elements regarding information security.
* Chapter 3 outlines several roles, supporting roles, and the respective responsibilities attributed to those roles on providing information security to the organization.
* Chapter 4 introduces threats and vulnerabilities, distinguishes the difference between the two, and provides examples of different threat sources and events.
* Chapter 5 discusses information security policy and the differences between Program Policy, Issue-Specific Policy, and System-Specific Policy.
* Chapter 6 considers how to manage risk and briefly describes the six steps of the NIST Risk Management Framework (RMF).
* Chapter 7 focuses on information assurance and what measures can be taken to protect information and systems.
* Chapter 8 introduces system support and operations, which collectively function to run a system.
* Chapter 9 provides a brief overview of cryptography as well as several NIST 800-series Publications that contain additional, more detailed information on specific cryptographic technologies.
* Chapter 10 introduces the 20 information security and privacy control families.
* Appendix A provides a list of References.
* Appendix B provides a Glossary of terms used throughout the document.
* Appendix C provides a list of Acronyms and Abbreviations used throughout the document.

## 1.4 Important Terminology

The term Information System is defined by 44 U.S.C., Sec. 3502 as “a discrete set of information resources organized for the collection, processing, maintenance, use, sharing, dissemination, or disposition of information.”

For this publication, the term system is used in lieu of the term information system to reflect the broader applicability of information resources of any size or complexity, organized expressly for the collection, processing, use, sharing, dissemination, maintenance, or disposition of data or information. Some other key terms to be familiar with are:(2)

`(2) These terms and definitions were retrieved from CNSSI 4009, Committee on National Security Systems (CNSS) Glossary, dated April 6, 2015.`

- Information – (1) Facts or ideas, which can be represented (encoded) as various forms of data; (2) Knowledge (e.g., data, instructions) in any medium or form that can be communicated between system entities.
- Information Security – The protection of information and information systems from unauthorized access, use, disclosure, disruption, modification, or destruction in order to ensure confidentiality, integrity, and availability.
- Confidentiality – Preserving authorized restrictions on information access and disclosure, including means for protecting personal privacy and proprietary information.
- Integrity – Guarding against improper information modification or destruction and ensuring information non-repudiation and authenticity.
    - Data Integrity – The property that data has not been altered in an unauthorized manner. Data integrity covers data in storage, during processing, and while in transit.
    - System Integrity – The quality that a system has when it performs its intended function in an unimpaired manner, free from unauthorized manipulation of the system, whether intentional or accidental.
- Availability – Ensuring timely and reliable access to and use of information.
- Security Controls(3) – The management, operational, and technical controls (i.e., safeguards or countermeasures) prescribed for a system to protect the confidentiality, availability, and integrity of the system and its information.

`(3) In this document, the terms security controls, safeguards, security protections, and security measures have been used interchangeably.`

## 1.5 Legal Foundation for Federal Information Security Programs

Within the Federal Government, many laws and regulations mandate that federal organizations protect their systems, the information processed, stored, or transmitted by systems, and related technology resources (e.g., telecommunications). A sampling of these laws and regulations is listed below.

* The Computer Security Act of 1987 required agencies to identify sensitive systems, conduct computer security training, and develop computer security plans. The Computer Security Act of 1987 was superseded by the Federal Information Security Management Act of 2002 (FISMA), described below.
* The Federal Information Resource Management Regulation (FIRMR) was the primary regulation for the use, management, and acquisition of computer resources in the Federal Government. The law was abolished pursuant to the Information Technology Management Reform Act of 1996 (ITMRA), redesignated the Clinger-Cohen Act.
* The E-Government Act of 2002 is intended to enhance the management and promotion of electronic government services and processes by establishing a Federal Chief Information Officer (CIO) within the Office of Management and Budget (OMB), and by establishing a broad framework of measures that require the use of Internet-based information technology to enhance citizens’ access to government information, services, and to make improvements in the way the government operates..
* The Federal Information Security Management Act (FISMA) was enacted as part of the E-Government Act of 2002 to address specific information security needs, which include,but are not limited to, providing: a comprehensive framework for ensuring the effectiveness of information security controls over information resources that support federal operations and assets; and the development and maintenance of minimum controls required to protect federal information and systems (as written in SEC. 301 of Public Law 107-347).
* The Federal Information Security Modernization Act of 2014 was an amendment to FISMA that made several modifications to modernize federal security practices as well as promote and strengthen the use of continuous monitoring.
* OMB Circular A-130, Management of Federal Information Resources, requires that federal agencies establish information security and privacy programs containing specified elements.
* OMB Memoranda as applicable.

This is not a comprehensive list of laws and regulations related to federal systems. There are more specific requirements imposed on federal agencies depending on the type of information they store, process, and disseminate. Additionally, some existing laws that affect non-government organizations were not included on this list. Examples of these laws include: the Health Insurance Portability and Accountability Act (HIPAA), which requires protection of the privacy and security of health information; and the Sarbanes-Oxley (SOX) Act, which requires protection for the public from accounting errors and fraudulent practices in financial systems. Federal managers are responsible for familiarizing themselves and complying with applicable legal requirements. However, laws and regulations do not typically provide detailed instructions for protecting information. Instead, they specify broad, flexible requirements such as restricting the availability of personal data to authorized users. This publication provides guidance on developing an effective, overall information security approach to meet applicable laws or policies.

## 1.6 Related NIST Publications

When it comes to information security and risk management, there are a specific set of Federal Information Processing Standards (FIPS) and NIST Special Publications (SPs) that apply. They include:

* FIPS 199 – Standards for Security Categorization of Federal Information and Information Systems, lists standards for the categorization of information and systems, which in turn provides a common framework and understanding of expressing security in a way that promotes effective management and consistent reporting.
* FIPS 200 – Minimum Security Requirements for Federal Information and Information Systems, specifies minimum security requirements for information and systems that support the executive agencies of the Federal Government as well as a risk-based process for selecting the security controls necessary to satisfy the minimum security requirements.
* SP 800-18 – Guide for Developing Security Plans for Systems, describes the procedures for developing a system security plan, provides an overview of the security requirements of the system, and describes the controls in place or planned for meeting those requirements.
* SP 800-30 – Guide for Conducting Risk Assessments, provides guidance for conducting risk assessments of federal systems and organizations.
* SP 800-34 – Contingency Planning Guide for Federal Information Systems, assists organizations in understanding the purpose, process, and format of information system contingency plans (ISCPs) development with practical, real-world guidelines.
* SP 800-37 – Guide for Applying the Risk Management Framework to Systems: A Security Life Cycle Approach, provides guidelines for applying the Risk Management Framework to federal systems, including conducting the activities of security categorization, security control selection and implementation, security control assessment, system authorization, and security control monitoring.
* SP 800-39 – Managing Information Security Risk: Organization, Mission, and Information System View, provides guidelines to establish an integrated, organization-wide program for managing information security risk to organizational operations (e.g., mission, functions, image, and reputation), assets, individuals, other organizations, and the Nation resulting from the operation and use of federal systems.
* SP 800-53 – Security and Privacy Controls for Systems and Organizations, provides guidelines for selecting and specifying security controls for organizations and systems supporting the executive agencies of the Federal Government to meet the requirements of FIPS Publication 200.
* SP 800-53A – Assessing Security and Privacy Controls in Systems and Organizations: Building Effective Assessment Plans, provides (i) guidelines for building effective security assessment plans and privacy assessment plans; and (ii) a comprehensive set of procedures for assessing the effectiveness of security controls and privacy controls employed in systems and organizations supporting the executive agencies of the Federal Government.
* SP 800-60 – Guide for Mapping Types of Information and Information Systems to Security Categories, assists agencies in consistently mapping security impact levels to types of: (i) information (e.g., privacy, medical, proprietary, financial, contractor sensitive, trade secret, investigation); and (ii) systems (e.g., mission critical, mission support, administrative).
* SP 800-128 – Guide for Security-Focused Configuration Management of Information Systems, provides guidance for organizations responsible for managing and administrating the security of federal systems and associated environments of operation.
* SP 800-137 – Information Security Continuous Monitoring (ISCM) for Federal Information Systems and Organizations, assists organizations in the development of an ISCM strategy and the implementation of an ISCM program, which provide awareness of threats and vulnerabilities, visibility into organizational assets, and the effectiveness of deployed security controls.
