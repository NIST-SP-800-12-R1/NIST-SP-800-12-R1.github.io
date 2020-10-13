---
layout: default
title: 2 Elements of Information Security
nav_order: 30 
---

# 2 Elements of Information Security
{: .no_toc }

1. TOC
{:toc}

This publication addresses eight major elements regarding information security to help the reader gain a better understanding of how the security requirements and controls discussed in Chapter 10 support the overall operations of the organization. These eight concepts are:

1. Information security supports the mission of the organization.
2. Information security is an integral element of sound management.(4)
3. Information security protections are implemented so as to be commensurate with risk.
4. Information security roles and responsibilities are made explicit.
5. Information security responsibilities for system owners go beyond their own organization.
6. Information security requires a comprehensive and integrated approach.
7. Information security is assessed and monitored regularly.
8. Information security is constrained by societal and cultural factors.

`(4) In the context of this publication, sound management refers to due diligence in taking all practical steps to ensure that information security management decisions are made in such a way that they not only protect the information stored, processed, and transmitted by an organization, but also the systems that fall under the purview of the organization.`

## 2.1 Information security supports the mission of the organization

In Chapter 1, information security was defined as the protection of information and systems from unauthorized access, use, disclosure, disruption, modification, or destruction in order to provide confidentiality, integrity, and availability. The careful implementation of information security controls is vital to protecting an organization’s information assets as well as its reputation, legal position, personnel, and other tangible or intangible assets.

An organization’s inability to select and implement appropriate security rules and procedures is likely to have a negative impact on the mission of the organization. However, well-chosen security rules and procedures that are put in place to protect important assets support the overall organizational mission. In today’s environment of malicious code, system breaches, and insider threats, publicized security issues can have dire consequences, especially to profitability and to the reputation of the organization. Private and public-sector organizations improve both profit and service to customers when appropriate security protections are in place. Information security, therefore, is a means to an end and not an end in itself.

It is critical to understand the organizational mission and how each system supports that mission. After a system's role has been defined, the security requirements implicit in that role can also be defined. Security can then be explicitly stated in terms of the organization's mission.

The roles and functions of a system may not be constrained to a single organization. In an inter-organizational system, each organization benefits from securing the system. For example, for electronic commerce to be successful, each of the participants requires security controls to protect their resources. Good security on the buyer's system also benefits the seller; the buyer's system is less likely to be used for fraud, to become unavailable, or to otherwise negatively affect the seller. (The reverse is also true.)

## 2.2 Information security is an integral element of sound management

Management personnel are ultimately responsible for determining the level of acceptable risk for a specific system and the organization as a whole, taking into account the cost of security controls. Since information security risk cannot be completely eliminated, the objective is to find the optimal balance between protecting the information or system and utilizing available resources. It is vital for systems and related processes to have the ability to protect information, financial assets, physical assets, and employees, while also taking resource availability into consideration.

When an organization's information and systems are linked with external systems, management's responsibilities extend beyond organizational boundaries. This may require that management (1) know what general level or type of security is employed on the external system(s), and/or (2) seek assurance that the external system provides adequate security for the organization’s information and system. For example, cloud service providers (CSPs) and cloud supply chain participants may assume the management role for storing, processing, and transmitting organizational information. However, that does not leave the organization(5) free of any security-
related responsibility. It is up to the organization to ensure that the CSPs and cloud supply chain participants provide an appropriate level of security for the information being stored, processed, and transmitted.

`(5) An organization is an entity of any size, complexity, or positioning within an organizational structure (e.g., a federal agency or, as appropriate, any of its operational elements).`


## 2.3 Information security protections are implemented so as to be commensurate with risk

Risk to a system can never be completely eliminated. Therefore, it is crucial to manage risk by striking a balance between usability and the implementation of security protections. The primary objective of risk management is to implement security protections that are commensurate with risk. Applying unnecessary protections may waste resources and make systems more difficult to use and maintain. Conversely, not applying protections needed to protect the system may leave it and its information vulnerable to breaches in confidentiality, integrity, and availability, all of which could impede or even halt the mission of the organization. 

Federal organizations use impact levels (high, moderate, and low) to identify and categorize the impact that a loss of confidentiality, integrity, or availability of information and/or a system may have on the organization’s operations and allow them to identify appropriate protections. The accurate categorization of information and systems is integral in determining how to protect
information commensurate with risk. Security categories convey the impact that a loss of confidentiality, integrity, or availability may have on the mission of the organization. To determine the impact level of a system, organizations may refer to the guidance in FIPS 199, NIST SP 800-30, and NIST SP 800-60.

An accurate determination of the system impact level provides the information needed to select an appropriate set of security controls from NIST SP 800-53. The selection process includes an assessment of the costs to implement and maintain the security controls and the expected security benefits (i.e., risk reduction) from applying those controls.

Security benefits have both direct and indirect costs. Direct costs include purchasing, installing, and administering security protections (e.g., access control software or fire-suppression systems). Indirect costs may affect both system and business performance, employee morale, or retraining requirements. In some cases, indirect costs may exceed the direct cost of the control. Organizational management is responsible for weighing the cost versus benefit of the appropriate protection implementation and making risk-based decisions.

## 2.4 Information security roles and responsibilities are made explicit

The roles and responsibilities of system owners, common control providers, authorizing officials, system s ecurity officers, users, and others are clear and documented. If the responsibilities are not made explicit, management may find it difficult to hold personnel accountable for future outcomes.

Documenting information security responsibilities is not dependent on the size of the organization. Even small organizations can prepare a document that states the organizational policy and identifies the information security responsibilities for a system or for the entire organization.

Roles and responsibilities are discussed briefly in Chapter 3 of this publication. For more detailed information specific to key information security participants, refer to Appendix D of NIST SP 800-37.

## 2.5 Information security responsibilities for system owners go beyond their own organization

Users of a system are not always located within the boundary of the system they use or have access to. For example, when an interconnection between two or more systems is in place, information security responsibilities might be shared amongst the participating organizations. When such is the case, the system owners are responsible for sharing the security measures used by the organization to provide confidence to the user that the system is adequately secure and capable of meeting security requirements. In addition to sharing security-related information, the
incident response team has a duty to respond to security incidents in a timely fashion in order to prevent damage to the organization, personnel, and other organizations.

## 2.6 Information security requires a comprehensive and integrated approach

Providing effective information security requires a comprehensive approach that considers a variety of areas both within and outside of the information security field. This approach applies throughout the entire system life cycle.

For example, defense-in-depth is a security principle used to protect organizational information and systems from threats by implementing multi-layered security countermeasures. Defense-in-depth utilizes administrative defenses (e.g., policies, procedures) and security technologies (e.g., intrusion detection systems, firewalls, configuration settings, and antivirus software) in tandem with physical security defenses (e.g., gates, guards) to minimize the probability of a successful attack on the system. These measures not only help reduce the likelihood that a security breach will compromise access to system assets or have detrimental effects on confidentiality, integrity, or availability, but also give the organization near-real time notification once an attack has been initiated.

### 2.6.1 Interdependencies of security controls

Security controls are seldom put in place as stand-alone solutions to a problem. They are typically more effective when paired with another control or set of controls. Security controls, when selected properly, can have a synergistic effect on the overall security of a system. Each security control in NIST SP 800-53 has a related controls section listing security control(s) that compliment that specific control. If users do not understand these interdependencies, the results can be detrimental to the system.

### 2.6.2 Other interdependencies

Interdependencies between and amongst security controls are not the only factor that can influence the effectiveness of security controls. System management, legal constraints, quality assurance, privacy concerns, and internal and management controls can also affect the functionality of the selected controls. System managers must be able to recognize how information security relates to other security disciplines like physical and environmental security. Understanding how those relationships work together will prove beneficial when implementing a
more holistic security strategy. NIST SP 800- 160 , Systems Security Engineering: Considerations for a Multidisciplinary Approach in the Engineering of Trustworthy Secure Systems, provides much more detailed information on considerations to engineering a trustworthy system.

Understanding the relationships between security controls is especially important when systems are connected to other systems or interconnected to a globally distributed supply chain ecosystem. Supply chains consist of public- and private-sector entities and use geographically-diverse routes to provide a highly-refined, cost-effective, reusable information and communications technology (ICT) solution. For more information on supply chain risk management, see NIST SP 800-161, Supply Chain Risk Management Practices for Federal Information Systems and Organizations.

### 2.7 Information security is assessed and monitored regularly

Information security is not a static process and requires continuous monitoring and management to protect the confidentiality, integrity, and availability of information as well as to ensure that new vulnerabilities and evolving threats are quickly identified and responded to accordingly. In the presence of a constantly evolving workforce and technological environment it is essential that organizations provide timely and accurate information while operating at an acceptable level
of risk.

Information Security Continuous Monitoring (ISCM) is defined in NIST SP 800-137 as the maintenance of ongoing awareness of information security, vulnerabilities, and threats to support organizational risk management decisions. ISCM provides a clear understanding of organizational risk tolerance to assist officials in setting priorities and managing risk throughout the organization in a consistent manner. ISCM ensures that the selected security controls remain effective and maintains organizational awareness of threats and vulnerabilities.

For more detailed information on continuous monitoring fundamentals and the continuous monitoring process, refer to NIST SP 800-137. NIST SP 800-53A can also be leveraged to provide insight on assessment procedures.

### 2.8 Information security is constrained by societal and cultural factors

Societal factors influence how individuals understand and use systems which consequently impacts the information security of the system and organization. Individuals perceive, reason, and make risk-based decisions in different ways. To address this, organizations make information security functions transparent, easy to use, and understandable. Additionally, providing regularly scheduled security awareness training mitigates individual differences of risk perception. As with societal factors, how an organization conducts business can serve as a culture factor worth considering when dealing with information security. An organization’s own culture can impact its response to information security. Careful explanation of the risks associated with the business practices can help in the transparency and acceptance of the recommended information security practices.

It is incumbent on organizations to find a balance between information security requirements and usability. Organizations can leverage a variety of tools that meet the security requirements of their system(s) without unduly burdening the user. For example, consider a system that requires a user to input their username and password multiple times to access different applications during
a single session. In that scenario, organizations can choose which types of applications, if any, will permit password and password hash storage based on a consideration of the risks versus the convenience of the users.

Privacy was once considered to be unrelated to information security—the two functions were discussed as if they could not co-exist in a system. Today, a symbiotic relationship between privacy and information security is essential. Organizations cannot protect the privacy of individuals without a basic foundation of information security. However, privacy is more than security as it also relates to problems that individuals may experience as a result of the authorized processing of their information throughout the data life cycle. Protecting the privacy of individuals is a fundamental responsibility of organizations that collect, use, maintain, share, and dispose of personally identifiable information (PII). For more detailed privacy information see NISTIR 8062, An Introduction to Privacy Engineering and Risk Management in Federal Systems and NIST SP 800-122, Guide to Protecting the Confidentiality of Personally Identifiable Information (PII).

Overall, the relationship between security and societal norms need not necessarily be antagonistic. Societal norms can have both a positive and negative impact on information security. For example, a negative impact on information security can be seen in the form of a user writing down passwords and keeping them near their computer. A positive impact can be seen by a broader implementation of multi-factor authentication—where in order for a user to reset a password, more than one form of authentication is required (e.g., text message to user, physical token). Security can enhance the access and flow of data and information by providing more accurate and reliable information as well as greater availability of systems. Security
mechanisms can also enhance individuals’ privacy (e.g., encryption). Some security mechanisms may present new vulnerabilities ( e.g., single sign-on). Thus, it is important to consider how to implement security solutions in ways that optimize broader societal goals.

Societal norms change and so too must the information security protections placed on systems. Security controls that are presently sufficient may not keep pace with the constantly changing computing environment. The culture and security environment of the organization also plays an important role in the employees’ perception of risk. Insufficient or non-existent security standards may lead to the degradation of the organization’s security posture. Providing updated and recurring training on what is and what is not an acceptable use of organizational systems helps safeguard the overall security of the system.
