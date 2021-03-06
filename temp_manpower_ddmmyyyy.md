---
title: PROPOSAL FOR MANPOWER FOR CUSTOMER_NAME
author: author_name; author_name@email;  [kxxxaxxx.in](http://kxxxxxxe.in)
date: 'January 05, 2018'
---

****
### version: 0.0.0 ###



## Table Of Contents ##

-   [Executive Summary](#executive-summary)
-   [Goals & Objectives](#goals-objectives)
-   [Current IT Infrastructure](#current-it-infrastructure)
-   [Architecture](#architecture)
-   [Scope of work (SoW)](#scope-of-work-sow)
-   [Exclusions/ Out of Scope](#exclusions-out-of-scope)
-   [Prerequisite](#prerequisite)
-   [Dependencies](#dependencies)
-   [ESCALATION MATRIX](#escalation-matrix)
-   [Call Logging Process](#call-logging-process)
    -   [Telephonic](#telephonic)
    -   [Email](#email)
-   [SLAs](#slas)
    -   [INITIAL RESPONSE TIME](#initial-response-time)
-   [Key Assumptions & Expectations](#key-assumptions-expectations)
-   [Commercials](#commercials)
-   [Important Terms & Conditions](#important-terms-conditions)
-   [ACCEPTANCE](#acceptance)
    -   [\# Annexures \#](#annexures)

##  
##  
##  
##
	
# Executive Summary # 

Customer <CUSTOMER NAME>, Noida is looking for a competent open source service partner to manage their spread of infrastructure monitoring. <CUSTOMER NAME> wants to engage with Kxxn and Axxx Cxxxxxxxs, an expert Open Source Infrastructure Services company  for the support services. The infrastructure  covered under the support services is mentioned further. This document aims at framing the proposed services under a contract i.e. annual maintenance  contract (AMC) for one year. 


# Goals & Objectives #

Primary goal to optimize the uptime of open source infrastructure by resolving issues arising by proactive monitoring

# Current IT Infrastructure #

-   Total 05 Physical Servers with Linux

-   03 APP Server

-   01 DB Primary Server

 -  01 DB Replication Server

# Architecture #

Captures the high level design diagram   

# Scope of work (SoW) #

The current high level sow is as:

1. 24x7 monitoring of ABC’s all setup. 
2. System Monitoring

> i) CPU,RAM,Disk space,I/O,PING,Zombie process, Disk failure, Read only mode with all basic metrics.
> ii) System security alerts: unauthorized login attempts, arp spoofing etc

3. Application Monitoring

> i) Most frequently occurring errors. like 4xx/5xx
> ii) Concurrent Users
> iii) Web server connection utilizing tracking
> iv) jvm monitoring
> v) java Exception monitoring

4. Database Monitoring

> i) Uptime
> ii) Replication Status if slave
> iii) User_Connections

5. Notification & reporting

# Exclusions/ Out of Scope #  

1. Any new installation of any product other than the existing ones.
2. Back end architecture designing including Database, Models, APIs, Web service and any Software (SW) development/coding. 
3. Any Hardware (HW) deployment & troubleshooting. 
4. Network and network related issue arising out of network or network device, data lines failure.
5. Issues due to unsupported Linux release and modified versions/RPM/Distro.
6. Any non-open source software and other application software
7. Warranty support of any software or/and hardware infrastructure
8. Known issues in Open source Linux OS, DB, Monitoring Software and Linux platform.
9. Database DR setup and restoration of data backup
10. Application/database integration & migration
11. Support services for technical issues not covered under scope and additional infrastructure

# Prerequisite # 

1. System design document including system inventory
2. Admin Access all the time.
3.
4.


|	Note: Prerequisites will be verified through a checklist

# Dependencies #
 
1. Infrastructure monitoring tool
2. VPN connection for remote troubleshooting
3. Dedicated access to the system is required while the service is being performed
4. Required software packages and Open Source repositories and subsequent release.
5. Formal approval from <CUSTOMER NAME> Team for any changes on any servers
6. Incident management tools

# ESCALATION MATRIX #

|  SNO. |		LEVEL	  |		 NAME			|		Contact Email			|    
|  :-----: | :------------------: | :---------------------------:  	| :--------------------------------------:  	|
|     1.   |            1             |  JOHN DOE ONE		|  johen.doe@kxxxxxxe.in	    	|
|     2 .  |            2             |  JOHN DOE TWO	   	|  johen.doe@kxxxxxxe.in	    	|
|     3.   |            3             |  JOHN DOE THREE	   	|  johen.doe@kxxxxxxe.in	    	|

Table: 01

# Call Logging Process #	

### Telephonic ###
: 	Call to Tech Support +91 000 000 000 

### Email ###
: 	support@kxxxxxxe.in


# SLAs #

## INITIAL RESPONSE TIME

|	SEVERITY	  |		 9am-5pm		|		5pm-9am			|    
| :----------------: | :---------------------------:  	| :--------------------------------------:  	|
|    P1             	  |  15 minutes			|  john.doe@                  	    	|
|    P2                |  60 minutes		   	|  john.doe@                   	    	|
|    P3                |  120 minutes		   	|  john.doe@                   	    	|


# Key Assumptions & Expectations #

1. These estimates are based on preliminary discussions and do not count for any contingencies. 
2. The mentioned services, activities under SoW are for one year only however services can be extended as per mutual agreements and contract.
3. Kxxxxxxe will provide services for 24x7 basis.
4. Kxxxxxxe will deploying on-site L1/L2 engineer for monitoring and SOP based operations tasks.
5. The working hours for onsite engineers will be monday to friday during standard business hours at Noida location. In weekdays, resource will be present at <CUSTOMER NAME> Noida office.
6. Over weekends and in night shift monitoring would be done remotely.
7. All engineers would be deployed post approval from <CUSTOMER NAME> system team only.
8. <CUSTOMER NAME> will provide SOP to L1 to execute daily basis task. Eg. Log rotation / backup.
9. <CUSTOMER NAME> and Kxxxxxxe both shall designate a coordinator and PMO for the Services to be performed vide the SOW. The coordinators shall interact to get approvals, report progress, discuss and resolve issues, manage meetings, etc. and can escalate issues or ask for clarification to their observations 
10. Kxxxxxxe’s any planning, execution; implementation will require an approval from designated coordinators from IB.
11. Adequate skill set  will be ensured to work on the production systems. 
12. Kxxxxxxe will change the resources incase if resource is not available or has moved out or is not fit to work. 
13. <CUSTOMER NAME> to maintain the Linux server, subscription active in order to get latest updates & patches necessary for service delivery, maintenance & troubleshooting. 
14. The solution is based on deployment under Red Hat Linux environment. 
15. For virtual systems where underlying hypervisor on non Red Hat then technical known issues arising out of such virtualized environment will be considered out of scope.
16. <CUSTOMER NAME> to provide onsite as well as remote access (via VPN) to servers, Storage and network for the mentioned environment to facilitate the activities. 
17. All facilities for which we’re dependent on a third-party to be made available on a timely manner. 
18. <CUSTOMER NAME> to ensure availability of server admin rights and resources for backup, alternate power backup, workplace safety and compliance for environment safety.
19. <CUSTOMER NAME> acknowledges that in order for <K&A> to provide the Support, <CUSTOMER NAME> may be required to license and install certain third-party software that are not provided or licensed by existing open source software and <K&A> Computers Pvt Ltd. 
20. <K&A> can neither be held responsible for impact on the functionality due any code change asked by <CUSTOMER NAME> under assigned Task nor the impact affecting the functionality after the rollback of any update, upgrade etc. 
21. All performance tuning & optimization will be based on Red Hat’s recommended best practices.
22. This service may necessitate the requirement to interrupt normal operating activities as necessary to permit delivery of this service therefore productive use of the system should not be scheduled during the installation, configuration and testing services.
23. <CUSTOMER NAME> to ensure the delivery of required IT hardware/software for the work at hand
24. Downtime server(s) can be expected and might be required for deployment purpose hence productive use of systems should avoided during such events.

# Commercials # 
  
|  ITEM |  RATE MAN-MONTH  	|	MONTHS		|	AMOUNT		|    
|  :-----: | :-------------------------:   	| :--------------------:  | :-------------------:  	|
|      1.  |          000,000         	    	|      			|  0,000,000	    	|



In words: Rs. (exclusive of GST)^1^

^1^ 18% Goods & Services Tax


# Important Terms & Conditions #

1. Goods and Services Tax Extra. 
2. Payment terms & schedules:  Quarterly Advance against invoice.
3. Price validity : One Month
4. Formal Purchase Order to be raised in the name of <K&A> and Once PO is raised, it can’t be cancelled
5. The mentioned commercials do not include and the price of any software, hardware and  3rd party software or service.
6. If any services/deliverables are required to be performed which are beyond those mentioned in the SOW, then the Kxxxxxxe shall provide an estimate of cost for performing such services to <CUSTOMER NAME> and shall obtain IB’s prior written approval for such costs. These costs will be invoiced to <CUSTOMER NAME> after completion of work and <CUSTOMER NAME> will pay the invoiced amount within 2 weeks of submission of invoice. 
7. The engineers will be available remotely and on-site unless absolutely required and asked by <CUSTOMER NAME>Team.
8. Onsite Travel by air and stay at a decent hotel preferably near the site will be arranged by <CUSTOMER NAME> in advance for the Kxxxxxxe’s designated resource.
9. <K&A> will provide the Services and Deliverables to <CUSTOMER NAME> as outlined in a SOW incorporating this proposal. Each deliverable in SoW will become binding when signed by both parties and will be governed by the terms and conditions of this proposal.
10. All necessary authorization to work, primary technical contact and local contact details for <CUSTOMER NAME> must be provided in advance.
11. <CUSTOMER NAME> will designated Level 2 resources for the purpose of interfacing between IB’s  team and Kxxxxxxe’s resources. 
12. Reporting & Escalation: All necessary reporting formats and frequency will be mutually agreed, and <CUSTOMER NAME> will provide the escalation matrix for Kxxxxxxe. All such reporting will be done through email, web or phone only. Any meeting requiring face to face discussion outside Delhi NCR, <CUSTOMER NAME> will arrange the travel and stay for Kxxxxxxe’s resource(s). 
13. <K&A> will not be responsible for the warranty and service issues in any of the HW or SW or 3rd party services which <CUSTOMER NAME> has already procured or purchased or has an ongoing services/support or commercial contract.
14. Any additional hardware, software and/or communications infrastructure and communication link/channel related usage/ configuration charges incurred for the implementation of this service will be borne entirely by the IB. 
15. Contract Term is 12 months  or 356 days.
16. Start Date: dd-mmm-yyyy  (means the day the services are officially started)
17. End date dd-mmm-yyyy (means the last day of the contract at the closure of business hours)
18. Business day means one working day consisting of standard business hours excluding weekends and holidays.
19. Leaves: Resources deployed will be entitled for sick leaves and personal emergency casual leaves
20. Business hours mean standard operating hour from 9AM to 6PM Mon-Friday.
21. <K&A> can be held responsible for the failure to perform any of its obligations loss or damage or delay due to FORCE MAJEURE such as act of God, firestorm, explosion, accident, strike, lockout, industrial dispute, labour trouble, transportation, war, war-like condition, civil commotion, riot, inability to obtain any material, refusal of license/subscription or imposition of sanctions and/or any measures taken by the Govt/government action or inaction. Whatsoever which renders it impossible or impractical for us to perform its obligation under the proposed services.
22.  <K&A> will not participate in any drill for any planned or unplanned downtime.
23. Non-solicitation. <CUSTOMER NAME> agrees not to solicit or hire any personnel of <K&A> involved with the delivery of Services about any work order/purchase order during the term of and for twelve (12) months after termination or expiration of such work order/purchase order.
24. Dispute Resolution. Each party agrees to give the other a written description of any problem(s) that may arise and to make a good faith effort to amicably resolve any such problem before commencing any proceeding
25. Termination: Either Party can terminate the contract by giving 60 days’ notice.
26. JURISDICTION: In case any dispute or difference shall arise between the parties during the subsistence the contract or by abandonment of contract or after the conclusion of the contract or touching or such relating either to the said service to be performed directly or indirectly under this contract then in such an event the courts at Delhi shall have exclusive jurisdiction.


# ACCEPTANCE #  

|  CUSTOMER NAME 						     |  Kxxx AND Axxxx Cxxxxxxxs PXxx.	      |
|  ---------------------------------------------------------------  |  -----------------------------------------------------   |
|										     |									      |
|										     |									      |
|										     |									      |
|										     |									      |	
|  Signature Authorised Signatory			     |  Signature Authorised Signatory		      |
|  Name:									     |  Name:							      |
|  Designation:							     |  Designation:						      |
|  Date:									     |  Designation:						      |	
|  Place:									     |  Designation:						      |	


# Annexures #
-
-
-

