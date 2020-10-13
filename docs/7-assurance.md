---
layout: default
title: 7 Assurance  
nav_order: 80 
---

# 7 Assurance
{: .no_toc }

1. TOC
{:toc}

Information assurance is the degree of confidence one has that security measures protect and defend information and systems by ensuring their availability, integrity, authentication, confidentiality, and non-repudiation. These measures include providing for restoration of systems by incorporating protection, detection, and reaction capabilities.

Assurance is not, however, an absolute guarantee that the measures will work as intended. Understanding this distinction is crucial as quantifying the security of a system can be daunting. Nevertheless, it is something individuals expect and obtain, often without realizing it. For example, an individual may routinely receive product recommendations from colleagues but may not consider such recommendations as providing assurance.

This chapter discusses planning for assurance and presents two categories of assurance methods and tools: the design and subsequent implementation of assurance and operational assurance (further categorized into audits and monitoring). The division between the two categories can be ambiguous at times as there is significant overlap. While such issues as configuration management or audits are discussed under operational assurance, they may also be vital during a system’s development. The discussion tends to focus more on technical issues during design and implementation assurance and is a mixture of management, operational, and technical issues under operational assurance.

## 7.1 Authorization

Authorization is the official management decision to authorize the operation of a system. The authorizing official (a senior organizational executive) explicitly accepts the risk of operating the system to organizational operations (e.g., mission, functions, image, reputation), organizational assets, individuals, other organizations, and the Nation based on the implementation of an agreed-upon set of security and privacy controls. There is a need for a collaborative relationship between the authorizing official and the SAOP. OMB A-130 gives SAOPs review and approval of privacy plans prior to authorization, and review of authorization packages for systems with PII. Therefore, before making risk determination and acceptance decisions, the authorizing official communicates with the SAOP to address any privacy-related concerns before the final authorization decision is made. The authorization process requires managers and technical staff to work together to find practical, cost-effective solutions given security needs, technical and operational constraints, requirements of other system quality attributes such as privacy, and mission or business requirements.

To facilitate sound risk-based decision making, decisions are based on reliable and current information about the implementation and effectiveness of both technical and nontechnical
safeguards. These include:

* Technical features (Do they operate as intended?);
* Operational policies and practices (Is the system operated according to stated policies and practices?);
* Overall security (Are there threats that the safeguards do not address?); and
* Remaining risk (Is residual risk(8) at an acceptable level?)
The Authorizing Official is responsible for authorizing the system before it is allowed to operate and have a plan in place for how that system will be continuously monitored.

`(8) Residual Risk is the portion of risk remaining after security measures have been applied.`

### 7.1.1 Authorization and Assurance

Assurance is an integral element in making the decision to authorize a system to operate. Assurance addresses whether the technical measures and procedures are operating according to a set of security requirements and specifications as well as general quality principles.

The authorizing official makes the final decision on how much and what types of assurance are needed for a system. In order to make a sound decision, the authorizing official considers the system categorization/impact level and reviews the results of risk assessments. The authorizing official analyzes the benefits and disadvantages of the cost of assurance, cost of controls, and risks to the organization. When the authorization process is complete, it is the responsibility of the authorizing official to accept the residual risk in the system.

7.1.2 Authorization of Products to Operate in a Similar Situation
The authorization of another product or system to operate in a similar situation can be used to provide some assurance (e.g., reciprocity). However, it is important to realize that an authorization is specific to the environment and the system. Since authorization balances risks and advantages, the same product may be appropriately authorized for one environment but not for another, even by the same authorizing official. For instance, an authorizing official might approve the use of cloud storage for research data but not for human resource data under the purview of the same system.

## 7.2 Security Engineering

The size and complexity of today’s systems make building a trustworthy system a priority. Systems security engineering provides an elementary approach for building dependable systems in today’s complex computing environment. For more information on security engineering, refer
to NIST SP 800-160.

### 7.2.1 Planning and Assurance

For new systems or for system upgrades, assurance requirements begin during the planning phase of the system life cycle. Planning for assurance as part of system requirements also is practical and helps authorizing officials make cost-effective decisions when building a system or when purchasing the components/equipment required to provide assurance for an older system.

### 7.2.2 Design and Implementation Assurance

Design and implementation assurance addresses a system’s design as well as whether the features of a system, application, or component meet security requirements and specifications. Design and implementation assurance examines system design, development, and installation and is usually associated with the development/acquisition and implementation phase of the system life cycle. However, it may also be considered throughout the life cycle as the system is modified.

#### 7.2.2.1 Use of Advanced or Trusted Development
In the development of both commercial off-the-shelf (COTS) products and customized systems, the use of advanced or trusted system architectures, development methodologies, or software engineering techniques can provide assurance. Examples include security design and development reviews, formal modeling, mathematical proofs, ISO 9000 quality techniques, ISO 15288 (a systems security engineering standard), or the use of security architecture concepts, such as a trusted computing base (TCB).

Since assurance in information technology products cannot be fully guaranteed, there are recognized evaluation processes available to establish a level of confidence that the security functionality of these IT products and the assurance measures applied to these IT products meet certain requirements. The Common Criteria (CC) allows for the comparability of results between independent evaluations. The CC is useful as a guide for the development, evaluation, and procurement of IT products with security functionality. For more information about the CC, see http://www.commoncriteriaportal.org or https://buildsecurityin.us-cert.gov/articles/best-
practices/requirements-engineering/the-common-criteria.

#### 7.2.2.2 Use of Reliable Architecture
Some system architectures are intrinsically more reliable, such as systems that use fault-tolerance, redundancy, shadowing, or redundant array of independent disks (RAID) features.
These examples are primarily associated with system availability.

#### 7.2.2.3 Use of Reliable Security
One factor in reliable security is the concept of ease of safe use, which postulates that a system that is easier to secure is more likely to actually be secure. Security features may be more likely utilized when the initial system defaults to the "most secure" option. In addition, a system's security may be deemed more reliable if it refrains from using new technology that has yet to be tested in the “real” world (often called “bleeding-edge” technology). Conversely, a system that uses older, well-tested software may be less likely to contain bugs.

#### 7.2.2.4 Evaluations
A product evaluation normally includes testing. Evaluations can be performed by many types of organizations, including: domestic and foreign government agencies; independent organizations such as trade and professional organizations; other vendors or commercial groups; or individual users or user consortia. Product reviews in trade literature are a form of evaluation, as are more formal reviews made against specific criteria. Important factors to consider when using valuations are the degree of independence of the evaluating group, whether the evaluation criteria reflect needed security features, the rigor of the testing, the testing environment, the age of the evaluation, the competence of the evaluating organization, and the limitations placed on the evaluations by the evaluating group (e.g., assumptions about the threat or operating environment).

#### 7.2.2.5 Assurance Documentation
The ability to describe security requirements and how they were met can reflect the degree to which a system or product designer understands applicable security issues. Without a comprehensive understanding of the requirements, it is unlikely that the designer will be able to meet them.

Assurance documentation can address the security for a system or for specific components. System-level documentation describes the system's security requirements and how they have been implemented, including interrelationships among applications, the operating system, or networks. System-level documentation addresses more than just the operating system, the security system, and applications; it describes the system as integrated and implemented in a particular environment. Component documentation will generally be an off-the-shelf product, whereas the system designer or implementer will typically develop system documentation.

#### 7.2.2.6 Warranties, Integrity Statements, and Liabilities
Warranties are an additional source of assurance. A manufacturer, producer, system developer, or integrator that is willing to correct errors within certain time frames or by the next release, gives the system manager a sense of commitment to the product and also speaks to the product’s quality. An integrity statement is a formal declaration or certification of the product. It can be augmented by a promise to (a) fix the item (i.e., warranty) or (b) pay for losses (i.e., liability) if the product does not conform to the integrity statement.

#### 7.2.2.7 Manufacturer’s Published Assertions
The published assertion or formal declarations of a manufacturer or developer provide a limited amount of assurance based on reputation. When there is a contract in place, reputation alone will
be insufficient given the legal liabilities imposed on the manufacturer.

#### 7.2.2.8 Distribution Assurance
It is often important to know that software has arrived unmodified, especially if it is distributed electronically. In such cases, check bits or digital signatures can provide high assurance that code has not been modified. Anti-virus software can be used to check software that comes from sources with unknown reliability (e.g., internet forum).

## 7.3 Operational Assurance

Design and implementation assurance addresses the quality of security features built into systems. Operational assurance addresses whether the system's technical features are being bypassed or have vulnerabilities and whether required procedures are being followed. It does not address changes in the system's security requirements, which could be caused by changes to the system and its operating or threat environment. (These changes are addressed in section 10.15). 
Security tends to degrade during the operational phase of the system life cycle. System users and operators discover new ways to intentionally or unintentionally bypass or subvert security, especially if there is a perception that bypassing security improves functionality or that there will be no repercussions to them or their systems. Strict adherence to procedures is rare. Policy becomes outdated, and errors in the system's administration commonly occur.

Organizations use three basic methods to maintain operational assurance:

* System assessment. An event or a continuous process to evaluate security. An assessment can vary widely in scope: it may examine an entire system for the purpose of authorization or it may investigate a single anomalous event;
* System audit. An independent review and examination of records and activities to assess the adequacy of system controls and to ensure compliance with established policies and operational procedures; and
* System monitoring. A process for maintaining ongoing awareness of information security, vulnerabilities, and threats to support organizational risk management decisions.

In general, the more "real-time" an activity is, the more it falls into the category of monitoring. This distinction can create some unnecessary linguistic hairsplitting, especially concerning system-generated audit trails. Daily or weekly reviewing of the audit trail for unauthorized access attempts is generally considered to be monitoring, while a historical review of several months' worth of the trail (e.g., tracing the actions of a specific user) is generally considered an audit. Overall, though, the specific terms applied to assurance-related activities are much less important than the real work of actually maintaining operational assurance.

### 7.3.1 Security and Privacy Control Assessments

Assessments can address the quality of the system as built, implemented, or operated. Assessments can be performed throughout the development cycle, after system installation, and throughout its operational phase. Assessment methods include interviews, examinations, and testing. Some common testing techniques feature functional testing (to see if a given function works according to its requirements) or penetration testing (to see if security can be bypassed). These techniques can range from trying several test cases to in-depth studies using metrics, automated tools, or multiple detailed test cases. See NIST SP 800-53A for assessment guidance.

### 7.3.2 Audit Methods and Tools

An audit conducted to support operational assurance examines whether the system is meeting stated or implied security requirements as well as system and organization policies. Some audits also examine whether security requirements are appropriate, though this is outside of the scope of operational assurance. (See section 10.15.) Less formal audits are often called security reviews.

Audits can be self-administered or independent—meaning they can be administered internally or externally. Both types can provide excellent information about technical, procedural, managerial, or other aspects of security. The essential difference between a self-audit and an independent audit is objectivity. Reviews conducted by system management staff—often called self-audits/assessments—present an inherent conflict of interest. The system management staff may have little incentive to report that the system was poorly designed or is carelessly operated. On the other hand, they may be motivated by a strong desire to improve the security of their system. In addition, they are knowledgeable about the system and may be able to find hidden problems.

The independent auditor, by contrast, has no professional stake in the system. A person who performs an independent audit is organizationally independent and free from personal or external constraints that may impair their independence. An independent audit may be performed by a professional audit staff in accordance with generally accepted auditing standards.

There are numerous methods and tools that can be used to audit, some of which are described
here.

#### 7.3.2.1 Automated Tools
Even for small multiuser systems, manually reviewing security features may require significant resources. Automated tools make it feasible to review even large systems for a variety of security flaws.

There are two types of automated tools: (1) active tools, which find vulnerabilities by trying to exploit them; and (2) passive tests, which only examine the system and infer the existence of problems from the state of the system.

Automated tools can be used to help uncover a variety of threats and vulnerabilities, such as improper access controls or access control configurations, weak passwords, lack of system software integrity, or not applying all relevant software updates and patches. These tools are often very successful at finding vulnerabilities and are sometimes used by hackers to break into systems. Utilizing these tools gives system administrators an advantage. Many of the tools are simple to use. However, some programs (e.g., access-control auditing tools for large mainframe
systems) require specialized skill to use and interpret.

#### 7.3.2.2 Internal Controls Audit
An auditor can review controls in place and determine whether they are effective. The auditor will often analyze both system and non-system based controls. Techniques used include inquiry, observation, and testing of both the data and the controls themselves. The audit can also detect illegal acts, errors, irregularities, or a lack of compliance with laws and regulations. System Security Plans and penetration testing, discussed below, may be used.

#### 7.3.2.3 Using the System Security Plan (SSP)
The system security plan provides implementation details against which the system can be audited. This plan, discussed in section 10.12, outlines the major security considerations for a system, including management, operational, and technical issues. One advantage of using a system security plan is that it reflects the unique security environment of the system, rather than a generic list of controls. Security control sets can be developed, including national or organizational security policies and practices (often referred to as baselines). The SSP is also used for historical purposes and, in such instances where a system interconnection exists, may need to be shared with other organizations.

Baselines are the starting point of the security control selection process for systems. Three security control baselines have been identified corresponding to the low-impact, moderate-impact, and high-impact systems using the high-water mark(9) defined in FIPS 200 to provide an initial set of security controls for each impact level. Once a security control baseline is selected, organizations use the tailoring guidance in NIST SP 800-53 to remove controls from the baseline (with a justification based on risk) or to add compensating or supplemental controls to strengthen the security posture of a specific system.

`(9) High Water Mark—For a system, the potential impact values assigned to the respective security objectives (confidentiality, integrity, availability) shall be the highest values from among those security categories that have been determined for each type of information resident on the system (retrieved from FIPS 199).`

Care needs to be taken to ensure that deviations from the baseline are based on an assessment of the associated risk as the changes may be appropriate for the system's particular environment or technical constraints.

#### 7.3.2.4 Penetration Testing
Penetration testing can use many methods to attempt a system break-in. In addition to using active automated tools as described above, penetration testing can be done "manually." The most useful type of penetration testing involves the use of methods that might be used against the system. For hosts on the Internet, this would certainly include automated tools. For many systems, lax procedures or a lack of internal controls on applications are common vulnerabilities that penetration testing can target. Another method is social engineering, which involves deceiving users or administrators into divulging information about systems, including their
passwords.

### 7.3.3 Monitoring Methods and Tools

Security monitoring is an ongoing activity that seeks out vulnerabilities and security problems. Many of the methods are similar to those used for audits but are done more regularly or, for some automated tools, in real time.

#### 7.3.3.1 Review of System Logs
A periodic review or use of automated tools to analyze system-generated logs can detect security problems, including attempts to exceed access authority or gain system access during unusual
hours (see section 10.15).

#### 7.3.3.2 Automated Tools
Several types of automated tools monitor a system for security problems. Some examples follow:

* Malicious code scanners are a popular means of checking for malicious code infections. These programs test for the presence of malicious code in executable program files;

* Checksum functions generate a mathematical value used to detect changes in the data based on the contents of a file. When the integrity of the file is being verified, the checksum is generated on the current file and compared with the previously generated value. If the two values are equal, the integrity of the file is verified. Running a checksum on programs can detect malicious code, accidental changes to files, and other changes to files. However, they may be subject to covert replacement by a system intruder. A digital signature, which guards against more than just accidental changes to files and are vastly superior to a checksum, can also be used to verify the integrity of a file;

* Password strength checkers test passwords against a dictionary (either a "regular" dictionary or a specialized one with easy-to-guess passwords, or both) and also check if passwords are common permutations of the user ID. Examples of special dictionary entries could be the names of regional sports teams and stars. Common permutations could be the user ID spelled backwards or the addition of numbers or special characters after common passwords;

* Integrity verification programs can be used by applications to look for evidence of data tampering, errors, and omissions. Techniques include consistency and reasonableness checks and validation during data entry and processing. These techniques can check data elements—as input or as processed—against expected values or ranges of values; analyze transactions for proper flow, sequencing, and authorization; or examine data elements for expected relationships. Integrity verification programs comprise a crucial set of processes meant to assure individuals that inappropriate actions, whether accidental or intentional, will be caught. Many integrity verification programs rely on logging individual user activities;

* Host-based intrusion detection systems analyze the system audit trail for activity that could represent unauthorized activity, particularly logons, connections, operating systems calls, and various command parameters. Intrusion detection is covered in sections 10.1 and 10.3; and

* System performance monitoring analyzes system performance logs in real time to look for availability problems, including active attacks, system and network slowdowns, and crashes.

#### 7.3.3.3 Configuration Management
Configuration management provides assurance that the system in operation has been configured to organizational needs and standards, that any changes to be made are reviewed for security implications, and that such changes have been approved by management prior to implementation. Configuration management can be used to help ensure that changes take place in an identifiable and controlled environment and that they do not unintentionally harm any of the system's properties, including its security. Some organizations, particularly those with very large systems (e.g., the Federal Government), use a configuration control board for configuration management. When such a board exists, it is crucial for an information security expert to participate.

Changes to the system can have security implications. Such changes may introduce or mitigate
vulnerabilities and may require updating the contingency plan, risk analysis, or authorization.
For more details on configuration management, see section 10.5.

#### 7.3.3.4 Trade Literature/Publications/Electronic News
In addition to monitoring the system, it is useful to monitor external sources for information. Such sources as trade literature, both printed and electronic, have information about security
vulnerabilities, patches, and other areas that impact security. The Forum of Incident Response Teams (FIRST) has an electronic mailing list that receives information on threats, vulnerabilities, and patches. The National Vulnerability Database (NVD) is a repository of standards-based vulnerability management data represented using the Security Content Automation Protocol (SCAP). This data enables automation of vulnerability management, security measurement, and compliance. NVD includes databases of security checklists, security-related software flaws, misconfigurations, product names, and impact metrics. The United States Computer Emergency Readiness Team (US-CERT), a DHS component, responds to major incidents, analyzes threats, and exchanges critical cybersecurity information with trusted partners around the world. Also, Information Sharing and Analysis Centers (ISACs) communicate critical sector-specific information about physical, cyber threats, and mitigation in order to maintain sector-wide situational awareness.

## 7.4 Interdependencies

Assurance is an issue for every control and safeguard discussed in this publication. One important point to reemphasize here is that assurance is not only for technical controls, but for operational controls as well. Although this chapter focused on systems assurance, it is also important to have assurance that management controls are working properly. Are user IDs and access privileges kept up to date? Has the contingency plan been tested? Can the audit trail be tampered with? Is the security program effective? Are policies understood and followed? As noted in the introduction to this chapter, the need for assurance is more widespread than individuals often realize.

Assurance is closely linked to planning for security in the system life cycle. Systems can be
designed to facilitate various kinds of testing against specified security requirements. By
planning for such testing early in the process, costs can be reduced. Some kinds of assurance
cannot be obtained without proper planning.

## 7.5 Cost Considerations

There are many methods of obtaining assurance that security features work as anticipated. Since assurance methods tend to be qualitative rather than quantitative, they will need to be evaluated. Assurance can also be quite expensive, especially if extensive testing is done. It is useful to evaluate the amount of assurance received for the cost to make a best-value decision. In general, personnel costs drive up the cost of assurance. Automated tools are generally limited to addressing specific problems, but they tend to be less expensive.

