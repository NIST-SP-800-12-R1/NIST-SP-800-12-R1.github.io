---
layout: default
title: 9 Cryptography  
nav_order: 100 
---

# 9 Cryptography
{: .no_toc }

1. TOC
{:toc}

Cryptography is a branch of mathematics based on the transformation of data. It is an important tool for protecting information and is used in many aspects of information security. For example, cryptography can help provide data confidentiality and integrity. These security objectives can be accomplished using various cryptographic algorithms such as electronic signatures, and advanced user authentication. Although modern cryptography relies upon advanced mathematics, users can reap its benefits without understanding its mathematical underpinnings.

NIST has published an array of Special Publications (SPs) and Federal Information Processing Standards (FIPS) that are applicable to the use of cryptography within the Federal Government. A list of such SPs and FIPS can be found in Appendix A of NIST SP 800-175B, Guideline for Using Crypto Standards: Cryptographic Mechanisms. Public Laws, Presidential Executive Orders and Directives, and other guidance from organizations in the Executive Office of the President drive the SPs and FIPS written by NIST. Legislative mandates, policies, and directives specific to cryptography are introduced in NIST SP 800-175A, Guideline for Using Crypto Standards: Directives, Mandates, and Policies.

Cryptography alone will not satisfy the information assurance needs of any organization. Rather, when combined with other security measures, cryptography is a useful tool for satisfying a wide spectrum of information security needs and requirements. This chapter describes fundamental aspects of the basic cryptographic technologies and some specific ways cryptography can be applied to improve security. The chapter also explores some of the important issues to be considered when incorporating cryptography into systems.

## 9.1 Uses of Cryptography

Cryptography is used to protect data both inside and outside the boundaries of a system. Data within a system may be sufficiently protected with logical and physical access controls (perhaps supplemented by cryptography). However, outside of the system, cryptography is sometimes the only way to protect data. For instance, data cannot be protected by the originator’s logical or physical access controls when in transit across communications lines or resident on another system. Cryptography provides a solution by protecting data even when the data is no longer in the control of the originator.

## 9.1.1 Data Encryption

One of the best ways to obtain cost-effective data confidentiality is through the use of encryption. Encryption transforms intelligible data, called plaintext, into an unintelligible form, called ciphertext. This is reversed through the process of decryption. One way to protect electronic data is by using the advanced encryption standard (AES). The AES algorithm is a cryptographic algorithm that can be used to encrypt and decrypt information. Once data is encrypted, the ciphertext does not have to be protected against disclosure. However, if ciphertext is modified, it will not decrypt correctly. A more comprehensive explanation of AES can be found in FIPS 197, Advanced Encryption Standard (AES).

Both secret and public key cryptography can be used for data encryption although not all public key algorithms provide for data encryption. To use a secret key algorithm, data is encrypted using a specific key. The same key must be used to decrypt the data. When public key cryptography is used for encryption, any party may use any other party's public key to encrypt a message. However, only the party with the corresponding private key can decrypt, and thus read, the message. There are several reasons to choose one form of cryptography over the other. For example, an organization may decide to go with public key cryptography because it is more secure and convenient to use since private keys do not have to be transmitted to anyone. In order for secret-key cryptography to function, the secret keys must be transmitted due to the fact that the same key is used for the encryption and decryption of that specific data. More detailed guidance on public key infrastructure (PKI) is available in NIST SP 800-32, Introduction to Public Key Technology and the Federal PKI Infrastructure, NIST SP 800-57 Part 3, Recommendation for Key Management: Part 3 – Application Specific Key Management Guidance, and NIST SP 800-152, A Profile for U.S. Federal Cryptographic Key Management Systems (CKMS).

### 9.1.2 Integrity

Integrity is a property whereby data has not been altered in an unauthorized manner since it was created, transmitted, or stored. In systems, it is not always possible for humans to scan information to determine if data has been erased, added, or modified. Even if scanning were possible, the individual may have no way of knowing what the correct data is supposed to be. For example, "do" may be changed to "do not," or $1,000 may be changed to $10,000. It is therefore desirable to have an automated means of detecting both intentional and unintentional modifications of data.

While error detection codes (e.g., parity bits) have long been used in communications protocols, to detect unintentional modifications, an attacker intercepting and modifying the message can also replace the message’s error detection code. Cryptography can effectively detect both intentional and unintentional modification.

### 9.1.3 Electronic Signatures

Today's systems store and process documents in electronic form. Having documents in electronic form permits rapid processing and transmission and improves overall efficiency. The approval of a paper document has traditionally been indicated by a written signature. What is needed, therefore, is the electronic equivalent of a written signature that can be recognized as having the same legal status as a written signature. In addition to the integrity protections discussed above, cryptography can provide a means of linking a document with a particular person, as is done with a written signature. Electronic signatures can use either secret key or public key cryptography. However, public key methods are generally easier to use.

Simply taking a digital picture of a written signature does not provide adequate security. Such a digitized written signature could easily be copied from one electronic document to another with no way to determine whether it is legitimate. Electronic signatures, on the other hand, can be validated uniquely for one message and only for that message. For example, a cryptographic hash function(10) , like SHA-3, can be used to increase the security and efficiency of a digital signature providing assurance that the original message could not have been altered to a different message with the same hash value, and hence, the same signature. To learn more about cryptographic hash functions, specifically SHA-3, see FIPS 202, SHA-3 Standard: Permutation-
Based Hash and Extendable-Output Functions.

`(10) A cryptographic hash function is a hash function that is designed to provide special properties including collision resistance, and preimage resistance, that are important for many applications in information security.`

#### 9.1.3.1 Secret Key Electronic Signatures
An electronic signature can be implemented using secret key message authentication codes, or MACs. For example, if two parties share a secret key, and one party receives data with a MAC that is correctly verified using the shared key, that party may assume that the other party signed the data. This also assumes that the two parties trust each other. Through the use of a MAC, data integrity and a form of electronic signature are obtained. Using additional controls, such as key notarization(11) and key attributes(12) , it is possible to provide an electronic signature even if the two parties do not trust each other.

`(11) Key Notarization – is a method, in conjunction with cryptographic facilities (called Key Notarization Facilities), that applies additional security to keys by identifying the sender and recipient, thus, providing assurance on the authenticity of the exchanged keys.`
`(12) Key Attributes – is a distinct identifier of an entity.`

#### 9.1.3.2 Public Key Electronic Signatures
Another type of electronic signature is called a digital signature and is implemented using public key cryptography. Data is electronically signed by applying the originator's private key to the data. (The exact mathematical process for doing this is not important for this discussion.) To increase the speed of the process, the private key is applied to a shorter form of the data, called a "hash" or "message digest," rather than to the entire set of data. The resulting digital signature can be stored or transmitted along with the data. The signature can be verified by any party using the public key of the signer. This feature is very useful, for example, when distributing signed copies of virus-free software. Any recipient can verify that the program remains virus-free. If the signature verifies properly, then the verifier has confidence that the data was not modified after being signed and that the owner of the public key was the signer.

NIST has published standards for a digital signature and a secure hash for use by the federal
government in FIPS 186-4, Digital Signature Standard and FIPS 180-4, Secure Hash Standard.

### 9.1.4 User Authentication

Authentication is a process that provides assurance of the source of information to a receiving entity. Cryptography can increase security in user authentication techniques. As discussed in
section 10.7, cryptography is the basis for several advanced authentication methods. Instead of communicating passwords over an open network, authentication can be performed by demonstrating knowledge of a cryptographic key. Using these methods, a one-time password, which is not susceptible to eavesdropping, can be used. User authentication can use either secret or public key cryptography.

## 9.2 Implementation Issues

This section explores several important issues to consider when using (e.g., designing,
implementing, integrating) cryptography in a system. NIST has developed several FIPS and SPs that apply to the implementation of cryptography in federal information and federal systems. A list of these FIPS and SPs is located in Appendix A of NIST SP 800-175B.

### 9.2.1 Selecting Design and Implementation Standards

NIST and other organizations have developed numerous standards for designing, implementing,
and using cryptography and for integrating it into automated systems. By using these standards, organizations can reduce costs and protect their investments in technology. Standards provide solutions that have been accepted by a wide community and reviewed by experts in relevant areas. Standards help ensure interoperability among different vendors' equipment, thus allowing an organization to select from various products in order to find cost-effective solutions.

Managers and users of systems choose the appropriate cryptographic standard based on a cost-
effectiveness analysis, trends in the standard's acceptance, and interoperability requirements. In addition, each standard is carefully analyzed to determine if it is applicable to the organization and the desired application.

### 9.2.2 Deciding between Software, Hardware, or Firmware Implementations

The trade-offs among security, cost, simplicity, efficiency, and ease of implementation need to be studied by managers acquiring various security products meeting a standard. Cryptography can be implemented in software, hardware, or firmware. Each has its related costs and benefits.

In general, software is less expensive and slower than hardware, although for large applications, hardware may be less expensive. In addition, software may be less secure, since it is more easily modified or bypassed than equivalent hardware products. Tamper resistance in hardware is usually considered more reliable.

In many cases, cryptography is implemented in a hardware device (e.g., electronic chip, ROM-protected processor), but is controlled by software. This software requires integrity protection to ensure that the hardware device is provided with correct information (e.g., controls, data) and is not bypassed. Thus, a hybrid solution is generally provided, even when the basic cryptography is implemented in hardware. Effective security requires correct management of the entire hybrid solution.

Firmware can be found in nearly every piece of technology used today, including cell phones, smart TVs, and even in USB keyboards. Thus, securing firmware implementations is critical. One way to protect your system is by purchasing hardware with built-in protection that prevents malicious firmware modification. For more information on hardening firmware, refer to NIST SP 800-147 , BIOS Protection Guidelines, and NIST SP 800-155 (DRAFT), BIOS Integrity
Measurement Guidelines.

### 9.2.3 Managing Keys

The security of information protected by cryptography directly depends upon the protection afforded to keys. All keys need to be protected against modification, and secret and private keys require protection against unauthorized disclosure. Key management involves the procedures and protocols, both manual and automated, used throughout the entire life cycle of the keys. This includes the generation, distribution, storage, entry, use, destruction, and archiving of cryptographic keys.

In a small community of users, public keys and their "owners" can be strongly bound by simply exchanging public keys (e.g., putting them on a CD-ROM or other media). However, conducting electronic business on a larger scale—potentially involving geographically and organizationally distributed users—necessitates a means for obtaining public keys electronically with a high degree of confidence in their integrity and binding to individuals. The support for the binding between a key and its owner is generally referred to as a public key infrastructure.

Users also need the ability to enter the community of key holders, generate keys (or have them
generated on their behalf), disseminate public keys, revoke keys (for example, in case of compromise of the private key), and change keys. In addition, it may be necessary to incorporate time/date stamping and to archive keys for verification of old signatures.

For more information on key management, see NIST SP 800-57 Part 1, Recommendation for Key Management, part 1: General, NIST SP 800-57 Part 2, Recommendation for Key Management, Part 2: Best Practices for Key Management Organization, and NIST SP 800-57 Part 3.

### 9.2.4 Security of Cryptographic Modules

Cryptography is typically implemented in a module of software, firmware, hardware, or some combination thereof. This module contains the cryptographic algorithm(s), certain control parameters, and temporary storage facilities for the key(s) being used by the algorithm(s). The proper functioning of cryptography requires the secure design, implementation, and use of the cryptographic module. This includes protecting the module against tampering.

Conformance to standards can be important for many reasons, including interoperability or strength of security provided. NIST established the Cryptographic Module Validation Program (CMVP) which validates cryptographic modules to FIPS 140- 2 , Security Requirements for Cryptographic Modules. The goal of the CMVP is to promote the use of validated cryptographic modules and provide federal agencies with a security metric to use in procuring equipment containing validated cryptographic modules. A list of modules that have been validated by NIST is available on the Computer Security Resource Center (CSRC) website.

FIPS 140-2 specifies the security requirements that will be satisfied by a cryptographic module
utilized within a security system protecting sensitive but unclassified information. The standard defines four security levels for cryptographic modules, with each level providing a significant increase in security over the preceding level. The four levels allow for cost-effective solutions that are appropriate for varying degrees of data sensitivity and different application environments. The user can select the best module for any given application or system, avoiding the cost of unnecessary security features.

### 9.2.5 Applying Cryptography to Networks

The use of cryptography within networking applications often requires special considerations. In these applications, the suitability of a cryptographic module may depend on its capability for handling special requirements imposed by locally attached communications equipment or by the network protocols and software.

Encrypted information, MACs, or digital signatures may require transparent communications protocols or equipment to avoid being misinterpreted by the communications equipment or software as control information. It may be necessary to format the encrypted information, MAC, or digital signature to ensure that it does not confuse the communications equipment or software. It is essential that cryptography satisfy the requirements imposed by the communications equipment and does not interfere with the proper and efficient operation of the network.

Data is encrypted on a network using either link encryption or end-to-end encryption. In general, link encryption is performed by service providers, such as a data communications provider. Link encryption encrypts all of the data along a communications path (e.g., a satellite link, telephone circuit, T3 line). Since link encryption also encrypts routing data, communications nodes need to decrypt the data to continue routing. In end-to-end encryption, data is encrypted when being passed through a network, but routing information remains visible. End-to-end encryption is generally performed by the end user organization. Some examples of modern usage of end-to-end encryption include Pretty Good Privacy (PGP) and Secure/Multipurpose Internet Mail Extensions (S/MIME) for email. It is possible to combine both types of encryption.

### 9.2.6 Complying with Export Rules

The U.S. Government controls the export of cryptographic implementations. The rules governing export can be quite complex since they consider multiple factors. Additionally, cryptography is a rapidly evolving field, and rules may change from time to time. Address questions concerning the export of cryptographic implementations to the appropriate legal counsel.

## 9.3 Interdependencies

There are many interdependencies among cryptography and other security controls highlighted in this publication. Cryptography both depends on other security safeguards and assists in providing them. For example:

* Physical Security. Physical protection of a cryptographic module is required to prevent—or at least detect—physical replacement or modification of the cryptographic system and the keys within it. In many environments (e.g., open offices, laptops), the cryptographic module itself has to provide the desired levels of physical security. In other environments (e.g., closed communications facilities, steel-encased Cash-Issuing Terminals), a cryptographic module may be safely employed within a secured facility.

* User Authentication. Cryptography can be used both to protect passwords that are stored in systems and to protect passwords that are communicated between systems. Furthermore, cryptographic-based authentication techniques may be used in conjunction with or in place of password-based techniques to provide stronger authentication of users.

* Logical Access Control. In many cases, cryptographic software may be embedded within a host system, and it may not be feasible to provide extensive physical protection to the host system. In these cases, logical access control may provide a means of isolating the cryptographic software from other parts of the host system, protect the cryptographic software from tampering, and safeguard the keys from replacement or disclosure. The use of such controls provides the equivalent of physical protection.

* Audit Trails. Cryptography may play a useful role in audit trails, which are used to help support electronic signatures. Audit records may implement electronic signatures for integrity, and cryptography may be needed to protect audit records stored on systems from disclosure or modification.

* Assurance. Assurance that a cryptographic module is properly and securely implemented is essential to the effective use of cryptography. NIST maintains validation programs for several of its standards for cryptography (see section 9.2.4). Vendors can have their products validated for conformance to the standard through a rigorous set of tests. Such testing provides increased assurance that a module meets stated standards, and system designers, integrators, and users can have greater confidence that validated products conform to accepted standards.

Cryptographic systems are monitored and periodically audited to ensure that they are still satisfying their security objectives. All parameters associated with correct operation of the cryptographic system are reviewed; operation of the system itself is periodically tested; and the results are audited. Certain information, such as secret keys or private keys in public key systems, are not subject to audit. However, non-secret or non-private keys could be used in a simulated audit procedure.

## 9.4 Cost Considerations

Using cryptography to protect information has both direct and indirect costs, which are determined in part by product availability. A wide variety of products exist for implementing cryptography in integrated circuits, add-on boards or adapters, and stand-alone units.

### 9.4.1 Direct Costs

The direct costs of cryptography include:

* Acquiring or implementing the cryptographic module and integrating it into the system. The medium (i.e., hardware, software, firmware, or a combination thereof) and various other issues such as level of security, logical and physical configuration, and special processing requirements will have an impact on cost; and

* Managing the cryptography and the cryptographic key generation, distribution, archiving, and disposal as well as security measures to protect the keys.

### 9.4.2 Indirect Costs

The indirect costs of cryptography include:

* A decrease in system or network performance, resulting from the additional overhead of applying cryptographic protection to stored or communicated data; and

* Changes in the way users interact with the system, resulting from more stringent security enforcement. However, cryptography can be made nearly transparent to the users so that the impact is minimal.


