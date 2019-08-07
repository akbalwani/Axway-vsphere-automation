# Axway-vsphere-automation


 
Table of Contents
Problem statement	2
Purpose	2
Milestones	2
Phases 1	2
Phase 2	2
Participants	2
RACI	2
Progress	3





















Problem statement
•	No Ready Environment.
•	Huge Latency in getting Resources.
•	Existing ESX didn’t had enough space.
Purpose
•	Self Service provisioning by TSEs
•	Cut down time provisioning.
•	Reusability of pre-built environments
•	Environment readiness.
•	Resource optimization.

Milestones
Phases 1
•	VM Template Creation through Template-Zilla for ST
o	Combination of OS and Product Version
•	Automated Provisioning using Templates.
•	VM deletion module added.
•	Health-check module added.
Phase 2
•	Automating architectural configurations
o	e.g. Clustering, HA, Load Balancers, shared storage, database, LDAP etc.
Participants
•	Product Specific Teams
o	ST – Arpit (E1), Akil (E2), Chaitanya (E3)
o	API – Mohd. Sharjil (E1), Abhinav Aggarwal (E2), Sandeep (E1), Rahul (E3)
o	ADI – Arpit (E1), Shivangi (E2), Praveen (E3)
o	B2Bi – Nitasha (E2), Jyoti (E1), Sandeep (E3)
o	CFT – Chirag (E1), Raju (E1),  Surya (E2), Chaitanya (E2), Abhinav (E3)
o	MG – Surya (E1), Shivangi (E2), Akil (E3)
RACI
Particulars	R	A	C	I
OS & Product Creation	E2	E3	E1, E3, PM	PM
Template Creation	E1	E3	E2, E3, PM	PM
Topology Creation	E1, E2	E3	PM	PM



Progress

Secure Transport
Environment	OS & Product Creation	Template Creation	Topology Creation
SUSE 12.1 ST 5.3.3
	Y	Y	Y
SUSE 12.1 ST 5.3.6	Y	Y	Y
SUSE 12.1 ST 5.4.0	Y	Y	Y
RHEL 7.6   ST 5.3.3	Y	Y	Y
RHEL 7.6   ST 5.3.6	Y	Y	Y
RHEL 7.6   ST 5.4.0	Y	Y	Y
Windows 2008 ST	Y	Y	Y
Windows 2008 ST	Y	Y	Y
Windows 2008 ST	Y	Y	Y
Windows 2012 ST	Y	Y	Y
Windows 2012 ST	Y	Y	Y
Windows 2012 ST	Y	Y	Y

CFT 
Environment	OS & Product Creation	Template Creation	Topology Creation
SUSE 11 SP4 CFT324	Y	Y	Y
SUSE11SP4_CFT332	Y	Y	Y
SUSE11SP4  CFT340	Y	Y	Y
RHEL72 CFT324	Y	y	y
RHEL72 CFT332	y	y	y
RHEL71 CFT340	y	y	y
Win2k8_CFT324	Y	Y	Y
Win2k12_CFT332	Y	Y	Y
Win2k12_CFT340	N	N	N
			
			
			




API
Environment	OS & Product Creation	Template Creation	Topology Creation
CENTOS7_APInode2	y	y	Y
CENTOS7_APInode3	y	y	Y
CENTOS7_APINODE4	y	y	Y


CG
Environment	OS & Product Creation	Template Creation	Topology Creation
CG113_CentOs7	Y	Y	Y





Access Right management	Clean up Process
•	All the user accounts has been verified for Vm creation on ESX with start,stop, delete operations 
•	EveryUser has a corresponding folder on ESX in which he/she should create resources.	•	Mail has been initiated with the team members, to identify the resources created on old ESX and the new one with demarcation as temporary /permanent.
•	Process will be refined after the same with Team discussion.


