------

-----

# Module 1: Understand Access Control Concepts:-

-----------

----

## 1.What is Security Control?

- A control is a safeguard or countermeasure designed to preserve Confidentiality, Integrity and Availability of data. This, of course, is the CIA Triad.  

- Access control involves limiting what objects can be available to what subjects according to what rules. We will further define objects, subjects and rules later in this chapter. For now, remember these three words, as they are the foundation upon which we will build. 

- One brief example of a control is a firewall, which is included in a system or network to prevent something from the outside from coming in and disturbing or compromising the environment. The firewall can also prevent information on the inside from going out into the Web where it could be viewed or accessed by unauthorized individuals.

------

------------

Imagine you have some important information that you want to keep safe. There are three main things you need to protect:

1. Confidentiality: This means making sure that only authorized people can access the information. You don't want just anyone to be able to see it or know about it.
    
2. Integrity: This is about ensuring that the information remains accurate and reliable. You don't want someone to tamper with or change the information without your knowledge.
    
3. Availability: This refers to making sure that the information is accessible when you need it. You don't want the information to be unavailable or inaccessible when you require it.
    

To achieve these goals, you use controls, which are like safeguards or protections. One example of a control is a firewall. Think of a firewall as a barrier or a wall that stands between your information and the outside world. It prevents unauthorized access from the outside, so nobody can get in and disturb or compromise your information. Similarly, it also prevents your information from going out into the internet where it could be seen or accessed by unauthorized individuals.

In simple terms, controls are like security measures that you put in place to keep your information safe and secure. They help you control who can access the information, prevent unauthorized changes, and ensure that the information is available when you need it.

------------

---------------

## 2.Controls Overview

- It can be argued that access controls are the heart of an information security program. Earlier in this course we looked at security principles through foundations of risk management, governance, incident response, business continuity and disaster recovery. But in the end, security all comes down to, “who can get access to organizational assets (buildings, data, systems, etc.) and what can they do when they get access?”

- Access controls are not just about restricting access to information systems and data, but also about allowing access. It is about granting the appropriate level of access to authorized personnel and processes and denying access to unauthorized functions or individuals.

- Access is based on three elements:
	 1. A subject can be defined as any entity that requests access to our assets. The entity requesting access may be a user, a client, a process or a program, for example. A subject is the initiator of a request for service; therefore, a subject is referred to as “active.”

		A subject:
		
		- Is a user, a process, a procedure, a client (or a server), a program, a device such as an endpoint, workstation, smartphone or removable storage device with onboard firmware.
		- Is active: It initiates a request for access to resources or services.
		- Requests a service from an object.
		- Should have a level of clearance (permissions) that relates to its ability to successfully access services or resources.

	 2. By definition, anything that a subject attempts to access is referred to as an object. An object is a device, process, person, user, program, server, client or other entity that responds to a request for service. Whereas a subject is active in that it initiates a request for a service, an object is passive in that it takes no action until called upon by a subject. When requested, an object will respond to the request it receives, and if the request is wrong, the response will probably not be what the subject really wanted either.

		Note that by definition, objects do not contain their own access control logic. Objects are passive, not active (in access control terms), and must be protected from unauthorized access by some other layers of functionality in the system, such as the integrated identity and access management system. An object has an owner, and the owner has the right to determine who or what should be allowed access to their object. Quite often the rules of access are recorded in a rule base or access control list.
		
		An object:
		
		- Is a building, a computer, a file, a database, a printer or scanner, a server, a communications resource, a block of memory, an input/output port, a person, a software task, thread or process.
		- Is anything that provides service to a user.
		- Is passive.
		- Responds to a request.
		- May have a classification.
	
	 3. An access rule is an instruction developed to allow or deny access to an object by comparing the validated identity of the subject to an access control list. One example of a rule is a firewall access control list. By default, firewalls deny access from any address to any address, on any port. For a firewall to be useful, however, it needs more rules. A rule might be added to allow access from the inside network to the outside network. Here we are describing a rule that allows access to the object “outside network” by the subject having the address “inside network.” In another example, when a user (subject) attempts to access a file (object), a rule validates the level of access, if any, the user should have to that file. To do this, the rule will contain or reference a set of attributes that define what level of access has been determined to be appropriate.

		A rule can:
		
		- Compare multiple attributes to determine appropriate access.
		- Allow access to an object.
		- Define how much access is allowed.
		- Deny access to an object.
		- Apply time-based access.

------------

---------

- Access controls are like the heart of a security program that protects information. We've already learned about different security principles like risk management, incident response, and others. But at the core, security is all about answering two important questions: "Who can get access to the organization's assets like buildings, data, and systems?" and "What can they do once they have access?"

- Access controls are the mechanisms that help answer these questions. They are not just about restricting access to information and systems, but also about allowing access to the right people and processes. It's important to grant the appropriate level of access to authorized individuals and functions, while denying access to unauthorized ones.

- To determine access, three elements come into play:

1. Subjects: These are the individuals, processes, or entities that are trying to access the organization's assets. For example, employees, contractors, or even automated systems could be subjects.
    
2. Objects: These are the things that the subjects are trying to access, such as data, systems, buildings, or any other valuable assets that need protection.
    
3. Rules: These are the guidelines or criteria that define how access is granted or denied. Rules can be based on factors like user roles, job responsibilities, security clearances, or even time of day.
    

- Access controls ensure that only the right subjects have access to the appropriate objects based on the defined rules. They play a crucial role in maintaining the security of an organization's assets by preventing unauthorized access and ensuring that access is given to those who need it.

-----------

----------------

## 3.Controls Assessments

- Risk reduction depends on the effectiveness of the control. It must apply to the current situation and adapt to a changing environment. 

- Consider a scenario where part of an office building is being repurposed for use as a secure storage facility. Due to the previous use of the area, there are 5 doors which must be secured before confidential files can be stored there. When securing a physical location, there are several things to consider. To keep the information the most secure, it might be recommended to install biometric scanners on all doors. A site assessment will determine if all five doors need biometric scanners, or if only one or two doors need scanners. The remaining doors could be permanently secured, or if the budget permits, the doors could be removed and replaced with a permanent wall. Most importantly, the cost of implementing the controls must align with the value of what is being protected.  If multiple doors secured by biometric locks are not necessary, and the access to the area does not need to be audited, perhaps a simple deadbolt lock on all of the doors will provide the correct level of control.

-------------

--------

## 4.Defense in Depth

- As you can see, we are not just looking at system access. We are looking at all access permissions including building access, access to server rooms, access to networks and applications and utilities. These are all implementations of access control and are part of a layered defense strategy, also known as defense in depth, developed by an organization.

- Defense in depth describes an information security strategy that integrates people, technology and operations capabilities to establish variable barriers across multiple layers and missions of the organization. It applies multiple countermeasures in a layered fashion to fulfill security objectives. Defense in depth should be implemented to prevent or deter a cyberattack, but it cannot guarantee that an attack will not occur. 

- A technical example of defense in depth, in which multiple layers of technical controls are implemented, is when a username and password are required for logging in to your account, followed by a code sent to your phone to verify your identity. This is a form of multi-factor authentication using methods on two layers, something you have and something you know. The combination of the two layers is much more difficult for an adversary to obtain than either of the authentication codes individually. 

- Another example of multiple technical layers is when additional firewalls are used to separate untrusted networks with differing security requirements, such as the internet from trusted networks that house servers with sensitive data in the organization. When a company has information at multiple sensitivity levels, it might require the network traffic to be validated by rules on more than one firewall, with the most sensitive information being stored behind multiple firewalls.

- For a non-technical example, consider the multiple layers of access required to get to the actual data in a data center. First, a lock on the door provides a physical barrier to access the data storage devices. Second, a technical access rule prevents access to the data via the network. Finally, a policy, or administrative control defines the rules that assign access to authorized individuals.

----

-----

## 5.Principle of Least Privilege

- The Principle of Least Privilege is a standard of permitting only minimum access necessary for users or programs to fulfill their function. Users are provided access only to the systems and programs they need to perform their specific job or tasks.

--------------------

-----------------

## 6.Examples of Least Privilege

- To preserve the confidentiality of information and ensure that it is only available to personnel who are authorized to see it, we use privileged access management, which is based on the principle of least privilege. That means each user is granted access only to the items they need and nothing further.  

- For example, only individuals working in billing will be allowed to view consumer financial data, and even fewer individuals will have the authority to change or delete that data. This maintains confidentiality and integrity while also allowing availability by providing administrative access with an appropriate password or sign-on that proves the user has the appropriate permissions to access that data.  

- Sometimes it is necessary to allow users to access the information via a temporary or limited access, for instance, for a specific time period or just within normal business hours. Or access rules can limit the fields that the individuals can have access to. One example is a healthcare environment. Some workers might have access to patient data but not their medical data. Individual doctors might have access only to data related to their own patients. In some cases, this is regulated by law, such as HIPAA in the United States, and by specific privacy laws in other countries. 

- Systems often monitor access to private information, and if logs indicate that someone has attempted to access a database without the proper permissions, that will automatically trigger an alarm. The security administrator will then record the incident and alert the appropriate people to take action.  

- The more critical information a person has access to, the greater the security should be around that access. They should definitely have multi-factor authentication, for instance.

----------

-------------

## 7.Privileged Access Management

- Privileged access management provides the first and perhaps most familiar use case. Consider a human user identity that is granted various create, read, update, and delete privileges on a database. Without privileged access management, the system’s access control would have those privileges assigned to the administrative user in a static way, effectively “on” 24 hours a day, every day. Security would be dependent upon the login process to prevent misuse of that identity. Just-in-time privileged access management, by contrast, includes role-based specific subsets of privileges that only become active in real time when the identity is requesting the use of a resource or service.

------------

------------

- Imagine you have a database, and there is a user who has special privileges to create, read, update, and delete data in that database. This user is an administrative user who needs these privileges to perform certain tasks.

- Now, without privileged access management, the system's access control would assign these privileges to the administrative user in a static way. This means that the user would have these privileges enabled all the time, 24 hours a day, every day. This could pose a security risk because if someone unauthorized gains access to that administrative user account, they would have full control over the database all the time.

- Here's where privileged access management comes in:

- Privileged access management (PAM) provides a solution to this security issue. It introduces the concept of "just-in-time" access. With just-in-time privileged access management, the administrative user is only granted specific subsets of privileges when they are actively needed.

- For example, let's say the administrative user needs to perform a task that requires the ability to delete data. Instead of having the delete privilege enabled all the time, the just-in-time privileged access management assigns that privilege to the administrative user dynamically and in real-time when they request to perform a delete operation.

- This approach improves security because the privileges are not permanently assigned to the administrative user. Instead, they are assigned on-demand and for a specific task or resource. This reduces the risk of unauthorized access and misuse of privileges because the administrative user only has the necessary privileges when they need them.

- In summary, privileged access management ensures that privileged user accounts have access to specific privileges only when they are actively required. It enhances security by minimizing the time window in which potential misuse can occur and reduces the risk associated with having static, always-on administrative privileges.

------------

----------

## 8.Privileged Accounts

- Privileged accounts are those with permissions beyond those of normal users, such as managers and administrators. 

- Broadly speaking, these accounts have elevated privileges and are used by many different classes of users, including: 

- Systems administrators, who have the principal responsibilities for operating systems, applications deployment and performance management. 
- Help desk or IT support staff, who often need to view or manipulate endpoints, servers and applications platforms by using privileged or restricted operations. 
- Security analysts, who may require rapid access to the entire IT infrastructure, systems, endpoints and data environment of the organization. 

- Other classes of privileged user accounts may be created on a per-client or per-project basis, to allow a member of that project or client service team to have greater control over data and applications. 

- These few examples indicate that organizations often need to delegate the capability to manage and protect information assets to various managerial, supervisory, support or leadership people, with differing levels of authority and responsibility. This delegation, of course, should be contingent upon trustworthiness, since misuse or abuse of these privileges could lead to harm for the organization and its stakeholders. 

- Typical measures used for moderating the potential for elevated risks from misuse or abuse of privileged accounts include the following: 

- More extensive and detailed logging than regular user accounts. The record of privileged actions is vitally important, as both a deterrent (for privileged account holders that might be tempted to engage in untoward activity) and an administrative control (the logs can be audited and reviewed to detect and respond to malicious activity). 
- More stringent access control than regular user accounts. As we will see emphasized in this course, even nonprivileged users should be required to use MFA methods to gain access to organizational systems and networks. Privileged users—or more accurately, highly trusted users with access to privileged accounts—should be required to go through additional or more rigorous authentication prior to those privileges. Just-in-time identity should also be considered as a way to restrict the use of these privileges to specific tasks and the times in which the user is executing them. 
- Deeper trust verification than regular user accounts. Privileged account holders should be subject to more detailed background checks, stricter nondisclosure agreements and acceptable use policies, and be willing to be subject to financial investigation. Periodic or event-triggered updates to these background checks may also be in order, depending on the nature of the organization’s activities and the risks it faces. 
- More auditing than regular user accounts. Privileged account activity should be monitored and audited at a greater rate and extent than regular usage.

-----------

-----------

- Privileged accounts are special accounts that have more permissions than regular user accounts. They are typically used by people like managers, administrators, help desk staff, and security analysts who need to perform important tasks and have greater control over systems, applications, and data.

- For example:
- Systems administrators are responsible for managing operating systems and applications.
- Help desk or IT support staff need to access and manipulate various devices and applications to assist users.
- Security analysts require access to the entire IT infrastructure to monitor and protect against threats.
- Additional privileged accounts may be created for specific projects or clients, giving certain team members more control over data and applications.

- Organizations delegate these privileges to trusted individuals based on their roles and responsibilities. However, misuse or abuse of these privileges can be harmful to the organization and its stakeholders. So, measures are put in place to mitigate the risks associated with privileged accounts:

1. Logging: Privileged actions are logged extensively to deter inappropriate behavior and provide a record for auditing and detecting malicious activity.
    
2. Access control: Even nonprivileged users are required to use multifactor authentication (MFA) for accessing organizational systems. Privileged users undergo more rigorous authentication processes. Just-in-time identity can also be used, allowing privileges to be granted only when necessary for specific tasks.
    
3. Trust verification: Privileged account holders undergo detailed background checks, sign strict agreements, and comply with acceptable use policies. They may be subject to financial investigations, and periodic updates to background checks may be required.
    
4. Auditing: Privileged account activity is closely monitored and audited more extensively than regular user accounts.
    

- These measures help reduce the risks associated with privileged accounts by ensuring accountability, limiting unnecessary access, and detecting any unauthorized or malicious activities.

- In summary, privileged accounts have elevated permissions and are used by individuals with specific roles. Organizations implement measures such as logging, access control, trust verification, and auditing to mitigate the risks associated with these accounts and protect the organization and its stakeholders.

--------------

-------------

## 9.Segregation of Duties 

- A core element of authorization is the principle of segregation of duties (also known as separation of duties). Segregation of duties is based on the security practice that no one person should control an entire high-risk transaction from start to finish. Segregation of duties breaks the transaction into separate parts and requires a different person to execute each part of the transaction. For example, an employee may submit an invoice for payment to a vendor (or for reimbursement to themselves), but it must be approved by a manager prior to payment; in another instance, almost anyone may submit a proposal for a change to a system configuration, but the request must go through technical and management review and gain approval, before it can be implemented.

- These steps can prevent fraud or detect an error in the process before implementation. It could be that the same employee might be authorized to originally submit invoices regarding one set of activities, but not approve them, and yet also have approval authority but not the right to submit invoices on another. It is possible, of course, that two individuals can willfully work together to bypass the segregation of duties, so that they could jointly commit fraud. This is called collusion.

- Another implementation of segregation of duties is dual control. This would apply at a bank where there are two separate combination locks on the door of the vault. Some personnel know one of the combinations and some know the other, but no one person knows both combinations. Two people must work together to open the vault; thus, the vault is under dual control. 

## Two-Person Integrity 

- The two-person rule is a security strategy that requires a minimum of two people to be in an area together, making it impossible for a person to be in the area alone. Many access control systems prevent an individual cardholder from entering a selected high-security area unless accompanied by at least one other person. Use of the two-person rule can help reduce insider threats to critical areas by requiring at least two individuals to be present at any time. It is also used for life safety within a security area; if one person has a medical emergency, there will be assistance present.

--------------------

--------------

# Module 2: Understand Physical Access Controls:-

------------

----------

## 1. What Are Physical Security Controls? 

- Physical access controls are items you can physically touch. They include physical mechanisms deployed to prevent, monitor, or detect direct contact with systems or areas within a facility. Examples of physical access controls include security guards, fences, motion detectors, locked doors/gates, sealed windows, lights, cable protection, laptop locks, badges, swipe cards, guard dogs, cameras, mantraps/turnstiles, and alarms.

- Physical access controls are necessary to protect the assets of a company, including its most important asset, people. When considering physical access controls, the security of the personnel always comes first, followed by securing other physical assets.

------

------------

## 2.Types of Physical Access Controls

- Many types of physical access control mechanisms can be deployed in an environment to control, monitor and manage access to a facility. These range from deterrents to detection mechanisms. Each area requires unique and focused physical access controls, monitoring and prevention mechanisms. The following sections discuss many such mechanisms that may be used to control access to various areas of a site, including perimeter and internal security.

### Badge Systems and Gate Entry

- Physical security controls for human traffic are often done with technologies such as turnstiles and remotely or system-controlled door locks. For the system to identify an authorized employee, an access control system needs to have some form of enrollment station used to assign and activate an access control device. Most often, a badge is produced and issued with the employee’s identifiers, with the enrollment station giving the employee specific areas that will be accessible. In high-security environments, enrollment may also include biometric characteristics. In general, an access control system compares an individual’s badge against a verified database. If authenticated, the access control system sends output signals allowing authorized personnel to pass through a gate or a door to a controlled area. The systems are typically integrated with the organization’s logging systems to document access activity (authorized and unauthorized)

- A range of card types allow the system to be used in a variety of environments. These cards include:

- Bar code
- Magnetic stripe
- Proximity
- Smart
- Hybrid

## Environmental Design

- Crime Prevention through Environmental Design (CPTED) approaches the challenge of creating safer workspaces through passive design elements. This has great applicability for the information security community as security professionals design, operate and assess the organizational security environment. Other practices, such as standards for building construction and data centers, also affect how we implement controls over our physical environment. Security professionals should be familiar with these concepts so they can successfully advocate for functional and effective physical spaces where information is going to be created, processed and stored.

- CPTED provides direction to solve the challenges of crime with organizational (people), mechanical (technology and hardware) and natural design (architectural and circulation flow) methods. By directing the flow of people, using passive techniques to signal who should and should not be in a space and providing visibility to otherwise hidden spaces, the likelihood that someone will commit a crime in that area decreases.

## Biometrics

- To authenticate a user’s identity, biometrics uses characteristics unique to the individual seeking access. A biometric authentication solution entails two processes.

- Enrollment—during the enrollment process, the user’s registered biometric code is either stored in a system or on a smart card that is kept by the user.
- Verification—during the verification process, the user presents their biometric data to the system so that the biometric data can be compared with the stored biometric code.

- Even though the biometric data may not be secret, it is personally identifiable information, and the protocol should not reveal it without the user’s consent. Biometrics takes two primary forms, physiological and behavioral.

- Physiological systems measure the characteristics of a person such as a fingerprint, iris scan (the colored portion around the outside of the pupil in the eye), retinal scan (the pattern of blood vessels in the back of the eye), palm scan and venous scans that look for the flow of blood through the veins in the palm. Some biometrics devices combine processes together—such as checking for pulse and temperature on a fingerprint scanner—to detect counterfeiting.

- Behavioral systems measure how a person acts by measuring voiceprints, signature dynamics and keystroke dynamics. As a person types, a keystroke dynamics system measures behavior such as the delay rate (how long a person holds down a key) and transfer rate (how rapidly a person moves between keys).

- Biometric systems are considered highly accurate, but they can be expensive to implement and maintain because of the cost of purchasing equipment and registering all users. Users may also be uncomfortable with the use of biometrics, considering them to be an invasion of privacy or presenting a risk of disclosure of medical information (since retina scans can disclose medical conditions). A further drawback is the challenge of sanitization of the devices.

--------------

------------------

# Module 3: Understand Logical Access Controls:-

--------------

-------------

## 1.What are Logical Access Controls?

- Whereas physical access controls are tangible methods or mechanisms that limit someone from getting access to an area or asset, logical access controls are electronic methods that limit someone from getting access to systems, and sometimes even to tangible assets or areas. Types of logical access controls include: 

- Passwords
- Biometrics (implemented on a system, such as a smartphone or laptop)
- Badge/token readers connected to a system

- These types of electronic tools limit who can get logical access to an asset, even if the person already has physical access.

------------

--------------

## 2.Discretionary Access Control (DAC)

- Discretionary access control (DAC) is a specific type of access control policy that is enforced over all subjects and objects in an information system. In DAC, the policy specifies that a subject who has been granted access to information can do one or more of the following:

- Pass the information to other subjects or objects 
- Grant its privileges to other subjects 
- Change security attributes on subjects, objects, information systems or system components 
- Choose the security attributes to be associated with newly created or revised objects; and/or 
- Change the rules governing access control; mandatory access controls restrict this capability 

- Most information systems in the world are DAC systems. In a DAC system, a user who has access to a file is usually able to share that file with or pass it to someone else. This grants the user almost the same level of access as the original owner of the file. Rule-based access control systems are usually a form of DAC.

--------------

--------------

- Discretionary Access Control (DAC) is a type of access control policy that applies to subjects (users) and objects (files or resources) in a computer system. In DAC, the policy determines what a user can do with the information they have been given access to. Here are some things a user can typically do under DAC:

1. Share information: If a user has access to a file, they can pass that file to other users or objects in the system. This means they can share the file with others.
    
2. Grant privileges: The user can also give their own access privileges to other users. For example, if they have read and write access to a file, they can grant the same level of access to someone else.
    
3. Change security attributes: The user has the ability to modify security attributes of subjects, objects, information systems, or system components. This means they can change settings or properties related to security.
    
4. Set security attributes for new objects: When creating new objects or updating existing ones, the user can choose the security attributes associated with them. They can decide how the new objects should be protected.
    
5. Modify access control rules: The user has the power to change the rules that govern access control. However, this capability is restricted by mandatory access controls, which are another type of access control mechanism.
    

- Most computer systems in the world follow the DAC approach. In a DAC system, if a user has access to a file, they typically have the ability to share it with others or perform actions similar to the original owner of the file. Rule-based access control systems often fall under the category of DAC.

------

------

## 3.Mandatory Access Control (MAC)

- A mandatory access control (MAC) policy is one that is uniformly enforced across all subjects and objects within the boundary of an information system. In simplest terms, this means that only properly designated security administrators, as trusted subjects, can modify any of the security rules that are established for subjects and objects within the system. This also means that for all subjects defined by the organization (that is, known to its integrated identity management and access control system), the organization assigns a subset of total privileges for a subset of objects, such that the subject is constrained from doing any of the following:

- Passing the information to unauthorized subjects or objects 
- Granting its privileges to other subjects 
- Changing one or more security attributes on subjects, objects, the information system or system components 
- Choosing the security attributes to be associated with newly created or modified objects 
- Changing the rules governing access control 

- Although MAC sounds very similar to DAC, the primary difference is who can control access. With Mandatory Access Control, it is mandatory for security administrators to assign access rights or permissions; with Discretionary Access Control, it is up to the object owner’s discretion.

----------------

-------------------

- Mandatory Access Control (MAC) is a type of access control policy that is applied consistently to all users and resources in a computer system. In simple terms, it means that only trusted security administrators have the authority to modify security rules for users and resources in the system. MAC imposes certain restrictions on what users can do:

1. Sharing information: Users are not allowed to pass information to unauthorized users or resources. They cannot share sensitive data with others without proper authorization.
    
2. Granting privileges: Users cannot give their own access privileges to other users. They cannot assign permissions to others or grant them additional rights.
    
3. Changing security attributes: Users are restricted from modifying security attributes of users, resources, the system itself, or its components. They cannot change settings or properties related to security without proper authorization.
    
4. Setting security attributes for new objects: Users are not permitted to choose security attributes for new or modified objects on their own. The organization assigns a specific subset of privileges to each user for specific objects, and users cannot exceed those assigned privileges.
    
5. Modifying access control rules: Users are not allowed to change the rules that govern access control. Only trusted security administrators have the authority to modify these rules.
    

- The main difference between MAC and DAC lies in who has control over access. With MAC, only security administrators can assign access rights and permissions, while with DAC, it is at the discretion of the object owner. MAC provides a more rigid and centrally controlled approach to access control, ensuring consistent and mandatory enforcement of security rules throughout the system.

---------------------------

-----------------

## 4.Role-Based Access Control (RBAC)

- Role-based access control (RBAC), as the name suggests, sets up user permissions based on roles. Each role represents users with similar or identical permissions.

---------------------

-----------------------

# Module 4: Chapter 3 Summary

-----------------

-----------

- **Audit** - Independent review and examination of records and activities to assess the adequacy of system controls, to ensure compliance with established policies and operational procedures. NIST SP 1800-15B
- **Crime Prevention through Environmental Design (CPTED)** - An architectural approach to the design of buildings and spaces which emphasizes passive features to reduce the likelihood of criminal activity.
- **Defense in Depth** - Information security strategy integrating people, technology, and operations capabilities to establish variable barriers across multiple layers and missions of the organization. Source: NIST SP 800-53 Rev 4
- **Discretionary Access Control (DAC)** - A certain amount of access control is left to the discretion of the object’s owner, or anyone else who is authorized to control the object’s access. The owner can determine who should have access rights to an object and what those rights should be. NIST SP 800-192
- **Encrypt** - To protect private information by putting it into a form that can only be read by people who have permission to do so.
- **Firewalls** - Devices that enforce administrative security policies by filtering incoming traffic based on a set of rules.
- **Insider Threat** - An entity with authorized access that has the potential to harm an information system through destruction, disclosure, modification of data, and/or denial of service. NIST SP 800-32
- **iOS** - An operating system manufactured by Apple Inc. Used for mobile devices.
- **Layered Defense** - The use of multiple controls arranged in series to provide several consecutive controls to protect an asset; also called defense in depth. 
- **Linux** - An operating system that is open source, making its source code legally available to end users.
- **Log Anomaly** - A system irregularity that is identified when studying log entries which could represent events of interest for further surveillance.
- **Logging** - Collecting and storing user activities in a log, which is a record of the events occurring within an organization’s systems and networks. NIST SP 1800-25B.
- **Logical Access Control Systems** - An automated system that controls an individual’s ability to access one or more computer system resources, such as a workstation, network, application or database. A logical access control system requires the validation of an individual’s identity through some mechanism, such as a PIN, card, biometric or other token. It has the capability to assign different access privileges to different individuals depending on their roles and responsibilities in an organization. NIST SP 800-53 Rev.5.
- **Mandatory Access Control** - Access control that requires the system itself to manage access controls in accordance with the organization’s security policies.
- **Mantrap** - An entrance to a building or an area that requires people to pass through two doors with only one door opened at a time.
- **Object** - Passive information system-related entity (e.g., devices, files, records, tables, processes, programs, domains) containing or receiving information. Access to an object (by a subject) implies access to the information it contains. See subject. Source: NIST SP 800-53 Rev 4
- **Physical Access Controls** - Controls implemented through a tangible mechanism. Examples include walls, fences, guards, locks, etc. In modern organizations, many physical control systems are linked to technical/logical systems, such as badge readers connected to door locks.
- **Principle of Least Privilege** - The principle that users and programs should have only the minimum privileges necessary to complete their tasks. NIST SP 800-179
- **Privileged Account** - An information system account with approved authorizations of a privileged user. NIST SP 800-53 Rev. 4
- **Ransomware** - A type of malicious software that locks the computer screen or files, thus preventing or limiting a user from accessing their system and data until money is paid.
- **Role-based access control (RBAC)** - An access control system that sets up user permissions based on roles.
- **Rule** - An instruction developed to allow or deny access to a system by comparing the validated identity of the subject to an access control list.
- **Segregation of Duties** - The practice of ensuring that an organizational process cannot be completed by a single person; forces collusion as a means to reduce insider threats. Also commonly known as Separation of Duties.
- **Subject** - Generally an individual, process or device causing information to flow among objects or change to the system state. Source: NIST SP800-53 R4
- **Technical Controls** - The security controls (i.e., safeguards or countermeasures) for an information system that are primarily implemented and executed by the information system through mechanisms contained in the hardware, software or firmware components of the system.
- **Turnstile** - A one-way spinning door or barrier that allows only one person at a time to enter a building or pass through an area.
- **Unix** - An operating system used in software development.
- **User Provisioning** - The process of creating, maintaining and deactivating user identities on a system.
