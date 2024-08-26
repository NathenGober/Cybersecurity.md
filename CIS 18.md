CIS stands for Center of Internet Security

# CIS 1 - Inventory and Control of Enterprise Assets
Identifying the hardware on your network 
- Company needs to protect all of these devices from being hacked
- A company is still liable for the devices they don't know about on the network
- CIS 1 recommends deployinh an automated assets inventory discovery tool and actively manage your assets. Review and update all assets to make sure devices are compliant

# CIS 2 - Inventory and Control of Software Assets
CIS 2 recommends to maintain inventory (list) of authorized software devices
- Ensure software is up to date and supported by vendor
- Utilize software inventory tools

The software inventory system should track (for OS and software)
- Name
- Version
- Publisher
- Installation date
  - Address unapproved software and remove
  - Utilize application whitelisting to ensure only authorized software executes
 
Key Takeaways
1. Identify and document all software
2. Develop an approved software whitelist
3. Manage software through regular scanning and updates

# CIS 3 - Data Protection
Business needs to classify data based on sensitivity. It is the only way to tell if confidential data was taken.
CIS 3 recommends to
1. Maintain an inventory of sensitive information
2. Remove sensitive data or systems not regularly accessed by the organization
3. Encrypt the harddrive of all mobile devices
4. Log sensitive access to data

# CIS 4 - Secure Configuration of Enterprise Assets & Software
CIS 4 recommends 
1. Establish and maintain a secure configuration process
2. Configure automatic session locking on all enterprise assets
3. Implement and manage a firewall on servers
4. Securely manage enterprise assets and software
5. Uninstall or disable unecessary services on enterprise assets and software

# CIS 5 - Account Management
CIS 5 recommends
1. Establish and maintain an inventory of accounts
2. Use unique passwords
3. Disable dormant accounts
4. Restrict administrator priviledges to dedicated administrator accounts
5. Establish and maintain an inventory of service accounts 

# CIS 6 - Access Control Management 
Have a detailed onboarding and offboarding process to gain/remove rights for accessing company data

CIS 6 recommends 
1. Establish an access granting process
2. Establish an access revoking process
3. Require MFA for externally-exposed applications
4. Require MFA for administrative access
5. Establish and maintain an inventory of authentication and authorization systems
6. Define and maintain role-based access control

# CIS 7 - Continuous Vulnerability Management 
Regularly scan for irregularities

CSI 7 recommends
1. Establishing and maintaining a Vulnerability Management Process and a Remediation Process
2. Performing Automated Patch Management for Operating Systems and Applications
3. Performing automated Vulnerability scans of Internal Enterprise Assets and Externally Exposed Enterprise Assets
4. Remediating detected vulnerabilities

Document a process to organize vulnerability scans and remediation

# CIS 8 - Audit Log Management 
Very important to maintain logs of everything that happened and store them in a safe place.

CIS 8 recommends
1. Establish and maintain an audit log management process
2. Standardize time synchronization
3. Collect detailed audit logs
4. Ensure adequate audit log storage

# CIS 9 - Email and Web Browser Protections
Ensure data protection by updating and using only fully supported web browsers and emails 

CIS 9 recommends
1. Ensure use of only fully supported browsers and email clients
2. Use DNS (Domain Name System) Filtering services
3. Maintain and enforce network-based url filters
4. Restrict unnecessary or unauthorized browser and email client extensions
5. Implement DMARC (Domain-Based Message Authentication, reporting and conformance)
6. Block unnecessary file types
7. Deploy and maintain email server anti-malware protections

# CIS 10 - Malware Defenses
CIS 10 recommends 
1. Deploy and maintain anti-malware software
2. Disable autorun and autoplay for removable media
3. Configure automatic anti-malware scanning of removable media
4. Enable anti-exploitation features
5. Centrally manage anti-malware software

# CIS 11 - Data Recovery
Self-restoring capabilities for whenever the data has been hacked, held for ransom, deleted, etc.

CIS 11 recommends 
1. Establish and maintain a data recovery process
2. Perform automated backups
3. Protect recovery data
4. Test data recovery

# CIS 12 - Network Infrastructure Management 
Securely manage network infrastructure so all systems work accordingly and safely 

CIS 12 recommends
1. Ensure network infrastructure is up to date
2. Establish, implement, actively manage, track, report, and correct network devices in order to prevent attackers from exploiting vulnerable network services and access points
3. Use of secure network management and communication protocols
4. Ensure remote devices use a VPN and connect to an enterprise's AAA infrastructure

AAA stands for Authentication, Authorization, and Accounting.

# CIS 13 - Network Monitoring and Defense
Many websites people use can carry malicious content on them. By accessing them on company networks, the company is then exposed to these malicious actors. Installing a network monitoring tool such as a firewall would keep company data secure and keep malicious actors away.

CIS 13 recommends 
1. Creating a central security alert system
2. Deploy Intrusion Detection Systems
3. Perform Traffic Filtering and collect network traffic flow logs
4. Manage access control for remote assets
5. Deploy Intrusion Preventation Systems
6. Perform Application Level Filtering

# CIS 14 - Security Awareness & Skills Training 
CIS 14 recommends 
1. Perform a skills gap analysis
2. Training employees in the skills they are lacking
3. Implementing a Security Awareness Program
5. Updating Awareness programs regularly
6. Train Workforce to secure authentication, identify social engineering attacks, sensitive data handling, causes of unintentional data exposure, and identification and reporting incidents
7. Organizations need to stay on top of making their employees aware of the risks and train them with the latest security measures
   
# CIS 15 - Service Provider Management 
Outside vendors to conduct daily business functions. Develop a process to evaluate service providers who hold sensitive data or are responsible for an enterprises critical IT platforms or processes to protect them.

CIS 15 recommends 
1. Identifying, classifying and assessing all vendors
2. Ensuring providers know organization's security requirements
3. Constant monitoring providers
4. Properly decommissioning providers

# CIS 16 - Application Software Security
Mange the security of in-house developed, hosted, or acquired software to prevent, detect, and remediate security weaknesses before they can impact the enterprise

CIS 16 recommends
1. Creating a secure app dev process
2. Taking inventory of all applications the organization uses
3. Use up-to-date and trusted versions of any apps needed
4. Rate applications on how secure they are
5. Train employees to create apps securely
6. Apply Security principles in application design
7. Implement security tests and conduct penetration testing and threat modeling 

# CIS 17 - Incident Reponse & Management 
Establish a program to develop and maintain an incident response capability (examples such as policies, plans, procedures, defined roles, training, and communications) to prepare, detect, and quickly respond to an attack.

CIS 17 recommends
1. Designating and assigning personnel to manage incident handling
2. Create a list of all entities to inform about the incident
3. Create a plan for reporting incidents
4. Conduct routine incidence management response simulations
5. Conduct post-incident reviews
6. Establish security thresholds

# CIS 18 - Penetration Testing
Pen testing is done to show vulnerabilities in a network. Organizations can hire ethical hackers to get an idea of just how secure their system is. 

There are multiple types of hackers and tests they conduct but it is recommended that a test be done annually to maintain network security.

Types of Pen Tests
- Black box - testers are in role of average hacker with no internal knowledge
- Grey box - access and knowledge of a user with potentially elevated priveledges
- White box - provides comprehensive of internal and external

CIS 18 recommends
1. Establish and maintain a penetration testing program
2. Perform periodic external penetration tests
3. Remediate penetration test findings
4. Validate security measures
5. Perform periodic internal penetration tests
