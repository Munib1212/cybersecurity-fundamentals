
## A) SHA-256
SHA-256 (Secure Hash Algorithm 256-bit) is a cryptographic hash function that produces a 256-bit fixed-length hash. It is widely used for file integrity verification, digital signatures, and blockchain technologies. SHA-256 is considered secure and resistant to known collision attacks.
## B) SHA-512
SHA-512 is part of the SHA-2 family and generates a 512-bit hash value. It offers stronger security than SHA-256 and is often used in systems that require higher cryptographic strength. It is secure and commonly used in enterprise and government systems.
## C) MD5
MD5 (Message Digest Algorithm 5) generates a 128-bit hash. It is considered broken due to proven collision vulnerabilities, meaning two different inputs can produce the same hash. MD5 should not be used for security purposes, but it may still appear in legacy systems.
## D) Bcrypt
Bcrypt is a password hashing function, not a general-purpose hash. It is designed to be slow and resource-intensive, which helps protect against brute-force and rainbow table attacks. Bcrypt is recommended for securely storing passwords.
 Hands-On Examples
 ## A) DNSSEC
 DNSSEC is used to make sure DNS answers are real and not fake.
When your computer asks, “What is the IP address for a website?”, DNSSEC lets your computer verify the answer hasn’t been changed by an attacker.
It protects against fake DNS responses
It uses digital signatures
It does not hide the DNS request
DNSSEC = verify DNS is authentic
## B) DNS over HTTPS (DoH)
DNS over HTTPS hides your DNS requests by encrypting them.
Instead of sending DNS queries in plain text, they are sent inside a secure HTTPS connection.
Prevents others from seeing which websites you visit
Protects against spying and man-in-the-middle attacks
Improves privacy
DoH = encrypted DNS
## C) Dynamic DNS
Dynamic DNS is used when a device’s IP address changes often.
It automatically updates DNS records so a domain name always points to the correct IP address.
Common for home labs, cameras, or servers
No security protection
Just convenience
Dynamic DNS = IP changes, DNS updates automatically
## D) Split DNS
Split DNS means different DNS answers for different users.
People inside a company network may get a private IP address, while people outside get a public IP.
Used in corporate networks
Improves security and efficiency
Not encryption
Split DNS = internal vs external DNS answers
A= DNSSEC = trust
B= DoH = privacy
C= Dynamic DNS = changing IPs
D= Split DNS = internal vs external
### What is WAF ? ( Web Application Firewall) 
security tool that protects web applications by filtering, monitoring, and blocking malicious HTTP/HTTPS traffic between users and a web app.
## What is LDAPS? (Lightweight Directory Access Protocol) 636 Port. 
LDAPS = LDAP secured with encryption (SSL/TLS) 
### what is this Used for ? (LDAPS) 636. 
 it’s used whenever you need to securely access or manage directory information.
 
### Common Uses (LDAPS) 636.
1. Authenticate Users
Check usernames and passwords against Active Directory
Example: Logging into a corporate network, VPN, or web app
2. Query Directory Data
Look up user accounts, groups, computers, or policies
Example: An admin wants to see all users in the “Sales” group
3. Manage Directory Data
Add, modify, or delete users or group memberships
Example: IT creating new accounts for employees securely
4. Secure Communication
Encrypts the traffic so usernames, passwords, and other sensitive info can’t be read by attackers on the network
## VPN protocls 
## 1. PPTP (Point-to-Point Tunneling Protocol)
. One of the oldest VPN protocols
. Designed in the 1990s by Microsoft
. Allows you to create a VPN tunnel to securely send data over the internet
### How it works? PPTP. 
Creates a tunnel between your device and the VPN server And then Encrypts data weakly (used older encryption methods like MPPE). Not really good
#### Pros (PPTP)
1. Very fast
2. Easy to set up
3. Works on almost every platform
#### Cons (PPTP) 
1. Insecure – easily broken by modern attacks
2. Vulnerable to password cracking and data interception ** Data interception = listens in” on the data you send over a network.
4. Not recommended for sensitive data.
  
## 2. L2TP (Layer 2 Tunneling Protocol) VPN protocls.
. L2TP is a VPN tunneling protocol used to create secure connections over the internet.
. On its own, L2TP does NOT encrypt data — it just creates a tunnel.
. That’s why it’s usually combined with IPsec (L2TP/IPsec) to provide encryption and security.
### How it works ? (L2TP).
1. L2TP creates a tunnel between your device and the VPN server.
2. IPsec encrypts the data going through that tunnel.
3. Data travels safely over the internet to the VPN server.
#### Pros
. More secure than PPTP when paired with IPsec
. Widely supported on Windows, macOS, iOS, and Android
. Good for corporate VPNs
#### Cons 
. Slower than PPTP due to double encapsulation (tunnel + encryption)
. Can be blocked by firewalls because it uses UDP ports 500 and 4500.
## What is What is IKEv2/IPsec? ( Internet Key Exchange Version 2 ) 
Modern, highly secure VPN protocol used to protect data as it travels over the internet.
##### It combines two technologies:
###### 1. IKEv2 (Internet Key Exchange version 2)
 1. Handles authentication
 2. Negotiates encryption keys
3. Manages the VPN connection
###### 2. IPsec (Internet Protocol Security)
1. Encrypts the data
 2. Ensures data integrity
 3. Prevents tampering and spying
##### Why it’s considered the MOST secure? 
1. Uses strong encryption (AES, SHA-2)
2. Resistant to modern attacks
3. Very stable, especially on mobile devices
4. Supported by Windows, macOS, iOS, Android
