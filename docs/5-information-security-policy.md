---
layout: default
title: 5 Information Security Policy  
nav_order: 60 
---

# 5 Information Security Policy
{: .no_toc }

1. TOC
{:toc}

The term policy has more than one definition when discussing information security. NIST SP 800-95 , Guide to Secure Web Services, defines policy as “statements, rules or assertions that specify the correct or expected behavior of an entity.” For example, an authorization policy might specify the correct access control rules for a software component. The term policy can also refer to specific security rules for a system or even the specific managerial decisions that dictate an organization’s email privacy policy or remote access security policy.

Information security policy is defined as an aggregate of directives, regulations, rules, and practices that prescribes how an organization manages, protects, and distributes information. In making these decisions, managers face difficult decisions with regard to resource allocation, competing objectives, and organizational strategy, all of which relate to protecting technical and information resources as well as guiding employee behavior. Managers at all levels make choices that can affect policy, with the scope of the policy’s applicability varying according to the scope of the manager’s authority.

Managerial decisions on information security issues vary greatly. To differentiate various kinds of policy, this chapter categorizes them into three basic types: Program Policy, Issue-specific Policy, and System-specific Policy.

Policy controls are addressed by the “-1” controls for every security control family found in NIST SP 800-53. The “-1” controls establish policy and procedures for the effective implementation of the selected security control and control enhancement.

## 5.1 Standards, Guidelines, and Procedures

Because policy is written at a broad level, organizations also develop standards, guidelines, and procedures that offer users, managers, system administrators, and others a clearer approach to implementing policy and meeting organizational goals. Standards and guidelines specify technologies and methodologies to be used to secure systems. Procedures are yet more detailed steps to be followed to accomplish security-related tasks. Standards, guidelines, and procedures may be promulgated throughout an organization via handbooks, regulations, or manuals.

* Organizational standards (not to be confused with American National Standards, FIPS, Federal Standards, or other national or international standards) specify uniform use of specific technologies, parameters, or procedures when such uniform use will benefit an organization. Standardization of organization-wide identification badges is a typical example, providing ease of employee mobility and automation of entry/exit systems. Standards are normally compulsory within an organization.

* Guidelines assist users, systems personnel, and others in effectively securing their systems. The nature of guidelines, however, immediately recognizes that systems vary considerably, and imposition of standards is not always achievable, appropriate, or cost-effective. For example, an organizational guideline may be used to help develop system-specific standard procedures. Guidelines are often used to help ensure that specific security measures are not overlooked, although they can be implemented, and correctly so, in more than one way.

* Procedures describe how to implement applicable security policies, standards, and guidelines. They are detailed steps to be followed by users, system operations personnel, or others to accomplish a particular task (e.g., preparing new user accounts and assigning the appropriate privileges).

Some organizations issue overall information security manuals, regulations, handbooks, or similar documents. These may mix policy, guidelines, standards, and procedures, since they are closely linked. While manuals and regulations can serve as important tools, it is often useful if they clearly distinguish between policy and its implementation. This can help in promoting flexibility and cost-effectiveness by offering alternative implementation approaches to achieving policy goals.

## 5.2 Program Policy

Program policy is used to create an organization’s information security program. Program policies set the strategic direction for security and assign resources for its implementation within the organization. A management official—typically the SISO—issues program policy to establish or restructure the organization’s information security program. This high-level policy defines the purpose of the program and its scope within the organization, addresses compliance issues, and assigns responsibility to the information security organization for direct program implementation as well as other related responsibilities.

### 5.2.1 Basic Components of Program Policy

Program policy addresses the following:

* Purpose. Program policy often includes a statement describing the purpose and goals of the program. Security-related needs such as integrity, availability, and confidentiality can form the basis of organizational goals established in the policy. For instance, in an organization responsible for maintaining large mission-critical databases, a reduction in errors, data loss, data corruption, and recovery might be specifically stressed. However, in an organization responsible for maintaining confidential personal data, goals might emphasize stronger protection against unauthorized disclosure.

* Scope. Program policies are clear as to which resources (e.g., facilities, hardware and software, information, and personnel) the information security program protects. In many cases, the program will encompass all systems and organizational personnel, while in others, it might be appropriate for an organization’s information security program to be more limited in scope. For example, a policy intended to protect information stored on a classified or high impact system will be much more stringent than that of a policy intended to secure a system deemed to be low impact.

* Responsibilities. Once the information security program is established, its management is normally assigned to either a newly created or existing office. The responsibilities of officials and offices throughout the organization also need to be addressed. This section of the policy statement, for example, would distinguish between the responsibilities of information service providers and the managers of applications using the provided services. The policy would also establish operational security offices for major systems, particularly those at high risk or that are most critical to organizational operations. It can also serve as the basis for establishing employee accountability. Roles and responsibilities were addressed in Chapter 3 of this publication.

* Compliance. Program policy typically addresses two compliance issues:
    1. General compliance to ensure meeting the requirements to establish a program and the responsibilities assigned therein to various organizational components. Often an oversight entity (e.g., the Inspector General) is assigned responsibility for monitoring compliance, including how well the organization is implementing management’s priorities for the program.

    2. The use of specified penalties and disciplinary actions. Since the security policy is a high-level document, specific penalties for various infractions are not normally detailed here. I nstead, the policy may authorize the creation of compliance structures that include violations and specific disciplinary actions.

An important aspect of developing compliance policy is to remember that an employee’s violation of policy may be unintentional. For example, nonconformance can often be the result of a lack of knowledge or training. The need to obtain guidance from appropriate legal counsel is critical when addressing issues involving penalties and disciplinary action for individuals. The policy does not need to restate penalties already addressed by law, although they can be listed if the policy will also be used as an awareness or training document.

## 5.3 Issue-Specific Policy

Based on the guidance from the information security policy, issue-specific policies are developed to address areas of current relevance and concern to an organization. The intent is to provide specific guidance and instructions on proper usage of systems to employees within the organization. An issue-specific policy is meant for every technology the organization uses and is written in such a way that it will be clear to users. Unlike program policies, issue-specific
policies must be reviewed on a regular basis due to frequent technological changes in an
organization.

### 5.3.1 Example Topics for Issue-Specific Policy

There are many areas for which issue-specific policy may be appropriate. New technologies and the discovery of new threats often require the creation of an issue-specific policy. Examples of issue-specific policy include:

* Internet Access. Connecting to the Internet yields many benefits as well as many problems. Some issues an Internet access policy may address include identifying who will have access, what types of systems may be connected to the network, what types of information may be transmitted via the network, requirements for user authentication for Internet-connected systems, and the use of firewalls.

* Email Privacy. This policy will clarify what information is collected and stored and the way the information is being used. Management may wish to monitor the employee to ensure that they are only using organizational systems for business purposes, or to determine if the employee is distributing viruses, sending offensive content, or disclosing private business information. Users may be accorded a certain level of privacy regarding email, and this policy addresses what level of privacy to expect as well as the circumstances under which email may be read.

* Bring Your Own Device (BYOD). Allows individuals to use personal devices in the workplace. Allowing BYOD can increase productivity and decrease costs to the organization. However, introducing different operating systems and user configurations to the organizations network can be challenging, not only to the security of the organizations information, but also to the privacy of the employee. A comprehensive BYOD policy has specific considerations for the device and the user as well as rules of behavior which must be adhered to in order to access organizational resources using personal devices.

* Social Media. Even if the organization does not have a social media presence, chances are their users will. Having a social media policy is crucial for protecting the organization and its employees. A social media policy provides guidelines for users that delineate expected behavior when using different social media platforms. Depending on the organization, the policy can be strict—not allowing the use of social media on organization provided resources—or a lenient policy that allows social media access within organization specified limitations.

Other topics that are candidates for issue-specific policy include, but are not limited to: approach to risk management and contingency planning, protection of confidential/proprietary information, unauthorized software, unauthorized use of equipment, violations of policy, use of external storage, rights of privacy, and physical emergencies.

### 5.3.2 Basic Components of Issue-Specific Policy

An issue-specific policy can be broken down into the following components:

* Issue statement. To formulate a policy on an issue, information owner/steward first define the issue with any relevant terms, distinctions, and conditions included. It is often useful to specify the goal or justification for the policy to facilitate compliance. For example, an organization might want to develop an issue-specific policy on the use of "unofficial software," which might be defined to mean any software not approved, purchased, screened, managed, or owned by the organization. Additionally, the applicable distinctions and conditions might then need to be included for some software, such as that for software privately owned by employees but approved for use at work, or owned and used by other businesses under contract to the organization.

* Statements of the Organization’s Position. Once the issue is stated and related terms and conditions are detailed, this section is used to clearly state the organization's position (i.e., management's decision) on the issue. Per the previous example, this would mean stating whether the use of unofficial software as defined is prohibited in all or some cases, whether there are further guidelines for approval and use, or whether case-by-case exceptions may be granted, by whom, and on what basis.

* Applicability. Issue-specific policies also need to include statements of applicability. This means clarifying where, how, when, to whom, and to what a policy applies. For example, it could be that the hypothetical policy on unofficial software is intended to apply only to the organization's own on-site resources and employees and not to contractors with offices at other locations. Additionally, the policy's applicability might need to be clarified as it pertains to employees travelling among different sites, working from home, or who need to transport and use disks at multiple sites.

* Roles and Responsibilities. The assignment of roles and responsibilities is also usually included in issue-specific policies. For example, if the policy permits employees to use privately owned, unofficial software at work with the appropriate approvals, then the approval authority granting such permission would need to be stated. (Policy would stipulate, who, by position, has such authority.) Likewise, it would need to be clarified who would be responsible for ensuring that only approved software is used on organizational system resources and, possibly, for monitoring users regarding unofficial software.

* Compliance. For some types of policy, it may be appropriate to describe unacceptable infractions and the consequences of such behavior in greater detail. Penalties may be explicitly stated and consistent with organizational personnel policies and practices. When used, they can be coordinated with appropriate officials, offices, and even employee bargaining units. It may also be desirable to task a specific office in the organization with monitoring compliance.

* Points of Contact and Supplementary Information. For any issue-specific policy, indicate the appropriate individuals to contact in the organization for further information, guidance, and compliance. Since positions tend to change less often than the individuals occupying them, specific positions may be preferable as the point of contact. For example, for some issues the point of contact might be a line manager; for other issues it might be a facility manager, technical support person, system administrator, or security program representative. Using the above example once more, employees would need to know whether the point of contact for questions and procedural information would be their immediate superior, a system administrator, or an information security official.

## 5.4 System-Specific Policy

Program and issue-specific policies are broad, high-level policies written to encompass the entire organization where system-specific policies provide information and direction on what actions are permitted on a particular system. These policies are similar to issue-specific policies in that they relate to specific technologies throughout the organization. However, system-specific policies dictate the appropriate security configurations to the personnel responsible for implementing the required security controls in order to meet the organization’s information security needs.

To develop a cohesive and comprehensive set of security policies, officials may use a management process that derives security rules from security goals. It is helpful to consider a two-level model for system security policy: security objectives and operational security rules. Closely linked and often difficult to distinguish, however, is the implementation of the policy in technology. Similar to issue-specific policies, it is recommended that system-specific policies be reviewed as required by organization defined time period to ensure conformance to the most current security procedures.

### 5.4.1 Security Objectives

The first step in the management process is to define security objectives commensurate with risk for the specific system. Although this process may begin with an analysis of the need for integrity, confidentiality, and availability, it may not stop there. A security objective needs to be specific, concrete, well defined, and stated in such a way that it is a clearly achievable objective. Stakeholders play an important role in developing comprehensive, yet practical, policy. Therefore, it is imperative to remember that policy is not created by management personnel only.

### 5.4.2 Operational Security Rules

After management determines the security objectives, rules for managing and operating a system
can be identified and documented. For example, the rules may define authorized modifications-specifying individuals allowed to take certain actions under particular conditions with regard to
specific classes and records of information. The degree of specificity needed for operational security varies from system-to-system. The more detailed the rules are, the easier it is for administrators to determine when a violation has occurred. A detailed description can also streamline automating policy enforcement.

In addition to deciding the level of detail, management determines the degree of formality in documenting the system-specific policy. Once again, the more formal the documentation, the easier it is to enforce and to follow the policy. For example, a helpful practice would be to draft a statement of the access privileges for a system as well as the assignment of security responsibilities. The rules for system usage and the consequences of noncompliance should also be addressed. Documenting access control policy can make it substantially easier to follow and to enforce.

Policy decisions in other areas of information security, such as those described in this publication, are often documented in the risk analysis, accreditation statements, or procedural manuals. However, any controversial, atypical, or uncommon policies will also need formal statements. Atypical policies may include areas in which the system policy varies from organizational policy or from normal practice within the organization. The documentation for a typical policy contains a statement explaining the reason for deviation from the organization's standard policy.

### 5.4.3 System-Specific Policy Implementation

Technology plays an important role in enforcing system-specific policies but it is not solely responsible for meeting an organization’s security needs. When technology is used to enforce policy, it is important to consider manual methods. For example, technical system-based controls could be used to limit the printing of confidential reports to a specific printer. However, corresponding physical security measures would also have to be in place to limit access to the printer output or the desired security objective would not be achieved.

Technological methods frequently used to implement system-security policy are likely to include the use of logical access controls. Some examples of access controls would be: separation of duties, which is a control designed to address the potential for abuse of authorized privileges and helps reduce the risk of malevolent activity without collusion; and least privilege, which allows only authorized access for users or processes acting on behalf of users that is necessary to accomplish assigned tasks in accordance with organizational missions and business functions. However, there are other automated means of enforcing or supporting security policy that
typically supplement logical access controls. For example, intrusion detection software can alert
system administrators to suspicious activity or even take action to stop such activity. 

Technology-based enforcement of system-security policy has both advantages and disadvantages. A system, properly designed, programmed, installed, configured, and maintained, consistently enforces policy within the system, although no system can force users to follow all procedures. Management controls also play an important role in policy enforcement, so neglecting them would be detrimental to the organization. In addition, deviations from the policy may sometimes be necessary and appropriate; such deviations may be difficult to implement easily with some technical controls. This situation occurs frequently if implementation of the security policy is too rigid, which can occur when the system analysts fail to anticipate contingencies and prepare for them.

## 5.5 Interdependencies

Policy is related to many of the topics covered in this publication:

* Program Management. Policy is used to establish an organization's information security program and is therefore closely tied to program management and administration. Both program and system-specific policy may be established in any of the areas covered in this publication. For example, an organization may wish to have a consistent approach to contingency planning for all its systems and would issue appropriate program policy to do so. On the other hand, it may decide that its systems are sufficiently independent of each other that system owners can deal with incidents on an individual basis.

* Access Controls. System-specific policy is often implemented using access controls. For example, it may be a policy decision that only two individuals in an organization are authorized to run a check-printing program. Access controls are used by the system to implement or enforce this policy.

* Links to Broader Organizational Policies. It is important to understand that information security policies are often extensions of other organizational policies. Support and coordination should be reciprocal between information security and other organizational policies to minimize confusion. For example, an organization's email policy would likely be relevant to its broader policy on privacy.

## 5.6 Cost Considerations

A number of potential costs are associated with developing and implementing information security policies. The most significant costs are implementing the policy and addressing its subsequent impacts on the organization, its resources, and personnel. The establishment of an information security program, accomplished through policy, likely does not come at a negligible cost.

Other costs may be those incurred through the policy development process. Numerous administrative and management activities may be required for drafting, reviewing, coordinating, clearing, disseminating, and publicizing policies. In many organizations, successful policy implementation may require additional staffing and training. In general, the costs to an organization for information security policy development and implementation will be dependent upon how extensive the change must be in order for management to decide that an acceptable level of risk has been reached.

The cost of securing information and systems is unavoidable. The objective is to ensure that security protections are commensurate with risk by striking a balance between the protections required to meet the security objectives of the organization and the cost of such protections.

