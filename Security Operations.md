---------------

-----------

# Module 1: Understand Data Security

--------------

-------------

## 1. Data Handling

- Data itself goes through its own life cycle as users create, use, share and modify it. Many different models of the life of a data item can be found, but they all have some basic operational steps in common. The data security life cycle model is useful because it can align easily with the different roles that people and organizations perform during the evolution of data from creation to destruction (or disposal). It also helps put the different data states of in use, at rest and in motion, into context. Let’s take a closer look. 

- All ideas, data, information or knowledge can be thought of as going through six major sets of activities throughout its lifetime. Conceptually, these involve: 


### Create:- Creating the knowledge, which is usually tacit knowledge at this point.

### Store:- Storing or recording it in some fashion (which makes it explicit).

### USE:- Using the knowledge, which may cause the information to be modified, supplemented or partially deleted.

### Share:- Sharing the data with other users, whether as a copy or by moving the data from one location to another.

### Archive:- Archiving the data when it is temporarily not needed.

### Destroyed:- Destroying the data when it is no longer needed.

--------------------

-----------

## 2.Data Handling Practices

Data itself has value and must be handled appropriately.  In this section, we will explore the basics of classifying and labeling data to ensure it is treated and controlled in a manner consistent with the sensitivity of the data. In addition, we will complete the data life cycle by documenting retention requirements and ensuring data that is no longer in use is destroyed.

## Classification

- Businesses recognize that information has value and others might steal their advantage if the information is not kept confidential, so they classify it. These classifications dictate rules and restrictions about how that information can be used, stored or shared with others. All of this is done to keep the temporary value and importance of that information from leaking away. Classification of data, which asks the question “Is it secret?” determines the labeling, handling and use of all data. 

- Before any labels can be attached to sets of data that indicate its sensitivity or handling requirements, the potential impact or loss to the organization needs to be assessed. This is our first definition: Classification is the process of recognizing the organizational impacts if the information suffers any security compromises related to its characteristics of confidentiality, integrity and availability. Information is then labeled and handled accordingly. 

- Classifications are derived from laws, regulations, contract-specified standards or other business expectations. One classification might indicate “minor, may disrupt some processes” while a more extreme one might be “grave, could lead to loss of life or threaten ongoing existence of the organization.” These descriptions should reflect the ways in which the organization has chosen (or been mandated) to characterize and manage risks.  

- The immediate benefit of classification is that it can lead to more efficient design and implementation of security processes, if we can treat the protection needs for all similarly classified information with the same controls strategy.

------
- Businesses understand that their information is valuable and that it needs to be kept confidential to prevent others from taking advantage of it. To ensure this, they classify their information based on its importance and sensitivity. This classification helps establish rules and restrictions on how the information should be used, stored, and shared. The goal is to prevent the valuable information from leaking out and losing its competitive advantage.

- Before applying labels to data that indicate its sensitivity or handling requirements, businesses assess the potential impact or loss to their organization if the information is compromised. This assessment helps determine how the information should be classified. The classification process considers factors like confidentiality (keeping information secret), integrity (maintaining accuracy and trustworthiness), and availability (ensuring information is accessible when needed).

- Classifications are derived from various sources such as laws, regulations, contractual obligations, or internal business standards. Each classification reflects the level of risk and impact associated with the information. For example, one classification might indicate a minor impact that could disrupt some processes, while another classification could indicate a grave impact that may lead to loss of life or threaten the organization's existence.

- By classifying information, businesses can efficiently design and implement security processes. When information is classified, it allows for a consistent approach to applying security controls based on the classification level. This helps organizations effectively protect their information and manage risks according to their specific needs and expectations.

- In simple terms, classification is the process of categorizing information based on its sensitivity and potential impact to the organization. It helps establish rules for protecting the information and allows for more efficient security measures.

-----

- ## Labelling

- Security labels are part of implementing controls to protect classified information. It is reasonable to want a simple way of assigning a level of sensitivity to a data asset, such that the higher the level, the greater the presumed harm to the organization, and thus the greater security protection the data asset requires. This spectrum of needs is useful, but it should not be taken to mean that clear and precise boundaries exist between the use of “low sensitivity” and “moderate sensitivity” labeling, for example. 

- ### Data Sensitivity Levels and Labels 

- Unless otherwise mandated, organizations are free to create classification systems that best meet their own needs. In professional practice, it is typically best if the organization has enough classifications to distinguish between sets of assets with differing sensitivity/value, but not so many classifications that the distinction between them is confusing to individuals. Typically, two or three classifications are manageable, and more than four tend to be difficult. 

- Highly restricted: Compromise of data with this sensitivity label could possibly put the organization’s future existence at risk. Compromise could lead to substantial loss of life, injury or property damage, and the litigation and claims that would follow.
- Moderately restricted: Compromise of data with this sensitivity label could lead to loss of temporary competitive advantage, loss of revenue or disruption of planned investments or activities.
- Low sensitivity (sometimes called “internal use only”): Compromise of data with this sensitivity label could cause minor disruptions, delays or impacts.
- Unrestricted public data: As this data is already published, no harm can come from further dissemination or disclosure.

------------------

- Security labels are used to protect classified information and implement controls. These labels indicate the level of sensitivity or importance of a piece of data. The higher the sensitivity level, the more harm it could cause to the organization if it were compromised. Therefore, higher sensitivity data requires stronger security measures.

- It's helpful to have a range of sensitivity levels to meet different needs, but it's important to note that the boundaries between sensitivity levels are not always clear-cut. For example, there may not be a distinct line between "low sensitivity" and "moderate sensitivity" labels.

- When it comes to classifying data, organizations can develop their own systems that work best for them. It's generally recommended to have enough classifications to differentiate between different sets of data with varying levels of sensitivity or value. However, having too many classifications can confuse people. Typically, managing two or three classifications is more manageable, while having more than four can become difficult.

Here are some examples of sensitivity levels and their corresponding labels:

1. Highly restricted: Data with this sensitivity label is extremely critical. If this data is compromised, it could potentially threaten the organization's future existence. It could result in significant loss of life, injuries, damage to property, and lead to legal action and claims.
    
2. Moderately restricted: Data with this sensitivity label is important but not as critical as highly restricted data. If compromised, it could lead to the loss of temporary competitive advantage, loss of revenue, or disruption of planned investments or activities.
    
3. Low sensitivity (sometimes called "internal use only"): Data with this sensitivity label is less critical. If it's compromised, it may cause minor disruptions, delays, or impacts within the organization.
    
4. Unrestricted public data: This data is already publicly available, so there is no harm in further sharing or disclosing it.
    

These labels help organizations prioritize their security measures and allocate resources accordingly to protect their data based on its sensitivity level.

---------

##  Retention

- Information and data should be kept only for as long as it is beneficial, no more and no less. For various types of data, certain industry standards, laws and regulations define retention periods. When such external requirements are not set, it is an organization’s responsibility to define and implement its own data retention policy. Data retention policies are applicable both for hard copies and for electronic data, and no data should be kept beyond its required or useful life. Security professionals should ensure that data destruction is being performed when an asset has reached its retention limit. For the security professional to succeed in this assignment, an accurate inventory must be maintained, including the asset location, retention period requirement, and destruction requirements. Organizations should conduct a periodic review of retained records in order to reduce the volume of information stored and to ensure that only necessary information is preserved. 

- Records retention policies indicate how long an organization is required to maintain information and assets. Policies should guarantee that: 

- Personnel understand the various retention requirements for data of different types throughout the organization. 
- The organization appropriately documents the retention requirements for each type of information.
- The systems, processes and individuals of the organization retain information in accordance with the required schedule but no longer. 

- A common mistake in records retention is applying the longest retention period to all types of information in an organization. This not only wastes storage but also increases risk of data exposure and adds unnecessary “noise” when searching or processing information in search of relevant records. It may also be in violation of externally mandated requirements such as legislation, regulations or contracts (which may result in fines or other judgments). Records and information no longer mandated to be retained should be destroyed in accordance with the policies of the enterprise and any appropriate legal requirements that may need to be considered.

---------

- Retention refers to how long information and data should be kept by an organization. It's important to keep data for the right amount of time - neither too long nor too short. Different industries, laws, and regulations may have specific guidelines for how long certain types of data should be retained. If there are no external requirements, it's the organization's responsibility to define its own data retention policy.

- Data retention policies apply to both physical copies (like paper documents) and electronic data. It's crucial to ensure that data is not kept beyond its required or useful life. When data reaches its retention limit, security professionals should make sure that it is destroyed properly.

- To successfully manage data retention, accurate records must be maintained. This includes keeping track of where assets are located, the retention period required for each asset, and any requirements for destruction. Organizations should periodically review the records they retain to reduce unnecessary information and ensure that only necessary data is preserved.

- The goals of records retention policies are:

1. Ensuring that personnel understand the retention requirements for different types of data throughout the organization.
    
2. Documenting the retention requirements for each type of information in a proper manner.
    
3. Retaining information in accordance with the required schedule, but not beyond the necessary time.
    

- A common mistake in records retention is applying the longest retention period to all types of information within an organization. This leads to wasted storage space, increased risk of data exposure, and difficulties in finding relevant records. It may also violate external requirements, such as laws, regulations, or contracts, which can result in fines or other penalties. Records and information that are no longer required to be retained should be destroyed following the enterprise's policies and any relevant legal requirements.

-----

##  Destruction

- Data that might be left on media after deleting is known as remanence and may be a significant security concern. Steps must be taken to reduce the risk that data remanence could compromise sensitive information to an acceptable level. This can be done by one of several means:  

- Clearing the device or system, which usually involves writing multiple patterns of random values throughout all storage media (such as main memory, registers and fixed disks). This is sometimes called “overwriting” or “zeroizing” the system, although writing zeros has the risk that a missed block or storage extent may still contain recoverable, sensitive information after the process is completed.
- Purging the device or system, which eliminates (or greatly reduces) the chance that residual physical effects from the writing of the original data values may still be recovered, even after the system is cleared. Some magnetic disk storage technologies, for example, can still have residual “ghosts” of data on their surfaces even after being overwritten multiple times. Magnetic media, for example, can often be altered sufficiently to meet security requirements; in more stringent cases, degaussing may not be sufficient. 
- Physical destruction of the device or system is the ultimate remedy to data remanence. Magnetic or optical disks and some flash drive technologies may require being mechanically shredded, chopped or broken up, etched in acid or burned; their remains may be buried in protected landfills, in some cases.

- In many routine operational environments, security considerations may accept that clearing a system is sufficient. But when systems elements are to be removed and replaced, either as part of maintenance upgrades or for disposal, purging or destruction may be required to protect sensitive information from being compromised by an attacker.

-----
- Destruction refers to the process of getting rid of data in a way that ensures it cannot be recovered, reducing the risk of sensitive information falling into the wrong hands. When data is deleted, it may still remain on the media in a form known as remanence, which can pose a security concern. To mitigate this risk, various methods can be used:

1. Clearing: This involves writing multiple patterns of random values across all storage media, such as memory, registers, and fixed disks. It's like overwriting the data to make it harder to recover. However, there is a small chance that some sensitive information may still be retrievable if a block or storage area is missed during the process, especially if only zeros are written.
    
2. Purging: Purging goes a step further to eliminate or greatly reduce the chances of recovering residual physical effects from the original data. For example, certain magnetic disk storage technologies can retain faint traces of data even after multiple overwrites. Purging methods aim to make it extremely difficult or practically impossible to recover any remnants of the original data. Sometimes, degaussing (altering the magnetic field) may be sufficient, but in more stringent cases, additional measures may be necessary.
    
3. Physical Destruction: The most secure solution for data remanence is physically destroying the device or system. This can involve methods like shredding, chopping, breaking, acid etching, or burning. For instance, magnetic or optical disks and certain types of flash drives may need to be physically fragmented. The remains of the destroyed media can then be disposed of, often by burying them in protected landfills.
    

- In routine operational environments, clearing a system may be deemed sufficient for security purposes. However, when system elements are being replaced or disposed of, either during maintenance or upgrades, purging or destruction becomes necessary to safeguard sensitive information from potential attackers.

- The choice of destruction method depends on the sensitivity of the data, the level of security required, and the specific media involved. It's crucial to take appropriate measures to prevent unauthorized access to data and protect against any potential risks associated with remanence.

---

---

## 3.  Logging and Monitoring Security Events

- Logging is the primary form of instrumentation that attempts to capture signals generated by events. Events are any actions that take place within the systems environment and cause measurable or observable change in one or more elements or resources within the system. Logging imposes a computational cost but is invaluable when determining accountability. Proper design of logging environments and regular log reviews remain best practices regardless of the type of computer system. 

- Major controls frameworks emphasize the importance of organizational logging practices. Information that may be relevant to being recorded and reviewed include (but is not limited to): 

- user IDs
- system activities
- dates/times of key events (e.g., logon and logoff)
- device and location identity
- successful and rejected system and resource access attempts
- system configuration changes and system protection activation and deactivation events 

 - Logging and monitoring the health of the information environment is essential to identifying inefficient or improperly performing systems, detecting compromises and providing a record of how systems are used. Robust logging practices provide tools to effectively correlate information from diverse systems to fully understand the relationship between one activity and another. 

- Log reviews are an essential function not only for security assessment and testing but also for identifying security incidents, policy violations, fraudulent activities and operational problems near the time of occurrence. Log reviews support audits – forensic analysis related to internal and external investigations – and provide support for organizational security baselines. Review of historic audit logs can determine if a vulnerability identified in a system has been previously exploited. 

- It is helpful for an organization to create components of a log management infrastructure and determine how these components interact. This aids in preserving the integrity of log data from accidental or intentional modification or deletion and in maintaining the confidentiality of log data. 

- Controls are implemented to protect against unauthorized changes to log information. Operational problems with the logging facility are often related to alterations to the messages that are recorded, log files being edited or deleted, and storage capacity of log file media being exceeded. Organizations must maintain adherence to retention policy for logs as prescribed by law, regulations and corporate governance. Since attackers want to hide the evidence of their attack, the organization’s policies and procedures should also address the preservation of original logs. Additionally, the logs contain valuable and sensitive information about the organization.  Appropriate measures must be taken to protect the log data from malicious use.

------
- Logging is a way of recording important events and actions that happen within a computer system. It helps capture signals or information about these events. Events can be anything that causes a change in the system, and logging helps us keep track of what's happening. Logging comes with some computational cost, but it is crucial for accountability.

- Good logging practices involve designing the logging environment properly and regularly reviewing the logs. This is considered a best practice regardless of the type of computer system being used.

- Logging is emphasized in major control frameworks as it is important for organizations to have good logging practices. Some examples of information that should be recorded and reviewed include user IDs, system activities, dates and times of important events (like logging in and out), device and location information, successful and failed attempts to access the system and resources, system configuration changes, and activation and deactivation of system protection.

- Logging and monitoring the health of the information environment is essential for identifying problems with system performance, detecting security breaches, and keeping a record of system usage. It allows us to effectively analyze information from different systems to understand how one activity relates to another.

- Reviewing logs is not only important for security assessments and testing, but it also helps in identifying security incidents, policy violations, fraudulent activities, and operational issues soon after they occur. Log reviews are useful for audits and forensic analysis during internal and external investigations. They can help determine if a known vulnerability in a system has been exploited in the past.

- Creating a log management infrastructure and understanding how different components interact with each other is beneficial for organizations. It helps maintain the integrity of log data by preventing accidental or intentional modifications or deletions and ensures the confidentiality of log data.

- Controls are implemented to protect log information from unauthorized changes. Problems with the logging system often arise from tampering with recorded messages, editing or deleting log files, or exceeding the storage capacity of log file media. Organizations need to follow retention policies for logs as mandated by laws, regulations, and corporate governance. Since attackers want to hide evidence of their attacks, organizations should have policies and procedures in place to preserve original logs. Additionally, logs contain valuable and sensitive information about the organization, so appropriate measures should be taken to protect log data from being misused by malicious individuals.

-----

---

## 4.Event Logging Best Practices

- Different tools are used depending on whether the risk from the attack is from traffic coming into or leaving the infrastructure. Ingress monitoring refers to surveillance and assessment of all inbound communications traffic and access attempts. Devices and tools that offer logging and alerting opportunities for ingress monitoring include: 

- Firewalls
- Gateways
- Remote authentication servers
- IDS/IPS tools
- SIEM solutions
- Anti-malware solutions

- Egress monitoring is used to regulate data leaving the organization’s IT environment. The term currently used in conjunction with this effort is data loss prevention (DLP) or data leak protection. The DLP solution should be deployed so that it can inspect all forms of data leaving the organization, including: 

- Email (content and attachments)
- Copy to portable media
- File Transfer Protocol (FTP)
- Posting to web pages/websites
- Applications/application programming interfaces (APIs)

---

- Event logging best practices involve implementing effective monitoring and surveillance systems to track inbound and outbound network traffic and access attempts. Here are some simplified explanations of key concepts:

1. Ingress Monitoring: This refers to monitoring and assessing all incoming communications traffic and attempts to access the organization's network infrastructure. Tools used for ingress monitoring include:

- Firewalls: These help control and filter incoming network traffic.
- Gateways: They act as entry points into the network and can monitor and control access.
- Remote authentication servers: They verify the identity of users trying to access the network remotely.
- IDS/IPS tools: Intrusion Detection Systems (IDS) and Intrusion Prevention Systems (IPS) detect and prevent unauthorized access attempts.
- SIEM solutions: Security Information and Event Management (SIEM) solutions collect and analyze log data from various sources to identify security incidents.
- Anti-malware solutions: These tools detect and prevent malware from entering the network.

2. Egress Monitoring: This involves regulating the flow of data leaving the organization's IT environment. Data Loss Prevention (DLP) or Data Leak Protection tools are used for egress monitoring. These tools inspect different forms of data leaving the organization, including:

- Email (content and attachments): Monitoring the content and attachments of outgoing emails to prevent sensitive information from being leaked.
- Copy to portable media: Tracking data that is copied onto portable devices like USB drives to prevent unauthorized data transfer.
- File Transfer Protocol (FTP): Monitoring and controlling data transfers using FTP, a common method for sharing files.
- Posting to web pages/websites: Tracking data that is posted or uploaded to websites or web pages.
- Applications/APIs: Monitoring the data exchanged through applications or Application Programming Interfaces (APIs).

- By implementing these monitoring practices, organizations can enhance their security posture and detect potential threats or data breaches. It's important to choose the right tools and systems based on the specific risks and needs of the organization.

---------------

-------------

## 5. Encryption Overview

- Almost every action we take in our modern digital world involves cryptography. Encryption////// protects our personal and business transactions; digitally signed software updates verify their creator’s or supplier’s claim to authenticity. Digitally signed contracts, binding on all parties, are routinely exchanged via email without fear of being repudiated later by the sender. 

- Cryptography is used to protect information by keeping its meaning or content secret and making it unintelligible to someone who does not have a way to decrypt (unlock) that protected information. The objective of every encryption system is to transform an original set of data, called the plaintext, into an otherwise unintelligible encrypted form, called the ciphertext. 

- Properly used, singly or in combination, cryptographic solutions provide a range of services that can help achieve required systems security postures in many ways: 

- Confidentiality: Cryptography provides confidentiality by hiding or obscuring a message so that it cannot be understood by anyone except the intended recipient. Confidentiality keeps information secret from those who are not authorized to have it. 

- Integrity: hash functions and digital signatures can provide integrity services that allow a recipient to verify that a message has not been altered by malice or error. These include simple message integrity controls. Any changes, deliberate or accidental, will result in the two results (by sender and by recipient) being different. 


- An encryption system is the set of hardware, software, algorithms, control parameters and operational methods that provide a set of encryption services.

- Plaintext is the data or message in its normal, unencrypted form and format. Its meaning or value to an end user (a person or a process) is immediately available for use.

- Plaintext can be:

- image, audio or video files in their raw or compressed forms
- human-readable text and numeric data, with or without markup language elements for formatting and metadata
- database files or records and fields within a database
- or anything else that can be represented in digital form for computer processing, transmission and storage

- It is important to remember that plaintext can be anything—much of which is not readable to humans in the first place.

- ## Symmetric Encryption

- The central characteristic of a symmetric algorithm is that it uses the same key in both the encryption and the decryption processes. It could be said that the decryption process is just a mirror image of the encryption process. This image displays how symmetric algorithms work.

- The same key is used for both the encryption and decryption processes. This means that the two parties communicating need to share knowledge of the same key. This type of algorithm protects data, as a person who does not have the correct key would not be able to read the encrypted message. Because the key is shared, however, this can lead to several other challenges:

- If two parties suspect a specific communication path between them is compromised, they obviously can't share key material along that path. Someone who has compromised communications between the parties would also intercept the key.

- Distribution of the key is difficult, because the key cannot be sent in the same channel as the encrypted message, or the man-in-the-middle (MITM) would have access to the key. Sending the key through a different channel (band) than the encrypted message is called out-of-band key distribution. Examples of out-of-band key distribution would include sending the key via courier, fax or phone.
- Any party with knowledge of the key can access (and therefore change) the message.
- Each individual or group of people wishing to communicate would need to use a different key for each individual or group they want to connect with. This raises the challenge of scalability — the number of keys needed grows quickly as the number of different users or groups increases. Under this type of symmetric arrangement, an organization of 1,000 employees would need to manage 499,500 keys if every employee wanted to communicate confidentially with every other employee.


- # Encryption Overview

- Primary uses of symmetric algorithms:

- Encrypting bulk data (backups, hard drives, portable media)
- Encrypting messages traversing communications channels (IPsec, TLS)
- Streaming large-scale, time-sensitive data (audio/video materials, gaming, etc.)

- Other names for symmetric algorithms, which you may encounter, include:

- Same key
- Single key
- Shared key
- Secret key
- Session key

- An example of symmetric encryption is a substitution cipher, which involves the simple process of substituting letters for other letters, or more appropriately, substituting bits for other bits, based upon a cryptovariable. These ciphers involve replacing each letter of the plaintext with another that may be further down the alphabet.

- ##### Asymmetric Encryption

- Asymmetric encryption uses one key to encrypt and a different key to decrypt the input plaintext. This is in stark contrast to symmetric encryption, which uses the same key to encrypt and decrypt. For most security professionals, the math of asymmetric encryption can be left to the cryptanalysts and cryptographers to know.

- A user wishing to communicate using an asymmetric algorithm would first generate a key pair. To ensure the strength of the key generation process, this is usually done by the cryptographic application or the public key infrastructure (PKI) implementation without user involvement. One half of the key pair is kept secret; only the key holder knows that key. This is why it is called the private key. The other half of the key pair can be given freely to anyone who wants a copy. In many companies, it may be available through the corporate website or access to a key server. Therefore, this second half of the key pair is referred to as the public key.

- Note that anyone can encrypt something using the recipient’s public key, but only the recipient —with their private key—can decrypt it.

- Asymmetric key cryptography solves the problem of key distribution by allowing a message to be sent across an untrusted medium in a secure manner without the overhead of prior key exchange or key material distribution. It also allows for several other features not readily available in symmetric cryptography, such as the non-repudiation of origin and delivery, access control and data integrity.

- Asymmetric key cryptography also solves the problem of scalability. It does scale well as numbers increase, as each party only requires a key pair, the private and public keys. An organization with 100,000 employees would only need a total of 200,000 keys (one private and one public for each employee). This is less than half of the number of keys that would be required for symmetric encryption.

- The problem, however, has been that asymmetric cryptography is extremely slow compared with its symmetric counterpart. Asymmetric cryptography is impractical for everyday use in encrypting large amounts of data or for frequent transactions where speed is required. This is because asymmetric key cryptography is handling much larger keys and is mathematically intensive, thereby reducing the speed significantly.

- Let’s look at an example that illustrates the use of asymmetric cryptography to achieve different security attributes.

- The two keys (private and public) are a key pair; they must be used together. This means that any message that is encrypted with a public key can only be decrypted with the corresponding other half of the key pair, the private key. Similarly, signing a message with a sender’s private key can only be verified by the recipient decrypting its signature with the sender’s public key. Therefore, as long as the key holder keeps the private key secure, there exists a method of transmitting a message confidentially. The sender would encrypt the message with the public key of the receiver. Only the receiver with the private key would be able to open or read the message, providing confidentiality.

- This image shows how asymmetric encryption can be used to send a confidential message across an untrusted channel.

- ## Hashing

- Hashing takes an input set of data (of almost arbitrary size) and returns a fixed-length result called the hash value. A hash function is the algorithm used to perform this transformation. When used with cryptographically strong hash algorithms, this is the most common method of ensuring message integrity today.

- Hashes have many uses in computing and security, one of which is to create a message digest by applying such a hash function to the plaintext body of a message. 

- To be useful and secure, a cryptographic hash function must demonstrate five main properties: 

- Useful: It is easy to compute the hash value for any given message.
- Nonreversible: It is computationally infeasible to reverse the hash process or otherwise derive the original plaintext of a message from its hash value (unlike an encryption process, for which there must be a corresponding decryption process).
- Content integrity assurance: It is computationally infeasible to modify a message such that re-applying the hash function will produce the original hash value. 
- Unique: It is computationally infeasible to find two or more different, sensible messages that hash to the same value.
- Deterministic: The same input will always generate the same hash, when using the same hashing algorithm

- Cryptographic hash functions have many applications in information security, including digital signatures, message authentication codes and other forms of authentication. They can also be used for fingerprinting, to detect duplicate data or uniquely identify files, and as [checksums](https://learn.isc2.org/content/enforced/9541-CC-SPT-GLOBAL-1ED-1M/build/chapter_05/module_01/ch05_m01-Encryption_Overview.html?d2lSessionVal=dUQ4j60Ip2ybokY0gzQ7V6zKu&ou=9541&d2l_body_type=3#) to detect accidental data corruption. The operation of a hashing algorithm is demonstrated in this image.

- This is an example of a simple hashing function. The originator wants to send a message to the receiver and ensure that the message is not altered by noise or lost packets as it is transmitted. The originator runs the message through a hashing algorithm that generates a hash, or a digest of the message. The digest is appended to the message and sent together with the message to the recipient. Once the message is delivered, the receiver will generate their own digest of the received message (using the same hashing algorithm). The digest of the received message is compared with the digest sent by the originator. If the digests are the same, the received message is the same as the sent message.

- The problem with a simple hash function like this is that it does not protect against a malicious attacker that would be able to change both the message and the hash/digest by intercepting it in transit. The general idea of a cryptographic hash function can be summarized with the following formula:

 

- variable data input + hashing algorithm

- fixed bit size data output (the digest)

- Hash functions are very sensitive to any changes in the message. Because the size of the hash digest does not vary according to the size of the message, a person cannot tell the size of the message based on the digest.


- ## Hashing Deep Dive

- Hashing puts data through a hash function or algorithm to create an alphanumeric set of figures, or a digest, that means nothing to people who might view it. No matter how long the input is, the hash digest will be the same number of characters. Any minor change in the input, a misspelling, or upper case or lower case, will create a completely different hash digest. So you can use the hash digest to confirm that the input exactly matches what is expected or required, for instance, a password.

- For example, we pay our rent through automatic withdrawal, and it’s $5,000 a month. Perhaps someone at the bank or at the rental office thinks they can just change it to $50,000 and keep the extra money. They think no one will notice if they just add another zero to the number. However, that change will completely change the digest. Since the digest is different, it will indicate that someone corrupted the information by changing the value of the automatic withdrawal, and it will not go through. Hashing is an extra layer of defense.

- Before we go live with a software product provided by a third party, for instance, we have to make sure no one has changed anything since it was tested by you and the programmer. They will usually send you the digest of their code and you compare that to the original. This is also known as a Checksum. If you see a discrepancy, that means something has changed. Then the security coders will compare the original one and the new one, and sometimes it’s very tedious, but they have software that can do it for them. If it’s something a little more intricate, they may need to go line by line and find out where the bugs are or if some lines need to be fixed. Often these problems are not intentional; they sneak in when you are making final adjustments to the software.

- An incident occurred at the University of Florida many years ago, where a very reputable software source, Windows 2000 or Millennium, was provided to 50,000 students via CD-ROMs, and the copies were compromised. The problems were detected when the digests did not match on a distribution file.

-----

--------

# Module 2: Understand System Hardening:-

--------------

-----------
## 1.Configuration Management Overview

Configuration management is a process and discipline used to ensure that the only changes made to a system are those that have been authorized and validated. It is both a decision-making process and a set of control processes. If we look closer at this definition, the basic configuration management process includes components such as identification, baselines, updates and patches.  


### Identification: 

- This involves identifying and documenting all the components of a system, including hardware, software, and network elements. Each component is assigned a unique identifier to track its configuration.

### Baselines: 

- A security baseline is a minimum level of protection that can be used as a reference point. Baselines provide a way to ensure that updates to technology and architectures are subjected to the minimum understood and acceptable level of security requirements.

### Change Control:

- An update process for requesting changes to a baseline, by means of making changes to one or more components in that baseline. A review and approval process for all changes. This includes updates and patches.

### Verification and audit:

- A regression and validation process, which may involve testing and analysis, to verify that nothing in the system was broken by a newly applied set of changes. An audit process can validate that the currently in-use baseline matches the sum total of its initial baseline plus all approved changes applied in sequence.

# Configuration Management Overview

- Effective use of configuration management gives systems owners, operators, support teams and security professionals another important set of tools they can use to monitor and oversee the configuration of the devices, networks, applications and projects of the organization. An organization may mandate the configuration of equipment through standards and baselines. The use of standards and baselines can ensure that network devices, software, hardware and endpoint devices are configured in a consistent way and that all such devices are compliant with the security baseline established for the organization. If a device is found that is not compliant with the security baseline, it may be disabled or isolated into a quarantine area until it can be checked and updated.

### Inventory:

- Making an inventory, catalog or registry of all the information assets that the organization is aware of (whether they already exist, or there’s a wish list or need to create or acquire them) is the first step in any asset management process. It requires that we locate and identify all assets of interest, including (and especially) the information assets:

- You can’t protect what you don’t know you have.

- It becomes even more challenging to keep that inventory, and its health and status with respect to updates and patches, consistent and current, day in and day out. It is, in fact, quite challenging to identify every physical host and endpoint, let alone gather the data from them all.

### Baseline:

- A commercial software product, for example, might have thousands of individual modules, processes, parameter and initialization files or other elements. If any one of them is missing, the system cannot function correctly. The baseline is a total inventory of all the system’s components, hardware, software, data, administrative controls, documentation and user instructions.

- Once controls are in place to mitigate risks, the baselines can be referenced. All further comparisons and development are measured against the baselines.

- When protecting assets, baselines can be particularly helpful in achieving a minimal protection level of those assets based on value. Remember, if assets have been classified based on value, and meaningful baselines have been established for each of the classification levels, we can conform to the minimum levels required. In other words, if classifications such as high, medium and low are being used, baselines could be developed for each of our classifications and provide that minimum level of security required for each.

### Updates:

- Repairs, maintenance actions and updates are frequently required on almost all levels of systems elements, from the basic infrastructure of the IT architecture on up through operating systems, applications platforms, networks and user interfaces. Such modifications must be acceptance tested to verify that newly installed (or repaired) functionality works as required. They must also be regression tested to verify that the modifications did not introduce other erroneous or unexpected behaviors in the system. Ongoing security assessment and evaluation testing evaluates whether the same system that passed acceptance testing is still secure.

### Patches:

- Patch management mostly applies to software and hardware devices that are subject to regular modification. A patch is an update, upgrade or modification to a system or component. These patches may be needed to address a vulnerability or to improve functionality. The challenge for the security professional is maintaining all patches, since they can come at irregular intervals from many different vendors. Some patches are critical and should be deployed quickly, while others may not be as critical but should still be deployed because subsequent patches may be dependent on them. Standards such as the PCI DSS require organizations to deploy security patches within a certain time frame.

- There are some issues with the use of patches. Many organizations have been affected by a flawed patch from a reputable vendor that affected system functionality. Therefore, an organization should test the patch before rolling it out across the organization. This is often complicated by the lack of a testing environment that matches the production environment. Few organizations have the budget to maintain a test environment that is an exact copy of production. There is always a risk that the testing will not always be able to test everything, and problems may appear in production that were not apparent in the test environment. To the extent possible, patches should be tested to ensure they will work correctly in production.

- If the patch does not work or has unacceptable effects, it might be necessary to roll back to a previous (pre-patch) state. Typically, the criteria for rollback are previously documented and would automatically be performed when the rollback criteria were met.

- Many vendors offer a patch management solution for their products. These systems often have certain automated processes, or unattended updates, that allow the patching of systems without interaction from the administrator. The risk of using unattended patching should be weighed against the risk of having unpatched systems in the organization’s network. Unattended (or automated) patching might result in unscheduled outages as production systems are taken offline or rebooted as part of the patch process.

-----
- Configuration management is a process that helps organizations keep track of and control their devices, networks, applications, and projects. It involves using tools and techniques to monitor and oversee the configuration of these components to ensure they meet established standards and baselines.

- One important aspect of configuration management is maintaining an inventory. This means keeping a detailed record of all the devices, software, hardware, and endpoint devices that are part of the organization's infrastructure. By having an inventory, it becomes easier to manage and track these components.

- Baselines are another key element of configuration management. Baselines establish a standard or reference point for how devices and systems should be configured. They ensure that all components are set up consistently and in compliance with the organization's security requirements. If a device is found to deviate from the baseline, it may be temporarily isolated or disabled until it can be checked and updated to align with the established standards.

- Updates and patches are also important in configuration management. These refer to making necessary changes or enhancements to devices, software, and systems to address vulnerabilities, improve functionality, or fix issues. Regularly applying updates and patches helps keep the configuration up to date and secure.

- By effectively utilizing configuration management practices, systems owners, operators, support teams, and security professionals have the tools they need to monitor and control the configuration of various components within the organization. It promotes consistency, compliance, and security while ensuring that devices and systems are properly configured and maintained.

------

---

# Module 3: Understand Best Practice Security Policies

-------------------

-----------------

## 1. Common Security Policies

1. Data Handling Policy: This policy outlines how sensitive or confidential data should be handled and protected within an organization. It includes guidelines on data classification, storage, access controls, encryption, and data disposal to ensure data security and privacy.
    
2. Password Policy: A password policy sets rules and guidelines for creating and managing passwords within an organization. It typically includes requirements for password complexity, length, expiration, and restrictions to enhance the security of user accounts and prevent unauthorized access.
    
3. Acceptable Use Policy: An acceptable use policy defines the proper and acceptable use of an organization's computer systems, networks, and resources by employees or authorized users. It outlines guidelines for responsible and ethical use, prohibited activities, and consequences for policy violations to promote a safe and productive computing environment.
    
4. Bring Your Own Device (BYOD) Policy: A BYOD policy governs the use of personal devices, such as smartphones or laptops, for work purposes within an organization. It establishes rules for security measures, device registration, data access, and employee responsibilities to balance the benefits of using personal devices while ensuring data protection and network security.
    
5. Privacy Policy: A privacy policy explains how an organization collects, uses, stores, and protects personal information of individuals. It informs individuals about their privacy rights, data sharing practices, and how their information is secured. Privacy policies are typically provided to customers or users of a company's products or services.
    
6. Change Management Policy: A change management policy defines processes and procedures for managing changes to an organization's IT infrastructure or systems. It includes guidelines for requesting, reviewing, approving, and implementing changes, ensuring proper testing and documentation. The policy helps maintain system stability, minimize risks, and ensure that changes are properly controlled and tracked.
    

- These common security policies establish guidelines, rules, and procedures to promote security, privacy, and responsible use of resources within an organization. They help mitigate risks, protect sensitive data, and maintain a secure computing environment.

----------------

---------------

## 2.Change Management Components

The change management process includes the following components.


Change Management Components:

1. Requests for Changes: Change management begins with requests for changes, which are formal submissions made by individuals or teams to propose modifications to an organization's IT infrastructure or systems. These requests outline the desired changes, the reasons behind them, and any supporting information.
    
2. Approval: Once a change request is submitted, it goes through an approval process. This involves reviewing the request, assessing its feasibility, potential impact, and alignment with organizational goals and policies. The change control board or relevant stakeholders review and approve the change if it meets the necessary criteria.
    
3. Rollback: Rollback refers to the process of reverting back to the previous state or configuration in case a change implementation results in unexpected issues, disruptions, or adverse effects. It is a contingency plan that allows organizations to mitigate risks by undoing the change and restoring the system to its pre-change state.
    

- These three components are fundamental to change management. Requests for changes initiate the process, approvals ensure that changes are evaluated and authorized, and the rollback option provides a safety net in case changes do not go as planned. By following these components, organizations can effectively manage and control changes to their IT infrastructure, minimizing risks and ensuring smooth operations.

---------

----------

# Terms and Definitions

------------

-------

- **Application Server** - A computer responsible for hosting applications to user workstations. NIST SP 800-82 Rev.2
- **Asymmetric Encryption** - An algorithm that uses one key to encrypt and a different key to decrypt the input plaintext.
- **Checksum** - A digit representing the sum of the correct digits in a piece of stored or transmitted digital data, against which later comparisons can be made to detect errors in the data.
- **Ciphertext** - The altered form of a plaintext message so it is unreadable for anyone except the intended recipients. In other words, it has been turned into a secret.
- **Classification** - Classification identifies the degree of harm to the organization, its stakeholders or others that might result if an information asset is divulged to an unauthorized person, process or organization. In short, classification is focused first and foremost on maintaining the confidentiality of the data, based on the data sensitivity.
- **Configuration management** - A process and discipline used to ensure that the only changes made to a system are those that have been authorized and validated.
- **Cryptanalyst** - One who performs cryptanalysis which is the study of mathematical techniques for attempting to defeat cryptographic techniques and/or information systems security. This includes the process of looking for errors or weaknesses in the implementation of an algorithm or of the algorithm itself.
- **Cryptography** - The study or applications of methods to secure or protect the meaning and content of messages, files, or other information, usually by disguise, obscuration, or other transformations of that content and meaning.
- **Data Loss Prevention (DLP)** - System capabilities designed to detect and prevent the unauthorized use and transmission of information. 
- **Decryption** - The reverse process from encryption. It is the process of converting a ciphertext message back into plaintext through the use of the cryptographic algorithm and the appropriate key for decryption (which is the same for symmetric encryption, but different for asymmetric encryption). This term is also used interchangeably with the “deciphering.”
- **Degaussing** - A technique of erasing data on disk or tape (including video tapes) that, when performed properly, ensures that there is insufficient magnetic remanence to reconstruct data.
- **Digital Signature** - The result of a cryptographic transformation of data which, when properly implemented, provides the services of origin authentication, data integrity, and signer non-repudiation. NIST SP 800-12 Rev. 1
- **Egress Monitoring** - Monitoring of outgoing network traffic.
- **Encryption** - The process and act of converting the message from its plaintext to ciphertext. Sometimes it is also referred to as enciphering. The two terms are sometimes used interchangeably in literature and have similar meanings.
- **Encryption System** - The total set of algorithms, processes, hardware, software, and procedures that taken together provide an encryption and decryption capability.
- **Hardening** - A reference to the process of applying secure configurations (to reduce the attack surface) and locking down various hardware, communications systems, and software, including operating system, web server, application server, application, etc. Hardening is normally performed based on industry guidelines and benchmarks, such as those provided by the Center for Internet Security (CIS).
- **Hash Function** - An algorithm that computes a numerical value (called the hash value) on a data file or electronic message that is used to represent that file or message and depends on the entire contents of the file or message. A hash function can be considered to be a fingerprint of the file or message. NIST SP 800-152
- **Hashing** - The process of using a mathematical algorithm against data to produce a numeric value that is representative of that data. Source CNSSI 4009-2015
- **Ingress Monitoring** - Monitoring of incoming network traffic.
- **Message Digest** - A digital signature that uniquely identifies data and has the property such that changing a single bit in the data will cause a completely different message digest to be generated. NISTIR-8011 Vol.3
- **Operating System** - The software “master control application” that runs the computer. It is the first program loaded when the computer is turned on, and its main component, the kernel, resides in memory at all times. The operating system sets the standards for all application programs (such as the Web server) that run in the computer. The applications communicate with the operating system for most user interface and file management operations. NIST SP 800-44 Version 2
- **Patch** - A software component that, when installed, directly modifies files or device settings related to a different software component without changing the version number or release details for the related software component. Source: ISO/IEC 19770-2
- **Patch Management** - The systematic notification, identification, deployment, installation and verification of operating system and application software code revisions. These revisions are known as patches, hot fixes, and service packs. Source: CNSSI 4009
- **Plaintext** - A message or data in its natural format and in readable form; extremely vulnerable from a confidentiality perspective.
- **Records** - The recordings (automated and/or manual) of evidence of activities performed or results achieved (e.g., forms, reports, test results), which serve as a basis for verifying that the organization and the information system are performing as intended. Also used to refer to units of related data fields (i.e., groups of data fields that can be accessed by a program and that contain the complete set of information on particular items). NIST SP 800-53 Rev. 4
- **Records Retention** - A practice based on the records life cycle, according to which records are retained as long as necessary, and then are destroyed after the appropriate time interval has elapsed.
- **Remanence** - Residual information remaining on storage media after clearing. NIST SP 800-88 Rev. 1
- **Request for change (RFC)** - The first stage of change management, wherein a change in procedure or product is sought by a stakeholder.
- **Security Governance** - The entirety of the policies, roles, and processes the organization uses to make security decisions in an organization.
- **Social engineering** - Tactics to infiltrate systems via email, phone, text, or social media, often impersonating a person or agency in authority or offering a gift. A low-tech method would be simply following someone into a secure building.
- **Symmetric encryption** - An algorithm that uses the same key in both the encryption and the decryption processes.
- **Web Server** - A computer that provides World Wide Web (WWW) services on the Internet. It includes the hardware, operating system, Web server software, and Web site content (Web pages). If the Web server is used internally and not by the public, it may be known as an “intranet server.” NIST SP 800-44 Version 2
- **Whaling Attack** - Phishing attacks that attempt to trick highly placed officials or private individuals with sizable assets into authorizing large fund wire transfers to previously unknown entities.
