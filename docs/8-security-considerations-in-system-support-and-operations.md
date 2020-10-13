---
layout: default
title: 8 Security Considerations in System Support and Operations  
nav_order: 90 
---

# 8 Security Considerations in System Support and Operations
{: .no_toc }

1. TOC
{:toc}

System support and operations refers to all aspects involved in running a system. This includes both system administration and tasks external to the system that support its operation (e.g., maintaining documentation). It does not include system planning or design. The support and operation of any system—from a three-person local area network to a worldwide application serving thousands of users—is critical to maintaining the security of a system. Support and operations are routine activities that enable systems to function correctly. These include fixing software or hardware problems, installing and maintaining software, and helping users resolve problems.

The failure to consider security as part of the support and operations of systems, can be detrimental to the organization. Information security system literature includes examples of how organizations undermined their often-expensive security measures with poor documentation, old user accounts, conflicting software, or poor control of maintenance accounts. An organization’s policies and procedures often fail to address many of these important issues. Some major categories include:

* User support;
* Software support;
* Configuration management;
* Backups;
* Media controls;
* Documentation; and
* Maintenance

Even though the goals of system support and operation and information security are closely related, there is a distinction between the two. The primary goal of system support and operations is the continued and correct operation of the system, whereas the information security goals of a system include confidentiality, availability, and integrity.

This chapter addresses the support and operations activities directly related to security. Every control discussed in this publication relies, in one way or another, on system support and operations. However, this chapter focuses on areas not covered in other chapters. For example, operations personnel normally create user accounts on the system. This topic is covered in section 10.7. Similarly, the input from support and operations staff to the security awareness and training program is covered in section 10.2.

## 8.1 User Support

In many organizations, user support takes place through a service desk. Service desks can support an entire organization, a subunit, a specific system, or a combination of these. For smaller systems, the system administrator typically provides direct user support. Experienced users provide informal user support on most systems. It is not unusual for user support to be closely linked to the organization’s ability to handle incident response.

An important security consideration for user support personnel is being able to recognize which problems (brought to their attention by users) are security-related. For example, users’ inability to log on to a system may result from the disabling of their accounts due to too many failed access attempts. This could indicate the presence of malicious users trying to guess a user’s password.

In general, system support and operations staff need to be able to identify security problems, respond accordingly, and inform appropriate individuals. A wide range of possible security problems may exist; some will be internal to custom applications, while others apply to off-the-shelf products. Additionally, problems can be software- or hardware-based.

The more responsive and knowledgeable system support and operation staff personnel are, the less user support will be provided informally. The support other users provide can be valuable, but they may not be aware of all the issues across the organization or how they are related.

## 8.2 Software Support

Software is the heart of an organization's system operations, whatever the size and complexity of the system. Therefore, it is essential that software function correctly and be protected from corruption. There are many elements of software support.

The first element is controlling what software is used on a system. If users or systems personnel can install and execute any software on a system, the system is more vulnerable to viruses, unexpected software interactions, and software that may subvert or bypass security controls. One method of controlling software is to inspect or test software before it is install ed (e.g., determine compatibility with custom applications, identify other unforeseen interactions). This can apply to new software packages, upgrades, off-the-shelf products, or to custom software, as deemed appropriate. In addition to controlling the installation and execution of new software, organizations also oversee the configuration and use of powerful system utilities. System utilities can compromise the integrity of operating systems and logical access controls.

The second element in software support can be to ensure that software has not been modified without proper authorization. This involves the protection of software and backup copies and can be done with a combination of logical and physical access controls.

Many organizations also include a program to ensure that software is properly licensed, as required. For example, an organization may audit systems for illegal copies of copyrighted software. This problem is primarily associated with user systems (or devices), but can apply to any type of system.

## 8.3 Configuration Management

Closely related to software support is configuration management—the process of tracking and approving changes to the system. Configuration management can be formal or informal and normally addresses hardware, software, networking, and other changes. The primary security goal of configuration management is to ensure that changes to the system do not unintentionally or unknowingly diminish security. Some of the methods discussed under software support (e.g., such as inspecting and testing software changes) can be used. Chapter 7 discusses other methods. 

Note that the security goal is to know what changes occur, not to prevent security from being changed. There may be circumstances under which reducing security is deemed an acceptable risk due to the need to accomplish the mission. In such cases, the decrease in security is based on a decision by the authorizing official who considered all appropriate factors. Furthermore, the resulting increase in risk is monitored on an ongoing basis.

A second security goal of configuration management is to ensure that changes to the system are reflected in other documentation, such as the contingency plan. If the change is major, it may be necessary to reanalyze some or all of the security of the system. This is discussed in section 10.15.

## 8.4 Backups

Support and operations personnel and sometimes users back up software and data. This function is critical to contingency planning. The frequency of backups depends on how often data changes and how important those changes are. Consult with system administrators to determine what backup schedule is appropriate. Also, it is important to test that backup copies are actually usable. Finally, store backups securely (discussed below).

## 8.5 Media Controls

Media controls include a variety of measures to provide physical and environmental protection and accountability for digital and non-digital media. Examples of digital media include diskettes, magnetic tapes, external/removable hard disk drives, flash drives, compact disks, and digital video disks. Examples of non-digital media include paper and microfilm. From a security perspective, media controls are designed to prevent the loss of confidentiality, integrity, or availability of information, including data or software, when stored or disseminated outside of the system. This can include storage of information before it is input into the system and after it is output.

The extent of media control depends on many factors, including the type of data, the quantity of media, and the nature of the user environment. Physical and environmental protection is used to prevent unauthorized individuals from accessing the media and protects against such factors as heat, cold, or harmful magnetic fields. When necessary, logging the use of individual media (e.g., a tape cartridge) provides detailed accountability—so that the organizations may hold authorized individuals responsible for their actions. For more information on media protection, see section 10.10.

## 8.6 Documentation

Documentation of all aspects of system support and operations is important to ensure continuity and consistency. Formalizing operational practices and procedures with sufficient detail helps to eliminate security lapses and oversights, gives new personnel sufficiently detailed instructions, and provides a quality assurance function to help ensure that operations are performed correctly and efficiently.

The specific security implementation details of a system are also documented. This includes many types of documentation, such as security plans, contingency plans, risk analyses, and security policies and procedures. Much of this information, particularly risk and threat analyses, has to be protected against unauthorized disclosure. Security documentation also needs to be both current and accessible. Accessibility takes special factors into consideration such as the need to find the contingency plan during a disaster.

Some security documentation may need to be designed to fulfill the needs of different system roles. For this reason, many organizations separate documentation into policy and procedures. A security procedures manual may be written to inform system users on how to do their jobs securely. For systems operations and support staff, a security procedures manual may address a wide variety of technical and operational concerns in considerable detail.

## 8.7 Maintenance

System maintenance requires either physical or logical access to the system. Support and operations staff, hardware or software vendors, or third-party service providers may maintain a system. Maintenance may be performed on-site or remotely via communications connections. It may also be necessary to move equipment to a repair site for maintenance. If someone who does not typically have access to the system performs maintenance, then a security vulnerability is introduced.

In some circumstances, it may be necessary to take additional precautions (e.g., background investigation of service personnel) to prevent some problems such as "snooping around" the physical area. However, once someone has access to the system, it is very difficult for supervision to prevent damage done through the maintenance process.

Many systems provide maintenance accounts. These special login accounts are normally preconfigured at the factory with pre-set, widely-known passwords. It is critical to change these passwords or otherwise limit access to the accounts. Develop procedures to ensure that only authorized maintenance personnel have access to the preconfigured accounts. If the account is to be used remotely, authentication of the maintenance provider can be performed using call-back confirmation. This helps ensure that remote diagnostic activities actually originate from an established phone number at the vendor's site. Other helpful techniques include encryption and decryption of diagnostic communications, strong identification and authentication techniques such as tokens, and remote disconnect verification.

Manufacturers of larger systems and third-party providers may offer more diagnostic and support services, and larger systems may have diagnostic ports. It is critical to ensure that these ports are only used by authorized personnel, cannot be accessed by malicious users, and are only active when required.

## 8.8 Interdependencies

There are support and operations components in most of the controls discussed in this publication, such as:

* Personnel. Most support and operations staff have special access to the system. Some organizations conduct background checks on individuals in these positions. (See section 10.13);

* Incident Handling. Support and operations may include an organization's incident handling staff. Even if they are separate organizations, they need to work together to recognize and respond to incidents. (See section 10.8);

* Contingency Planning. Support and operations normally provides technical input to contingency planning and carries out the activities of creating backups, updating documentation, and practicing responses to contingencies. (See section 10.6);

* Security Awareness, Training, and Education. Support and operations staff are trained in security procedures and aware of the importance of security. In addition, they provide technical expertise needed to teach users how to secure their systems. (See section 10.2);

* Physical and Environmental. Support and operations staff often control the immediate physical area around the system. (See section 10.11);

* Technical Controls. The technical controls are installed, maintained, and used by support and operations staff. They create the user accounts, add users to access control lists, review audit logs for unusual activity, control bulk encryption over telecommunications links, and perform the countless operational tasks needed to use technical controls effectively. In addition, support and operations staff provide needed input to the selection of controls based on their knowledge of system capabilities and operational constraints.(See Chapter 10); and

* Assurance. Support and operations staff ensure that changes to a system do not introduce security vulnerabilities by using assurance methods to evaluate or test the changes and their effects on the system. Operational assurance is normally performed by support and operations staff. (See Chapter 7).

## 8.9 Cost Considerations

The cost of ensuring adequate security in day-to-day support and operations is largely dependent upon the size and characteristics of the operating environment and the nature of the processing being performed. It may not be necessary to hire additional support and operations security specialists. If sufficient support personnel are already available, it is important that they be trained in the security aspects of their assigned jobs. Initial and ongoing training is a cost of successfully incorporating security measures into support and operations activities.

Another cost is that associated with creating and updating documentation to ensure that security concerns are appropriately reflected in support and operations policies, procedures, and duties.
