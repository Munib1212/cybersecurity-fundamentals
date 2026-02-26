### Cybersecurity Framework 01
1. IDENTIFY

Goal: Understand what you need to protect.
- Develop security policies
- Identify assets (servers, laptops, cloud systems)
- Evaluate risks, threats, and vulnerabilities
- Recommend security controls
###### Example:
- Discover company has 200 laptops and 5 cloud servers
- Identify ransomware as a major threat
- Recommend MFA, backups, and endpoint protection
 - Think: Know your environment
   #### 2. project

Goal: Put safeguards in place.

- Install firewalls
- Enable encryption
- Configure MFA
-Patch systems
- Secure the system lifecycle (from purchase to disposal)
 Example
- Install antivirus on all devices
- Encrypt employee laptops
Apply security patches monthly
##### 3. Detect 
Goal: Find attacks quickly.
- Monitor logs
- Use SIEM tools
- Analyze alerts
- Detect suspicious behavior
 Example:
- SIEM alerts unusual login from another country
- IDS detects abnormal network traffic
  Spot the problem
  ##### 4. RESPOND
  Goal: Take action when an incident occurs.
- Analyze the incident
- Contain the threat
- Eradicate malware
- Communicate with stakeholders
   Example:
- Isolate infected computer
- Remove ransomware
- Patch exploited vulnerability
 Handle the attack
##### 5. RECOVER
Goal: Restore operations and improve resilience.
- Restore from backups
- Rebuild servers
- Improve controls
- Update policies
   Example:
- Restore data from backup
- Add better monitoring to prevent repeat attack,,
 Get back to normal
#### Easy Memory Trick
I P D R R
***
### Gap Analysis 02 
##### What is Gap Analysis in Cybersecurity
Gap analysis is a structured process that compares an organization’s current cybersecurity posture against a defined framework, standard, or regulatory requirement to identify missing or ineffective controls. It answers the question: “What security controls are missing or insufficient compared to what is required?”
###### Purpose
- Measure current security maturity
- Identify missing or weak controls
- Determine compliance status
- Prioritize remediation efforts
- Create a structured improvement roadmap
###### When It Is Performed
- When adopting a new cybersecurity framework (e.g., NIST CSF, ISO 27001)
- Before regulatory or compliance audits
- After major infrastructure or policy changes
- Periodically (every 1–3 years)
- When new legal or industry requirements are introduced
###### Process
1. Define the Target Framework
Select the framework or regulation to assess against.
2. Assess Current State
Document existing policies, procedures, and technical controls.
3. Compare Against Requirements
Identify differences between implemented controls and required or recommended controls.
4. Identify Gaps
###### Classify findings such as:
- Missing controls
- Partially implemented controls
- Misconfigured controls
- Ineffective controls
5. Evaluate Risk
###### Assess the impact of gaps on:
- Confidentiality
- Integrity
- Availability
6. Create Remediation Plan
Develop a prioritized action plan with timelines and assigned responsibilities.
###### Example
- Requirement: Maintain an up-to-date asset inventory.
- Current State: Asset inventory exists but is not regularly updated.
- Gap: No formal update and validation process.
- Risk: Increased exposure to unpatched vulnerabilities.
- Remediation: Implement automated asset discovery and scheduled quarterly reviews.
###### Gap Analysis Report Typically Includes
- Executive summary
- Overall maturity score
- Detailed list of gaps by function or category
- Risk ratings
- CIA impact assessment
- Remediation recommendations
- Target completion dates
- Key Concept
- Gap Analysis = Current State – Required State
###### It is a formal method used to identify, measure, and prioritize security deficiencies to align an organization with a cybersecurity framework or compliance requirement.
*** 
### Access Control 03 
Access control is the security process that controls access to systems and data by verifying identity and enforcing permissions.
###### Who is allowed to access what — and what they’re allowed to do.
#### Subjects vs  Objects
- Subjects = users, devices, apps (anything requesting access)
- Objects = files, databases, servers, networks (the resources)
Simple Real-Life Example
###### Think of a school:
- Your student ID card = identification
- Swiping it at the door = authentication
- Some rooms open, others stay locked = authorization
- Security cameras/logs track entry = accounting
- That whole system = access control
### Security controls 04 
Security controls are safeguards used to protect systems, data, and networks.
#### Security Control Categories
1. Managerial/administrative control
it focus on policies, procedures, and management decisions, Managerial control are rules and oversight created by management to reduce risk and guide security behavior.
#### example Examples
- Security policies
- Acceptable Use Policy (AUP)
- Risk assessments
- Security awareness training
- Background checks
- Incident response plans
- Change management procedures

QR: A managerial control is a policy, procedure, or governance mechanism implemented by management to guide and enforce security practices.
**********
### 2. Operational
security procedures and activities performed by staff to protect systems.
- Security awareness training
- Incident response procedures
- Backup procedures
- User account management
- Monitoring and reviewing logs
- Physical security patrols
 ###### Let's say compnay wants to protect data. 
1. Managerial control → Create a security policy
2. Operational control → IT staff follow procedures to manage accounts
###### QR: 
Operational controls are security measures implemented and maintained through day-to-day procedures and actions performed by people.
### 03 Technical control. 
A technical control (also called a logical control) is a security measure that uses technology to protect systems and data.(enforced by hardware or software) 
#### Examples of Technical Controls
- Firewalls
- Antivirus software
- Encryption
- Multi-Factor Authentication (MFA)
- Access Control Lists (ACLs)
- Intrusion Detection Systems (IDS)
- Password protection
##### Comparison

If a company wants to protect its servers:
- Managerial control → Create a password policy
- Operational control → IT staff reset and manage accounts
- Technical control → System enforces password complexity rules
#### 04 Pysical control.
A physical control is a security measure that protects people, buildings, and equipment from physical access or damage.
###### Examples of Physical Controls
- Door locks
- Security guards
- Surveillance cameras (CCTV)
- Fences
- Badge access systems
- Biometric door scanners
- Alarm systems
- Server room locks
###### Easy comparison 
Managerial control → Policy: “Only IT staff may enter server room.”
Operational control → Staff check visitor badges.
Technical control → Firewall protects network.
Physical control → Locked server room door.
###### Portation 2 
### Information Security Competencies
1.  Risk Assessment and Security Testing
- Security professionals participate in identifying threats, vulnerabilities, and risks. They:
- Conduct or support risk assessments
- Perform security testing (vulnerability scans, configuration reviews)
- Evaluate existing controls
- Recommend improvements to reduce risk
  END--- due to time 
   
