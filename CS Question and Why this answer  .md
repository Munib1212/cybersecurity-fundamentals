### 1. What is the first step in incident response?
#### Answer: Preparation
### Why ? 
Incident response follows a defined lifecycle, and you must be ready before an incident happens.

Preparation includes:
1. Creating incident response policies and plans
2. Training the incident response team
3. Setting up logging, monitoring, and tools
4. Defining roles and communication procedures
### 2. According to order of volatility, which should be collected FIRST?
- A) Hard drive contents
###### - B) RAM contents
- C) Backup tapes
- D) Log files
### Why ? 
Lost when the system is powered off or rebooted. 
###### Ex. 
1. Running processes
2. Network connections
3. Encryption keys
4. Logged-in users
### 3. What is the purpose of chain of custody?
- A) Encrypt evidence
###### - B) Document every transfer of evidence
- C) Destroy evidence securely
- D) Analyze malware
### Why the other options are wrong
#### A) Encrypt evidence
 ##### Encryption protects data, but it is not the purpose of chain of custody
#### C) Destroy evidence securely
 ##### That happens after legal requirements, not during investigation
#### D) Analyze malware
##### Analysis is a separate forensic task
### 4. A SIEM system is used to ?
- A) Encrypt data at rest
###### - B) Collect and correlate security logs
- C) Create backups
- D) Manage user accounts
### Why Not Other ? 
- A) Encrypt data at rest,
  That’s handled by disk/database encryption
- C) Create backups,
 That’s a backup or DR system
- D) Manage user accounts,
 That’s IAM / Active Directory
### 5.Which vulnerability scan provides the MOST thorough results?
- A) External scan
- B) Uncredentialed scan
###### - C) Credentialed scan
- D) Passive scan
### Why? 
A credentialed scan logs into the system using valid credentials (like a real user or admin).
- See inside the operating system
- Check installed software
- Detect missing patches
- Identify misconfigurations
- Find more vulnerabilities
### 6.A CVSS score of 9.5 indicates: CVSS " Common Vulnerability Scoring System", Normal socre = 4.0 – 6.9,, High score = 7.0 – 8.9,, Critical socore= 9.0 - 10.0 ,, 
- A) Low severity
- B) Medium severity
- C) High severity
###### - D) Critical severity
### Why ? 
9.5 falls in the 9.0–10.0 range
Vulnerabilities in this range are:
- Easy to exploit
- Have severe impact
- Often allow remote code execution, privilege escalation, or full system compromise
- These require immediate attention.
### 7.What is the goal of containment in incident response?
- A) Remove the malware
###### - B) Stop the spread of the incident
- C) Restore normal operations
- D) Document lessons learned
  ### Why Not Other ?
1. - A) Remove the malware
   - You first isolate, then remove
   - You first isolate, then remove
2. - C) Restore normal operations
   - This is recovery
   - Systems are brought back online
   - This Happens after malware is removed
3. - D) Document lessons learned
   - This is post-incident activity
   - Done at the very end
   - Used to improve future response
     ##### This is connected the Incident response preparation.
     Incident Response Order (easy memory)

Preparation 
- Detection & Analysis
- Containment ← stop spread
- Eradication ← remove threat
- Recovery ← restore systems
- Lessons Learned
  ### 8.Which backup type backup only changes since the last FULL back up?
- A) Full
- B) Incremental
###### - C) Differential
- D) Snapshot
### Why not other ? 
1. - A) Full
   - A full backup copies everything, not just changes
   - The question asks for only changes
   - Full = all files, every time
2. - B) Incremental
   - Incremental backs up changes since the last backup of any type
   - Not specifically since the last full backup
   - Incremental = changes since last backup, not last full
3. - D) Snapshot ( The system tracks changes )
   - Snapshot is a point-in-time copy
   - Often used in virtualization/storage
   - Not a traditional backup type in this context
   - Snapshot ≠ incremental or differential backup
### 9. RTO (Recovery Time Objective) defines:
- A) How much data loss is acceptable
- B) How quickly systems must be restored
- C) How often backups run
- D) How long to keep backups
### 10. During which IR phase do you remove malware and patch vulnerabilities? IR = Incident response.
- A) Containment
- B) Eradication
- C) Recovery
- D) Detection
### Why Eradication ? 
- It is all about removing the root cause of incident
- Closing compromised accounts
- Patching vulnerabilities that were exploited
- Deleting malious scripts and tools
###### Must make sure Threat is Gone before Starting the back up. 
### 11. What tool is commonly used for packet capture and analysis?
- A) Nessus
- B) Wireshark
- C) Metasploit
- D) Nmap
### Why not other ? 
1. - A) Nessus 
- Vulnerability scanner
- Finds missing patches, misconfigurations
- Does not capture packets
2. - C) Metasploit
  - Exploitation framework
  - Used for penetration testing
  - Not for capturing or analyzing traffic
3. - D) Nmap
    - Network Scanner
    - Scanning Open Ports
### 12. RPO (Recovery Point Objective) defines:
- A) How quickly systems must be restored
###### - B) How much data loss is acceptable
- C) How often to test backups
- D) How long incidents last
 ### Why about other ?
1. A) How quickly systems must be restored " RTO – Recovery Time Objective "
- defines downtime 
3. C) How often to test backups
  - Backup test frequency is operational procedure
3. D) How long incidents last
- Incident duration is tracked in IR metrics, not RPO
