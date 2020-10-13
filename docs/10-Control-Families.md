---
layout: default
title: 10 Control Families  
nav_order: 110 
---

# 10 Control Families
{: .no_toc }

1. TOC
{:toc}

To ensure the protection of confidentiality, integrity, and availability, FIPS 200 specifies minimum security requirements in multiple security-related areas. The areas which are introduced below, represent a broad-based, balanced information security program that addresses the management, operational, and technical aspects of protecting federal information and systems.

The intent of this section is to provide a brief description of each security control family. Each family has a list of controls that address a specific security goal. To view the complete security control catalog and a description of all controls, refer to NIST SP 800-53.

## 10.1 Access Control (AC)

The requirements for using—and prohibitions against the use of—various system resources vary considerably from one system to another. For example, some information must be accessible to all users, some may be needed by several groups or departments, and some may be accessed by only a few individuals. While users must have access to specific information needed to perform their jobs, denial of access to non-job-related information may be required. It may also be important to control the kind of access that is permitted (e.g., the ability for the average user to execute, but not change, system programs). These types of access restrictions enforce policy and help ensure that unauthorized actions are not taken.

Access is the ability to make use of any system resource. Access control is the process of granting or denying specific requests to: 1) obtain and use information and related information processing services; and 2) enter specific physical facilities (e.g., federal buildings, military establishments, border crossing entrances). System-based access controls are called logical access controls. Logical access controls can prescribe not only who or what (in the case of a process) is to have access to a specific system resource, but also the type of access that is permitted. These controls may be built into the operating system, incorporated into applications programs or major utilities (e.g., database management systems, communications systems), or implemented through add-on security packages. Logical access controls may be implemented internally to the system being protected or in external devices.

Examples of access control security controls include: account management, separation of duties, least privilege, session lock, information flow enforcement, and session termination. 

Organizations limit: (i) system access to authorized users; (ii) processes acting on behalf of authorized users; (iii) devices, including other systems; and (iv) the types of transactions and functions that authorized users are permitted to exercise.

## 10.2 Awareness and Training (AT)

Often, it is the user community that is recognized as being the weakest link in securing systems. This is due to users not being aware of how their actions may impact the security of a system. Making system users aware of their security responsibilities and teaching them correct practices helps change their behavior. It also supports individual accountability, which is one of the most important ways to improve information security. Without knowing the necessary security measures or how to use them, users cannot be truly accountable for their actions. The importance of this training is emphasized in the Computer Security Act, which requires training for those involved with the management, use, and operation of federal systems.

The purpose of information security awareness, training, and education is to enhance security by: (i) raising awareness of the need to protect system resources; (ii) developing skills and knowledge so system users can perform their jobs more securely; and (iii) building in-depth knowledge as needed to design, implement, or operate security programs for organizations and systems. The organization is responsible for making sure that managers and users are aware of the security risks associated with their activities and that organizational personnel are adequately trained to carry out their information security-related duties and responsibilities.

Examples of awareness and training security controls include: security awareness training, role-based security training, and security training records.

Organizations: (i) ensure that managers and users of organizational systems are made aware of the security risks associated with their activities and of the applicable laws, executive orders, directives, policies, standards, instructions, regulations, or procedures related to the security of organizational systems; and (ii) ensure that organizational personnel are adequately trained to carry out their assigned information security-related duties and responsibilities.

## 10.3 Audit and Accountability (AU)

An audit is an independent review and examination of records and activities to assess the adequacy of system controls and ensure compliance with established policies and operational procedures. An audit trail is a record of individuals who have accessed a system as well as what operations the user has performed during a given period. Audit trails maintain a record of system activity both by system and application processes and by user activity of systems and applications. In conjunction with appropriate tools and procedures, audit trails can assist in detecting security violations, performance issues, and flaws in applications.

Audit trails may be used as a support for regular system operations, a kind of insurance policy, or both. As insurance, audit trails are maintained but not used unless needed (e.g., after a system outage). As a support for operations, audit trails are used to help system administrators ensure that the system or resources have not been harmed by hackers, insiders, or technical problems.

Examples of audit and accountability controls include: audit events, time stamps, non-repudiation, protection of audit information, audit record retention, and session audit.

Organizations: (i) create, protect, and retain system audit records to the extent needed to enable the monitoring, analysis, investigation, and reporting of unlawful, unauthorized, or inappropriate system activity; and (ii) ensure that the actions of individual system users can be uniquely traced to those users so they can be held accountable.

## 10.4 Assessment, Authorization, and Monitoring (CA)

A security control assessment is the testing and/or evaluation of the management, operational,
and technical security controls on a system to determine the extent to which the controls are
implemented correctly, operating as intended, and producing the desired outcome with respect to meeting the security requirements for the system. The assessment also helps determine if the
implemented controls are the most effective and cost-efficient solution for the function they re
intended to serve. Assessment of the security controls is done on a continuous basis to support a near real-time analysis of the organization’s current security posture.

Following a complete and thorough security control assessment, the authorizing official makes the decision to authorize the system to operate (for a new system) or to continue to operate.

Examples of security assessment and authorization controls include: security assessments, system interconnections, plans of action and milestones, and continuous monitoring. Organizations: (i) periodically assess the security controls in organizational systems to determine if the controls are effective in their application; (ii) develop and implement plans of action designed to correct deficiencies and reduce or eliminate vulnerabilities in organizational systems; (iii) authorize the operation of organizational systems and any associated system connections; and (iv) monitor security controls on an ongoing basis to ensure the continued effectiveness of the controls.

## 10.5 Configuration Management (CM)

Configuration management is a collection of activities focused on establishing and maintaining
the integrity of information technology products and systems through the control of processes for initializing, changing, and monitoring the configurations of those products and systems
throughout the SDLC. Configuration management consists of determining and documenting the appropriate specific settings for a system, conducting security impact analyses, and managing changes through a change control board. It allows the entire system to be reviewed to help ensure that a change made on one system does not have adverse effects on another system. For more information on configuration management, see NIST SP 800-128.

Common secure configurations (also known as security configuration checklists) provide recognized, standardized, and established benchmarks that stipulate secure configuration settings for information technology platforms and products. Once implemented, checklists can be used to verify that changes to the system have been reviewed from a security point-of-view. A common audit examines the system's configuration to see if major changes (such as connecting to the Internet) have occurred that have not yet been analyzed. The NIST checklist repository, maintained as part of the National Vulnerability Database (NVD), provides multiple checklists which can be used to check compliance with the secure configuration specified in the system security plan. The checklists can be accessed at https://web.nvd.nist.gov/view/ncp/repository. 

Examples of configuration management controls include: baseline configuration, configuration change control, security impact analysis, least functionality, and software usage restrictions. 

Organizations: (i) establish and maintain baseline configurations and inventories of organizational systems, including hardware, software, firmware, and documentation throughout the respective SDLC; and (ii) establish and enforce security configuration settings for information technology products employed in organizational systems.

## 10.6 Contingency Planning (CP)

An information security contingency is an event with the potential to disrupt system operations, thereby disrupting critical mission and business functions. Such an event could be a power outage, hardware failure, fire, or storm. Particularly destructive events are often referred to as “disasters.” To avert potential contingencies and disasters or minimize the damage they cause, organizations can take early steps to control the outcome of the event. Generally, this activity is called contingency planning.

A contingency plan is a management policy and procedure used to guide organizational response to a perceived loss of mission capability. The System Contingency Plan (SCP) is used by risk managers to determine what happened, why, and what to do. The SCP may point to the Continuity of Operations Plan (COOP) or Disaster Recovery Plan (DRP) for major disruptions. Contingency planning involves more than planning for a move offsite after a disaster destroys a data center. It also addresses how to keep an organization's critical functions operational in the event of disruptions, both large and small. This broader perspective on contingency planning is based on the distribution of system support throughout an organization. For more information on contingency planning, see NIST SP 800-34.

Examples of contingency planning controls include: contingency plan, contingency training, contingency plan testing, system backup, and system recovery and reconstitution.

Organizations: (i) establish, maintain, and effectively implement plans for emergency response (ii) backup operations, and (iii) oversee post-disaster recovery for organizational systems to ensure the availability of critical information resources and the continuity of operations in emergency situations.

## 10.7 Identification and Authentication (IA)

For most systems, identification and authentication is often the first line of defense. Identification is the means of verifying the identity of a user, process, or device, typically as a prerequisite for granting access to resources in a system. Identification and authentication is a technical measure that prevents unauthorized individuals or processes from entering a system.

Identification and authentication is a critical building block of information security since it is the basis for most types of access control and for establishing user accountability. Access control often requires that the system be able to identify and differentiate between users. For example, access control is often based on least privilege, which refers to granting users only those accesses required to perform their duties. User accountability requires linking activities on a system to specific individuals and, therefore, requires the system to identify users.

Systems recognize individuals based on the authentication data the systems receive. Authentication presents several challenges: collecting authentication data, transmitting the data securely, and knowing whether the individual who was originally authenticated is still the
individual using the system. For example, a user may walk away from a terminal while still logged on, and another person may start using it.

There are four means of authenticating a user's identity that can be used alone or in combination. User identity can be authenticated based on:
* something the individual knows – e.g., a password or Personal Identification Number (PIN);
* something the individual possesses (a token) – e.g., an ATM card or a smart card;
* something the individual is (static biometric) – e.g., fingerprint, retina, face; and
* something the individual does (dynamic biometrics) – e.g., voice pattern, handwriting, typing rhythm
While it may appear that any of these individual methods could provide strong authentication, there are problems associated with each. If an individual wanted to impersonate someone else on
a system, they can guess or learn another user’s password or steal or fabricate tokens. Each method also has drawbacks for legitimate users and system administrators: users forget passwords and may lose tokens, and administrative overhead for keeping track of identification and authorization data and tokens can be substantial. Biometric systems have significant technical, user acceptance, and cost problems as well.

Examples of identification and authentication controls include: device identification and authentication, identifier management, authenticator management, authenticator feedback, and re-authentication.

Organizations: (i) identify system users, processes acting on behalf of users, or devices and (ii) authenticate or verify the identities of those users, processes, or devices, as a prerequisite to allowing access to organizational systems.

## 10.8 Individual Participation (IP)

Engagement with individuals whose information is being processed by a system is an important aspect of privacy protection and the development of trustworthy systems. System functioning can have significant impacts on people’s quality of life and their ability to be autonomous individuals. Effective engagement can help to mitigate these risks and prevent a range of problems. For example, individuals may feel surveilled by a system, which may create chilling effects on ordinary behavior or cause them to alter their interactions with the system in unexpected ways. They may feel information has been appropriated – or used for profit or organizational gain without their permission or sufficient economic benefit. Excluding access to information can affect data quality that could lead to adverse decision-making about users, including inappropriate restrictions on access to products or services or other types of discrimination.

The Individual Participation controls address user interaction with the system to enable them to develop reliable assumptions about how the system is processing information about them. In addition, these controls create touch points so that users can better engage with the system and the management of their information. Users who have the ability to participate in decisions about their information processing may be more likely to have trust in the system and engage with it in constructive ways. Furthermore, enabling users to correct inaccurate information can improve system functioning, and protect these users from experiencing problems arising from system actions based on the processing of inaccurate information.

With Individual Participation controls, organizations keep individuals notified about the processing of their PII. These controls also, when appropriate, engage individuals as active participants in the decision-making process regarding their PII through information access and consent options, and provide them the ability to have their PII corrected or amended through appropriate redress mechanisms.

Examples of individual participation controls include: consent, redress, privacy notice, privacy act statements for federal agencies, and individual access.

Organizations: (i) request consent for processing PII; (ii) provide access to PII and redress opportunities for individual to amend or correct PII; and (iii) provide notice to individuals regarding the processing of PII.

## 10.9 Incident Response (IR)

Systems are subject to a wide range of threat events, from corrupted data files to viruses to natural disasters. Vulnerability to some threat events can be mitigated by having relevant standard operating procedures that can be followed in the event of an incident. For example, frequently occurring events like mistakenly deleting a file can usually be repaired through restoration from the backup file. More severe threat events, such as outages caused by natural disasters, are normally addressed in an organization's contingency plan. 

Threat events can also result from a virus, other malicious code, or a system intruder (either an insider or an outsider). They can more generally refer to those incidents that could result in severe damage without a technical expert response. An example of a threat event that would require an immediate technical response would be an organization experiencing a denial-of-service attack. This kind of attack would require swift action on the part of the incident response team in order to reduce the affect the attack will have on the organization. The definition of a threat event is somewhat flexible and may vary by organization and computing environment.

Although the threats that hackers and malicious code pose to systems and networks are well known, the occurrence of such harmful events remains unpredictable. Security incidents on larger networks (e.g., the Internet), such as break-ins and service disruptions, have harmed various organizations' computing capabilities. When initially confronted with such incidents, most organizations respond in an ad hoc manner. However, recurrence of similar incidents can make it cost-beneficial to develop a standard capability for quick discovery of and response to such events. This is especially true since incidents can often "spread" when left unchecked, thus escalating the damage and seriously harming an organization.

Incident handling is closely related to contingency planning. An incident handling capability may be viewed as a component of contingency planning because it allows for the ability to react quickly and efficiently to disruptions in normal processing. Broadly speaking, contingency planning addresses events with the potential to interrupt system operations. Incident handling can be considered that portion of contingency planning specifically that responds to malicious technical threats. For more information on incident response, see NIST SP 800-61, Computer Security Incident Handling Guide.

Examples of incident response controls include: incident response training, incident response testing, incident handling, incident monitoring, and incident reporting.

Organizations: (i) establish an operational incident handling capability for organizational systems that includes adequate preparation, detection, analysis, containment, recovery, and user response activities; and (ii) track, document, and report incidents to appropriate organizational officials and/or authorities.

## 10.10 Maintenance (MA)

To keep systems in good working order and to minimize risks from hardware and software failures, it is paramount that organizations establish procedures for the maintenance of organizational systems. There are many different ways an organization can address these maintenance requirements.

Controlled maintenance of a system deals with maintenance that is scheduled and performed in accordance with the manufacturer’s specifications. Maintenance performed outside of a scheduled cycle, known as corrective maintenance, occurs when a system fails or generates an error condition that must be corrected in order to return the system to operational conditions. Maintenance can be performed locally or non-locally. Nonlocal maintenance is any maintenance
or diagnostics performed by individuals communicating through a network either internally or
externally (e.g., the Internet).

Examples of maintenance controls include: controlled maintenance, maintenance tools, nonlocal maintenance, maintenance personnel, and timely maintenance.

Organizations: (i) perform periodic and timely maintenance on organizational systems; and (ii) provide effective controls on the tools, techniques, mechanisms, and personnel used to conduct system maintenance.

## 10.11 Media Protection (MP)

Media protection is a control that addresses the defense of system media, which can be described as both digital and non-digital. Examples of digital media include: diskettes, magnetic tapes, external/removable hard disk drives, flash drives, compact disks, and digital video disks. Examples of non-digital media include paper or microfilm.

Media protections can restrict access and make media available to authorized personnel only, apply security labels to sensitive information, and provide instructions on how to remove information from media such that the information cannot be retrieved or reconstructed. Media protections also include physically controlling system media and ensuring accountability, as well as restricting mobile devices capable of storing and carrying information into or outside of restricted areas.

Examples of media protection controls include: media access, media marking, media storage, media transport, and media sanitization.

Organizations: (i) protect system media, both paper and digital; (ii) limit access to information on system media to authorized users; and (iii) sanitize or destroy system media before disposal or release for reuse.

## 10.12 Privacy Authorization (PA)

To better protect individuals’ privacy and limit problems arising from system processing of their information, organizations should have a clear rationale for the collection, use, maintenance, and sharing of personally identifiable information (PII). Overly broad collection and maintenance of information may create the potential for security vulnerabilities or allow for internal abuses or expanded uses that cross privacy boundaries. Individuals could be stigmatized by the release of their information or suffer from identity theft. Third parties with whom information is shared may disregard the purpose or context in which information is collected and use that information in a manner that contradicts individuals’ privacy interests. As a result, individuals could lose trust in these systems, which could lead to abandonment or threaten the adoption of new technologies, even those designed to improve access to public services.

Organizations may have to comply with external laws or regulations, as well as internal policies
pertaining to the processing of PII. Privacy Authorization controls aid an organization in
ensuring that it is only processing PII in ways that it has the authority for and clear purposes for doing so. This assurance facilitates an organization’s accountability for following relevant policies, and minimizes potential noncompliance costs and reputational damage. Documenting this information also supports individuals’ understanding of a system’s processing of their PII. 

Examples of privacy authorization controls include: authority to collect, purpose specification, and information sharing with external parties.

Organizations: (i) identify the legal bases that authorize particular personally identifiable information (PII) collection use, maintenance, and sharing; (ii) specify in their notices the purpose(s) for which PII is collected; and (iii) manage the sharing of PII with external parties.

## 10.13 Physical and Environmental Protection (PE)

The term physical and environmental security refers to measures taken to protect systems, buildings, and related supporting infrastructure against threats associated with their physical environment. Physical and environmental controls cover three broad areas:

1. The physical facility is typically the building, other structure, or vehicle housing the system and network components. Systems can be characterized, based upon their operating location, as static, mobile, or portable. Static systems are installed in structures at fixed locations. Mobile systems are installed in vehicles that perform the function of a structure, but not at a fixed location. Portable systems may be operated in a wide variety of locations, including buildings, vehicles, or in the open. The physical characteristics of these structures and vehicles determine the level of physical threats such as fire, roof leaks, or unauthorized access.

2. The facility's general geographic operating location determines the characteristics of natural threats, which include earthquakes and flooding; man-made threats such as burglary, civil disorders, or interception of transmissions and emanations; and damaging nearby activities, including toxic chemical spills, explosions, fires, and electromagnetic interference from emitters (e.g., radars).

3. Supporting facilities are those services (both technical and human) that maintain the operation of the system. The system's operation usually depends on supporting facilities such as electric power, heating and air conditioning, and telecommunications. The failure or substandard performance of these facilities may interrupt operation of the system and cause physical damage to system hardware or stored data.

Examples of physical and environmental controls include: physical access authorizations, physical access control, monitoring physical access, emergency shutoff, emergency power, emergency lighting, alternate work site, information leakage, and asset monitoring and tracking. 

Organizations: (i) limit physical access to systems, equipment, and the respective operating environments to authorized individuals; (ii) protect the physical plant and support infrastructure for systems; (iii) provide supporting utilities for systems; (iv) protect systems against environmental hazards; and (v) provide appropriate environmental controls in facilities containing systems.

## 10.14 Planning (PL)

Systems have increasingly taken on a strategic role in the organization. They assist organizations in conducting their daily activities and support decision making. With proper planning, systems can provide a security level commensurate with the risk associated with the operation of the system, improve productivity and performance, and enable new ways of managing and organizing. Planning for systems is crucial in the development and implementation of the
organization’s information security goals.

System security plans (SSPs)(13) are developed to provide an overview of the security requirements of the system and how the security controls and control enhancements meet those security requirements. Having security controls in place alone does not guarantee the overall protection of a system. Organizations also need to develop, document, and disseminate how these controls are implemented, rules that describe the responsibility of users, and how the organization operates the system from the perspective of information security.

Examples of planning controls include: system security plan, rules of behavior, security concept of operations, information security architecture, and central management.

Organizations: develop, document, periodically update, and implement security plans for organizational systems that describe the security controls in place or planned for the system, as well as the rules of behavior for individuals accessing the systems.

`(13) For more information on developing a System Security Plan, see NIST SP 800-18.`

## 10.15 Program Management (PM)

Systems and the information they process are critical to many organizations' ability to perform their missions and business functions. It makes sense that executives view system security as a management issue and seek to protect their organization's information technology resources as they would any other valuable asset. To do this effectively requires the development of a comprehensive management approach.

Many security programs, distributed throughout the organization, have different elements performing various functions. While this approach has benefits, the distribution of the system security functions in many organizations is haphazard, usually based upon history (i.e., who was available in the organization to do what when the need arose). Ideally, the distribution of system security functions is the result of a planned and integrated management philosophy.

Managing system security at multiple levels has its benefits. Each level contributes to the overall system security program with different types of expertise, authority, and resources. In general, higher-level officials (e.g., those at the headquarters, unit levels in the agency described above) better understand the organization as a whole and have more authority. On the other hand, lower-level officials (e.g., at the system facility and applications levels) are more familiar with the specific technical and procedural requirements and problems of the systems and users. The levels of system security program management are complementary; each can help the other be more effective.

Examples of program management controls include: information security program plan, information security resources, plan of action and milestone process, system inventory, enterprise architecture, risk management strategy, insider threat program, and threat awareness program.

## 10.16 Personnel Security (PS)

Users play a vital role in protecting a system as many important issues in information security involve users, designers, implementers, and managers. How these individuals interact with the system and the level of access they need to do their jobs can also impact the system’s security posture. Almost no system can be secured without properly addressing these aspects of personnel security.

Personnel security seeks to minimize the risk that staff (permanent, temporary, or contractor) pose to organizational assets through the malicious use or exploitation of their legitimate access to the organization’s resources. An organization’s status and reputation can be adversely affected by the actions of its employees. Employees may have access to extremely sensitive, confidential, or proprietary information, the disclosure of which can destroy an organization’s reputation or cripple it financially. Therefore, organizations must be vigilant when recruiting and hiring new employees, as well as when an employee transfers or is terminated. The sensitive nature and value of organizational assets requires in-depth personnel security measures.

Examples of personnel control include: personnel screening, personnel termination, personnel transfer, access agreements, and personnel sanctions.

Organizations: (i) ensure that individuals occupying positions of responsibility within organizations (including third-party service providers) are trustworthy and meet established security criteria for those positions; (ii) ensure that organizational information and systems are protected during and after personnel actions such as terminations and transfers; and (iii) employ formal sanctions for personnel failing to comply with organizational security policies and procedures.

## 10.17 Risk Assessment (RA)

Organizations are dependent upon information technology and associated systems to successfully carry out their missions. While the increasing number of information technology products used in various organizations and industries can be beneficial, in some instances they may also introduce serious threats that can adversely affect an organization’s systems by exploiting both known and unknown vulnerabilities. The exploitation of vulnerabilities in organizational systems can compromise the confidentiality, integrity, or availability of the information being processed, stored, or transmitted by those systems.

Performing a risk assessment is one of four components of risk management as described in
NIST SP 800-39. Risk assessments identify and prioritize risks to organizational operations, assets, individuals, other organizations, and the Nation that may result from the operation of a system. Risk assessments, which can be conducted at all three tiers in the risk management hierarchy, inform decision makers and support risk responses by identifying: (i) relevant threats to organizations or threats directed through organizations against other organizations; (ii) vulnerabilities both internal and external to organizations; (iii) impact (i.e., harm) to organizations that may occur given the potential for threats exploiting vulnerabilities; and (iv) the likelihood that harm will occur. For more information on risk assessments, see NIST SP 800-30.

Examples of risk assessment controls include: security categorization, risk assessment, vulnerability scanning, and technical surveillance countermeasures survey.

Organizations: periodically assess the risk to organizational operations (e.g., mission, functions, image, reputation), organizational assets, and individuals, which may result from the operation of organizational systems and the associated processing, storage, or transmission of organizational information.

## 10.18 System and Services Acquisition (SA)

As with other aspects of information processing systems, security is most effective and efficient if planned and managed throughout a system's life cycle, from initial planning to design, implementation, operation, and disposal. Many security-relevant events and analyses occur during a system's life which begins with the organization acquiring the necessary tools and services. The effective integration of security requirements into enterprise architecture also helps to ensure that important security considerations are addressed early in the SDLC and that those considerations are directly related to the organizational mission/business processes. 

SSPs can be developed for a system at any point in the life cycle. However, to minimize costs and prevent the disruption of ongoing operations, the recommended approach is to incorporate the plan at the beginning of the system’s life cycle. It is significantly more expensive to add security features to a system than it is to include them from the very beginning. It is important to ensure that security requirements keep pace with changes to the computing environment, technology, and personnel.

Examples of system and service acquisition controls include: allocation of resources, acquisition process, system documentation, supply chain protection, trustworthiness, criticality analysis, developer-provided training, component authenticity, and developer screening.

Organizations: (i) allocate sufficient resources to adequately protect organizational systems; (ii) employ SDLC processes that incorporate information security considerations; (iii) employ software usage and installation restrictions; and (iv) ensure that third-party providers employ adequate security measures to protect information, applications, and/or services outsourced from
the organization.

## 10.19 System and Communications Protection (SC)

System and communications protection controls provide an array of safeguards for the system.
Some of the controls in this family address the confidentiality and integrity of information at rest and in transit. The protection of confidentiality and integrity can be provided by these controls through physical or logical means. For example, an organization can provide physical protection by segregating certain functions to separate servers, each having its own set of IP addresses.

Organizations can better safeguard their information by separating user functionality and system management functionality. Providing this type of protection prevents the presentation of system management-related functionality on an interface for non-privileged users. System and communications protection also establishes boundaries that restrict access to publicly accessible information within a system. Using boundary protections, an organization can monitor and control communications at external boundaries as well as key internal boundaries within the
system.

Examples of system and communication protection controls include: application partitioning, denial of service protection, boundary protection, trusted path, mobile code, session authenticity, thin nodes, honeypots, transmission confidentiality and integrity, operations security, protection of information at rest and in transit, and usage restrictions.

Organizations: (i) monitor, control, and protect organizational communications (i.e.,information transmitted or received by organizational systems) at the external boundaries and key internal boundaries of the systems; and (ii) employ architectural designs, software development techniques, and systems engineering principles that promote effective information security within organizational systems.

## 10.20 System and Information Integrity (SI)
Integrity is defined as guarding against improper information modification or destruction, and includes ensuring information non-repudiation and authenticity. It is the assertion that data can only be accessed or modified by the authorized personnel. System and information integrity provides assurance that the information being accessed has not been meddled with or damaged by an error in the system.

Examples of system and information integrity controls include: flaw remediation, malicious code protection, security function verification, information input validation, error handling, non-persistence, and memory protection.

Organizations: (i) identify, report, and correct information and system flaws in a timely manner; (ii) provide protection from malicious code at appropriate locations within organizational systems; and (iii) monitor system security alerts and advisories and respond appropriately.


