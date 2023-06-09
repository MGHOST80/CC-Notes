
---------------

--------------
# Module 1: Understand Incident Response:-

--------------------------------------------------

-------------------------

## 1.Incident Terminology:-

### 1.Breach

- The loss of control, compromise, unauthorized disclosure, unauthorized acquisition, or any similar occurrence where: a person other than an authorized user accesses or potentially accesses personally identifiable information; or an authorized user accesses personally identifiable information for other than an authorized purpose. NIST SP 800-53 Rev. 5


### 2.Event

- Any observable occurrence in a network or system. NIST SP 800-61 Rev 2

### 3.Exploit

- A particular attack. It is named this way because these attacks exploit system vulnerabilities.

### 4.Incident

- An event that actually or potentially jeopardizes the confidentiality, integrity or availability of an information system or the information the system processes, stores or transmits.

### 5.Intrusion

- A security event, or combination of events, that constitutes a deliberate security incident in which an intruder gains, or attempts to gain, access to a system or system resource without authorization. IETF RFC 4949 Ver 2.

### 6.Threat

- Any circumstance or event with the potential to adversely impact organizational operations (including mission, functions, image or reputation), organizational assets, individuals, other organizations or the nation through an information system via unauthorized access, destruction, disclosure, modification of information and/or denial of service. NIST SP 800-30 Rev 1

### 7.Vulnerability

- Weakness in an information system, system security procedures, internal controls or implementation that could be exploited by a threat source. NIST SP 800-30 Rev 1

### 8.Zero Day

- A previously unknown system vulnerability with the potential of exploitation without risk of detection or prevention because it does not, in general, fit recognized patterns, signatures or methods.


---------------------

--------------------

## 2.The Goal of Incident Response

- Every organization must be prepared for incidents. Despite the best efforts of an organization’s management and security teams to avoid or prevent problems, it is inevitable that  adverse events will happen that have the potential to affect the business mission or objectives.

- The priority of any incident response is to protect life, health and safety. When any decision related to priorities is to be made, always choose safety first.

- The primary goal of incident management is to be prepared. Preparation requires having a policy and a response plan that will lead the organization through the crisis. Some organizations use the term “crisis management” to describe this process, so you might hear this term as well.

- An event is any measurable occurrence, and most events are harmless. However, if the event has the potential to disrupt the business’s mission, then it is called an incident. Every organization must have an  incident response plan that will help preserve business viability and survival.

- The incident response process is aimed at reducing the impact of an incident so the organization can resume the interrupted operations as soon as possible. Note that incident response planning is a subset of the greater discipline of business continuity management (BCM), which we will cover shortly.

--------------

-------

## 3. Components of the Incident Response Plan

- The incident response policy should reference an incident response plan that all employees will follow, depending on their role in the process. The plan may contain several procedures and standards related to incident response. It is a living representation of an organization’s incident response policy.

- The organization’s vision, strategy and mission should shape the incident response process. Procedures to implement the plan should define the technical processes, techniques, checklists and other tools that teams will use when responding to an incident.

- To prepare for incidents, here are the components commonly found in an incident response plan:

## 1.Preparation

- Develop a policy approved by management.
- Identify critical data and systems, single points of failure.
- Train staff on incident response.
- Implement an incident response team. (covered in subsequent topic)
- Practice Incident Identification. (First Response)
- Identify Roles and Responsibilities.
- Plan the coordination of communication between stakeholders.

## 2. Detection and Analysis

- Monitor all possible attack vectors.
- Analyze incident using known data and threat intelligence.
- Prioritize incident response.
- Standardize incident documentation.

## 3. Containment

- Gather evidence.
- Choose an appropriate containment strategy.
- Identify the attacker.
- Isolate the attack.

## 4. Post-Incident Activity

- Identify evidence that may need to be retained.
- Document lessons learned.

Retrospective

- Preparation
- Detection and Analysis
- Containment, Eradication and Recovery
- Post-incident Activity

-----------------

---------------

## 4.Incident Response Team

- Along with the organizational need to establish a Security Operations Center (SOC) is the need to create a suitable incident response team. A properly staffed and trained incident response team can be leveraged, dedicated or a combination of the two, depending on the requirements of the organization. 

- Many IT professionals are classified as first responders for incidents. They are the first ones on the scene and know how to differentiate typical IT problems from security incidents. They are similar to medical first responders who have the skills and knowledge to provide medical assistance at accident scenes and help get the patients to medical facilities when necessary. The medical first responders have specific training to help them determine the difference between minor and major injuries. Further, they know what to do when they come across a major injury. 

- Similarly, IT professionals need specific training so they can determine the difference between a typical problem that needs troubleshooting and a security incident that they need to report and address at a higher level. 

- A typical incident response team is a cross-functional group of individuals who represent the management, technical and functional areas of responsibility most directly impacted by a security incident. Potential team members include the following:

- Representative(s) of senior management
- Information security professionals
- Legal representatives
- Public affairs/communications representatives
- Engineering representatives (system and network)

- Team members should have training on incident response and the organization’s incident response plan. Typically, team members assist with investigating the incident, assessing the damage, collecting evidence, reporting the incident and initiating recovery procedures. They would also participate in the remediation and lessons learned stages and help with root cause analysis.

- Many organizations now have a dedicated team responsible for investigating any computer security incidents that take place. These teams are commonly known as computer incident response teams (CIRTs) or computer security incident response teams (CSIRTs). When an incident occurs, the response team has four primary responsibilities:

- Determine the amount and scope of damage caused by the incident.
- Determine whether any confidential information was compromised during the incident.
- Implement any necessary recovery procedures to restore security and recover from incident-related damage.
- Supervise the implementation of any additional security measures necessary to improve security and prevent recurrence of the incident.

----------------------

------------------

# Module 2: Understand Business Continuity (BC):-

--------------------------------------------

-----------------

## 1.The Importance of Business Continuity

- The intent of a business continuity plan is to sustain business operations while recovering from a significant disruption. An event has created a disturbance in the environment, and now you need to know how to maintain the business. 

- A key part of the plan is communication, including multiple contact methodologies and backup numbers in case of a disruption of power or communications. Many organizations will establish a phone tree, so that if one person is not available, they know who else to call. Organizations will go through their procedures and checklists to make sure they know exactly who is responsible for which action. No matter how many times they have flown, without fail, pilots go through a checklist before take-off. Similarly, there must be established procedures and a thorough checklist, so that no vital element of business continuity will be missed. 

- We call the appropriate individuals and start to activate the business continuity plan. Management must be included, because sometimes priorities may change depending on the situation. Individuals with proper authority must be there to execute operations, for instance, if there are critical areas that need to be shut down. 

- We need to have at hand the critical contact numbers for the supply chain, as well as law enforcement and other sites outside of the facility. For example, a hospital may suffer a severe cyberattack that affects communications from the pharmacy, the internet or phone lines. In the United States, in case of this type of cyberattack that knocks out communications, specific numbers in specific networks can bypass the normal cell phone services and use military-grade networks. Those will be assigned to authorized individuals for hospitals or other critical infrastructures in case of a major disruption or cyberattack, so they can still maintain essential activity.

## 2.Components of a Business Continuity Plan

- Business continuity planning (BCP) is the proactive development of procedures to restore business operations after a disaster or other significant disruption to the organization. Members from across the organization should participate in creating the BCP to ensure all systems, processes and operations are accounted for in the plan.

- The term business is used often, as this is mostly a business function as opposed to a technical one. However, in order to safeguard the confidentiality, integrity and availability of information, the technology must align with the business needs.

- Here are some common components of a comprehensive business continuity plan:

- List of the BCP team members, including multiple contact methods and backup members
- Immediate response procedures and checklists (security and safety procedures, fire suppression procedures, notification of appropriate emergency-response agencies, etc.)
- Notification systems and call trees for alerting personnel that the BCP is being enacted
- Guidance for management, including designation of authority for specific managers
- How/when to enact the plan
- Contact numbers for critical members of the supply chain (vendors, customers, possible external emergency providers, third-party partners)

----------------

-------------------

# Module 3: Understand Disaster Recovery (DR):-

------------

-----------

## 1.The Goal of Disaster Recovery

- In the Business Continuity module, the essential elements of business continuity planning were explored. Disaster recovery planning steps in where BC leaves off. When a disaster strikes or an interruption of business activities occurs, the Disaster recovery plan (DRP) guides the actions of emergency response personnel until the end goal is reached—which is to see the business restored to full last-known reliable operations.

- Disaster recovery refers specifically to restoring the information technology and communications services and systems needed by an organization, both during the period of disruption caused by any event and during restoration of normal services. The recovery of a business function may be done independently of the recovery of IT and communications services; however, the recovery of IT is often crucial to the recovery and sustainment of business operations. Whereas business continuity planning is about maintaining critical business functions, disaster recovery planning is about restoring IT and communications back to full operations after a disruption.

## 2.Components of a Disaster Recovery Plan

- Depending on the size of the organization and the number of people involved in the DRP effort, organizations often maintain multiple types of plan documents, intended for different audiences. The following list includes various types of documents worth considering:

- Executive summary providing a high-level overview of the plan
- Department-specific plans
- Technical guides for IT personnel responsible for implementing and maintaining critical backup systems
- Full copies of the plan for critical disaster recovery team members
- Checklists for certain individuals:

- Critical disaster recovery team members will have checklists to help guide their actions amid the chaotic atmosphere of a disaster.
- IT personnel will have technical guides helping them get the alternate sites up and running. 
- Managers and public relations personnel will have simple-to-follow, high-level documents to help them communicate the issue accurately without requiring input from team members who are busy working on the recovery.

---------

----------

## Chapter 2: Terms and Definitions:-

- **Adverse Events** - Events with a negative consequence, such as system crashes, network packet floods, unauthorized use of system privileges, defacement of a web page or execution of malicious code that destroys data.
- **Breach** - The loss of control, compromise, unauthorized disclosure, unauthorized acquisition or any similar occurrence where: a person other than an authorized user accesses or potentially accesses personally identifiable information; or an authorized user accesses personally identifiable information for other than an authorized purpose. Source: NIST SP 800-53 Rev. 5
- **Business Continuity (BC)** - Actions, processes and tools for ensuring an organization can continue critical operations during a contingency. 
- **Business Continuity Plan (BCP)** - The documentation of a predetermined set of instructions or procedures that describe how an organization’s mission/business processes will be sustained during and after a significant disruption.
- **Business Impact Analysis (BIA)** - An analysis of an information system’s requirements, functions, and interdependencies used to characterize system contingency requirements and priorities in the event of a significant disruption. Reference: https://csrc.nist.gov/glossary/term/business-impact-analysis
- **Disaster Recovery (DR)** - In information systems terms, the activities necessary to restore IT and communications services to an organization during and after an outage, disruption or disturbance of any kind or scale. 
- **Disaster Recovery Plan (DRP)** - The processes, policies and procedures related to preparing for recovery or continuation of an organization's critical business functions, technology infrastructure, systems and applications after the organization experiences a disaster. A disaster is when an organization’s critical business function(s) cannot be performed at an acceptable level within a predetermined period following a disruption.
- **Event** - Any observable occurrence in a network or system. Source: NIST SP 800-61 Rev 2 
- **Exploit** - A particular attack. It is named this way because these attacks exploit system vulnerabilities.
- **Incident** - An event that actually or potentially jeopardizes the confidentiality, integrity or availability of an information system or the information the system processes, stores or transmits. 
- **Incident Handling** - The mitigation of violations of security policies and recommended practices. Source: NIST SP 800-61 Rev 2
- **Incident Response (IR)** - The mitigation of violations of security policies and recommended practices. Source: NIST SP 800-61 Rev 2
- **Incident Response Plan (IRP)** - The documentation of a predetermined set of instructions or procedures to detect, respond to and limit consequences of a malicious cyberattack against an organization’s information systems(s). Source: NIST SP 800-34 Rev 1
- **Intrusion** - A security event, or combination of security events, that constitutes a security incident in which an intruder gains, or attempts to gain, access to a system or system resource without authorization. Source: IETF RFC 4949 Ver 2 
- **Security Operations Center** - A centralized organizational function fulfilled by an information security team that monitors, detects and analyzes events on the network or system to prevent and resolve issues before they result in business disruptions.
- **Vulnerability** - Weakness in an information system, system security procedures, internal controls or implementation that could be exploited or triggered by a threat source. Source: NIST SP 800-128. 
- **Zero Day** - A previously unknown system vulnerability with the potential of exploitation without risk of detection or prevention because it does not, in general, fit recognized patterns, signatures or methods.
