# Recovery Strategies

Identifying the preventive controls is the third step of the business continuity steps as outlined in NIST SP 800-34 RI. If preventive controls are identified in the business impact analysis (BIA), disasters or disruptive events might be mitigated or eliminated. These preventive measures deter, detect, and/or reduce impacts to the system. Preventive methods are preferable to actions that might be necessary to recover the system after a disruption if the preventive controls are feasible and cost effective. 

The following sections discuss the primary controls that organizations can implement as part of business continuity and: disaster recovery, including redundant systems, facilities, and power; fault-tolerance technologies; insurance; data backup; fire detection and suppression; high availability; quality of service; and system resilienct. 

## Create Recovery Strategies 

Organizations must create recovery strategies for all assets that are vital to successful operation. Higher-level recovery strategies identify the order in which processes and functions are restored. System-level recovery strategies define how a particular system is to be restored. Keep in mind those individuals who best understand the system should define system recovery strategies. Although the business continuity planning (BCP) committee probably can develop the prioritized recovery lists and high-level recovery strategies, system administrators and other IT personnel need to be involved in the development of recovery strategies for IT assets. 

Disaster recovery tasks include recovery procedures, personnel safety procedures, and restoration procedures. The overall business recovery plan should require a committee to be formed to decide the best course of action. This recovery plan committee receives its direction from the BCP committee and senior management. 

All decisions regarding recovery should be made in advance and incorporated into the disaster recovery plan (DRP). Any plans and procedures that are developed should refer to functions or processes, not specific individuals. As part of the disaster recovery planning, the recovery plan committee should contact critical vendors ahead of time to ensure that any equipment or supplies can be replaced in a timely manner. 

When a disaster or disruptive event has occurred, the organization's spokesperson should report the bad news in an emergency press conference before the press learns of the news through another channel. The DRP should detail any guidelines for handling the press. The emergency press conference site should be planned ahead of time. 

When resuming normal operations after a disruptive event, the organization should conduct a thorough investigation if the cause of the event is unknown. Personnel should account for all damage-related costs that occur as a result of the event. In addition, appropriate steps should be taken to prevent further damage to property. 

The commonality between all recovery plans is that they all become obsolete. For this reason, they require testing and updating. 

The following sections include a discussion of categorizing asset recovery priorities, business process recovery, facility recovery, supply and technology recovery, user environment recovery, data recovery, and training personnel. 

## Categorize Asset Recovery Priorities 

As discussed in Chapter 1, the recovery time objective (RTO), work recovery time (WRT), and recovery point objective (RPO) values determine what recovery solutions are selected. An RTO stipulates the amount of time an organization wij need to recover from a disaster, and an RPO stipulates the amount of data an organization can lose when a disaster occurs. The RTO, WRT, and RPO values are derived during the BIA process. 

In developing the recovery strategy, the recovery plan committee takes the RTO, WRT, and RPO values and determines the recovery strategies that should be used to ensure that the organization meets these BIA goals. 

Critical devices, systems, and applications need to be restored earlier than devices, systems, or applications that do not fall into this category. Keep in mind when classifying systems that most critical systems cannot be restored using manual methods. The recovery plan committee must understand the backup/restore solutions that are available and implement the system that will provide recovery within the BIA values and cost constraints. The window of time for recovery of data-processing capabilities is based on the criticality of the operations affected. 

## Business Process Recovery 

As part of the DRP, the recovery plan committee must understand the interrelationships between the processes and systems. A business process is a collection of tasks that produces a specific service or product for a particular customer or customers. For example, if the organization determines that an accounting system is a critical application and the accounting system relies on a database server farm, the DRP needs to include the database server as a critical asset. Although restoring the entire database server farm to restore the critical accounting system might not be necessary, at least one of the servers in the farm is necessary for proper operation. Workflow documents should be provided to the recovery plan committee for each business process. As part of recovering the business processes, the recovery plan committee must also understand the process’s required roles and resources, input and output tools, and interfaces with other business processes. 

## Supply and Technology Recovery 

Although facility recovery is not often a concern with smaller disasters or disruptive events, almost all recovery efforts usually involve the recovery of supplies and technology. Organizations must ensure that any DRPs include guidelines and procedures for recovering supplies and technology. As part of supply and technology recovery, the DRP should include all pertinent vendor contact information in the event that new supplies and technological assets must be purchased. 

The DRP must include recovery information on the following assets that must be restored: 

⁃
Hardware backup 
⁃
Software backup
⁃
Human resources 
⁃
Heating, ventilation, and air conditioning (HVAC)
⁃
Supplies 
⁃
Documentation 

### Hardware Backup 

Hardware that must be included as part of the DRP includes client computers, server computers, routers, switches, firewalls, and any other hardware that is running on the organization's network. The DRP must include not only guidelines and procedures for restoring all the data on each of these devices, but also information regarding restoring these systems manually if the systems are damaged or completely destroyed. Legacy devices that are no longer available in the retail market should also be identified.

As part of preparing the DRP, the recovery plan team must determine the amount of time that it will take the hardware vendors to provide replacements for any damaged or destroyed hardware. Without this information documented, any recovery plans might be ineffective due to lack of resources. Organizations might need to explore other options, including purchasing redundant systems and storing them at an alternate location, if vendors are unable to provide replacement hardware in a timely manner. When legacy devices is possible, organizations should take measures to replace them before the disaster occurs. 

### Software Backup 

Even if an organization has every device needed to restore its infrastructure, those devices are useless if the applications and software that run on the devices are not available. The applications and software include any operating systems, databases, and utilities that need to be running on the device. 

Many organizations might think that this requirement is fulfilled if they have a backup on either tape, DVD, flash drive, hard drive, or other media of all their software. But all software that is backed up usually requires at least an operating system to be running on the device on which it is restored. These data backups often also require that the backup management software is running on the backup device, whether that is a server or dedicated device. 

All software installation media, service packs, and other necessary updates should be stored at an alternate location. In addition, all license information should be documented as part of the DRP. Finally, frequent backups of applications should be taken, whether this is through the application's internal backup system or through some other organizational backup. A backup is useful only if it can be restored, so the DRP should fully document all the steps involved. 

In many cases, applications are purchased from a software vendor, and only the software vendor understands the coding that occurs in the applications. Because there are no guarantees in today's market, some organizations might decide that they need to ensure that they are protected against a software vendor demise. A software escrow is an agreement whereby a third party is given the source code of the software to ensure that the customer has access to the source code if certain conditions for the software vendor occur, including bankruptcy and disaster. 

### Human Resources 

No organization is capable of operating without personnel. An occupant emergency plan specifically addresses procedures for minimizing loss of life or injury when a threat occurs. The human resources team is responsible for contacting all personnel in the event of a disaster. Contact information for all personnel should be stored onsite and offsite. Multiple members of the HR team should have access to the personnel contact information. Remember that personnel safety is always the primary concern. All other resources should be protected only after the personnel are safe. 

After the initial event is over, the HR team should monitor personnel morale and guard against employee stress and burnout during the recovery period. If proper cross-training has occurred, multiple personnel can be rotated in during the recovery process. Any DRP should take into consideration the need to provide adequate periods of rest for any personnel involved in the disaster recovery process. It should also include guidelines on how to deal with situations where any personnel fall victims of a disaster. 

The organization must ensure that salaries and other funding to personnel continue during and after the disaster. Because funding can be critical both for personnel and for resource purchases, authorized, signed checks should be securely stored offsite. Lower-level management with the appropriate access controls should have the ability to disperse funds using these checks in the event that senior management is unavailable. 

Aa executive succession plan should also be created to ensure that the organization follows the appropriate steps to protect itself and continue operation. 

### Supplies
 
Often disasters affect the ability to supply an organization with its needed resources, including paper, cabling, and even water. The organization should document any resources that are vital to its daily operations and the vendors from which these resources can be obtained. Because supply vendors can also be affected by the disaster, alternative suppliers should be identified. 

### Documentation 

For disaster recovery to be a success, the personnel involved must be able to complete the appropriate recovery procedures. Although the documentation of all these procedures might be tedious, it is necessary to ensure that recovery occurs. In addition, each department within the organization should be asked to decide what departmental documentation is needed to carry out day-to-day operations. This documentation should be stored in a central location onsite, and a copy should be retained offsite also. Specific personnel should be tasked with ensuring that this documentation is created, stored, and updated as appropriate. 

## User Environment Recovery 

All aspects of the end-user environment recovery must be included as part of the DRP to ensure that the end users can return to work as quickly as possible. As part of this user environment recovery, end-user notification must occur. Users must be notified of where and when to report after a disaster occurs. 

The actual user environment recovery should occur in stages, with the most critical functions being restored first. User requirements should be documented to ensure that all aspects of the user environment are restored. For example, users in a critical department might all need their own client computers. These same users might also need to access an application that is located on a server. If the server is not restored, the users will be unable to perform their job duties even if their client computers are available. 

Finally, manual steps that can be used for any function should be documented. Because we are so dependent on technology today, we often overlook the manual methods of performing our job tasks. Documenting these manual methods might that operations can still occur, even if they occur at a decreased rate. 

## Data Recovery 

In most organizations, the data is one of the most critical assets when recovering from a disaster. The BCPs and DRPs must include guidelines and procedures for recovering data. However, the operations teams must determine which data is backed up, how often the data is backed up, and the method of backup used. So although we discuss data backup, remember that BCP teams do not actually make any data backup decisions. The BCP teams are primarily concerned with ensuring that the data that is backed up can be restored in a timely manner. Next, we discuss the data backup types and schemes that are used as well as electronic backup methods that organizations can implement. 

### Data Backup Types and Schemes 

To design an appropriate data recovery solution, security professionals must understand the different types of data backups that can occur and how these backups are used together to restore the live environments. 

For the CISSP exam, you must understand the following data backup types and schemes: 

⁃
Full backup 
⁃
Differential backup
⁃
Incremental backup
⁃
Copy backup
⁃
Daily backup
⁃
Transaction log backup
⁃
First in, first out rotation scheme
⁃
Grandfather/father/son rotation scheme 

The three main data backups are full backups, differential backups, and incremental backups. ‘To understand these three data backup types, you must understand the concept of archive bits. When a file is created or updated, the archive bit for the file is enabled. If the archive bit is cleared, the file will not be archived during the next backup. If the archive bit is enabled, the file will be archived during the next backup. 

With a **full backup**, all data is backed up. During the full backup process, the archive bit for each file is cleared. A full backup takes the longest time and the most space to complete. However, if an organization uses only full backups, then only the latest full backup needs to be restored. Any differential or incremental backup will first start with a full backup as its baseline. A full backup is the most appropriate for offsite archiving. 

In a **differential** backup, all files that have been changed since the last full backup will be backed up. During the differential backup process, the archive bit for each file is not cleared. A differential backup might vary from taking a short time and a small amount of space to growing in both the backup time and amount of space it needs over time. Each differential backup will back up all the files in the previous differential backup if a full backup has not occurred since that time. In an organization that uses a full/differential scheme, the full backup and only the most recent differential backup must be restored, meaning only two backups are needed. 

An **incremental** backup backs up all files that have been changed since the last backup of any type. During the incremental backup process, the archive bit for each file is cleared. An incremental backup usually takes the least amount of time and space to complete. In an organization that uses a full/incremental scheme, the full backup and each subsequent incremental backup must be restored. The incremental backups must be restored in order. If your organization completes a full backup on Sunday and an incremental backup daily Monday through Saturday, up to seven backups could be needed to restore the data. Figure 7-9 compares the difterent types of backups. 

| Backup Type | Data Backed Up | Backup Time | Restore Time | Storage Space |
| — | — | — | — | — |
| Full Backup | All Data | Slowest | Fast | High | 
| Incremental Backup | Only New/Modified Files/Folders | Fast | Moderate | Lowest |
| Differential Backup | All Data Since Last Full | Moderate | Fast | Moderate |

Figure 7-9 Backup Types Comparison 

Copy and daily backups are two special backup types that are not considered part any regularly scheduled backup scheme because they do not require any other backup type for restoration. **Copy backups** are similar to normal backups but do not reset the file archive bit. **Daily backups** use a file’s timestamp to determine whether it needs archiving, Daily backups are popular in mission-critical environments where multiple daily backups are required because files are updated constantly. 

**Transaction log backups** are used only in environments where capturing all transactions that have occurred since the last backup is important. Transaction log backups help organizations to recover to a particular point in time and are most commonly used in database environments. 

Although magnetic tape drives are still used to back up data, organizations today may back up their data to optical discs, including CD-ROMs, DVDs, and Blu-ray discs; high-capacity, high-speed magnetic drives; flash-based media; or even network storage. No matter the media used, retaining backups both onsite and offsite is important. Store onsite backup copies in a waterproof, heat-resistant, fire-resistant safe or vault. 

### Electronic Backup 

Electronic backup solutions back up data quicker and more accurately than the normal data backups and are best implemented when information changes often. 

For the CISSP exam, you should be familiar with the following electronic backup terms and solutions: 

⁃
**Electronic vaulting**: Copies files as modifications occur. This method occurs in real time. 
⁃
**Remote journaling**: Copies the journal or transaction log offsite on a regular schedule. This method occurs in batches. 
⁃
**Tape vaulting**: Creates backups over a direct communication line on a backup system at an offsite facility. 
⁃
**Hierarchical storage management (HSM)**: Stores frequently accessed data on faster media and less frequently accessed data on slower media.
⁃
**Optical jukebox**: Stores data on optical disks and uses robotics to load and unload the optical disks as needed. This method is ideal when 24/7 availability is required. 
⁃
**Replication**: Copies data from one storage location to another. Synchronous replication uses constant data updates to ensure that the locations are close to the same, whereas asynchronous replication delays updates to a predefined schedule. 

Many companies use cloud backup or replication solutions. Any organization considering a cloud solution should research the full security implications of this type of deployment. 

### Training Personnel 

Even if an organization takes the steps to develop the most thorough BCPs and DRPs, these plans are useless if the organization's personnel do not have the skills to completely recover the organization's assets when a disaster occurs. Personnel should be given the appropriate time and monetary resources to ensure that adequate training occurs. This includes allowing personnel to test any DRPs. 

Training should be obtained from both internal and external sources. When job duties change or new personnel are hired, policies should be in place to ensure the appropriate transfer of knowledge occurs. 

## Backup Storage Strategies 

As part of any backup plan, an organization should also consider the backup storage strategy or rotation scheme that it will use. Cost considerations and storage considerations often dictate that backup media is reused after a period of time. If this reuse is not planned in advance, media can become unreliable due to overuse. Two of the most popular backup rotation schemes are first in, first out and grandfather/father/son. 

In the **first in, first out (FIFO)** scheme, the newest backup is saved to the oldest media. Although this is the simplest rotation scheme, it does not protect against data errors. If an error in data exists, the organization might not have a version of the data that does not contain the error. 

In the **grandfather/father/son (GFS)** scheme, three sets of backups are defined. Most often these three definitions are daily, weekly, and monthly. The daily backups are the sons, the weekly backups are the fathers, and the monthly backups are the grandfathers. Each week, one son advances to the father set. Each month, one father advances to the grandfather set. 

Figure 7-10 displays a typical 5-day GFS rotation using 21 backup media. The daily backups are usually differential or incremental backups. The weekly and monthly backups must be a full backup. 

## Recovery and Multiple Site Strategies

When dealing with an event that either partially or fully destroys the primary facility, the organization will need an alternate location from which to operate until the primary facility is restored. The DRP should define the alternate location and its recovery procedures, often referred to as a recovery site strategy. 

The DRP should include not only how to bring the alternate location to full operation but also how the organization will return from the alternate location to the primary facility after it is restored. Also, for security purposes, the DRP should include details on the security controls that were used at the primary facility and guidelines on how to implement these same controls at the alternate location. 

The most important factor in locating an alternate location during the development of the DRP is to ensure that the alternate location is not affected by the same disaster. This might mean that the organization must select an alternate location that is in another city or geographic region. The main factors that affect the selection of an alternate location include the following: 

⁃
Geographic location
⁃
Organizational needs
⁃
Location’s cost
⁃
Location's restoration effort 

Testing an alternate location is a vital part of any DRP. Some locations are easier to test than others. The DRP should include instructions on when and how to periodically test alternate facilities to ensure that the contingency facility is compatible with the primary facility. 

The alternate locations that you should understand for the CISSP exam include the following:

⁃
Hot site
⁃
Cold site
⁃
Warm site
⁃
Tertiary site
⁃
Reciprocal agreements
⁃
Redundant sites 

### Hot Site 

A **hot site** is a leased facility that contains all the resources needed for full operation. This environment includes computers, raised flooring, full utilities, electrical and communications wiring, networking equipment, and UPSs. The only resource that must be restored at a hot site is the organization's data, often only partially. It should take only a few minutes to hours to bring a hot site to full operation. 

Although a hot site provides the quickest recovery, it is the most expensive to maindue to the ready-to-use asset conditions. In addition, it can be administratively hard to manage if the organization requires proprietary hardware or software. A hot site requires the same security controls as the primary facility and full redundancy, including hardware, software, and communication wiring.

### Cold Site 

A **cold site** is a leased facility that contains only electrical and communications wiring, air conditioning, plumbing, and raised flooring. No communications equipment, networking hardware, or computers are installed at a cold site until it is necessary to bring the site to full operation. For this reason, a cold site takes much longer to bring to full operation than a hot or warm site. 

Although a cold site provides the slowest recovery, it is the least expensive to maintain. lt is also the most difficult to test. 

### Warm Site 

A **warm site** is a leased facility that contains electrical and communications wiring, full utilities, and networking equipment. In most cases, the only devices that are not included in a warm site are the computers. A warm site takes longer to restore than a hot site but less than a cold site. 

A warm site is somewhere between the restoration time and cost of a hot site and cold site. It is the most widely implemented alternate leased location. Although testing a warm site is easier than testing a cold site, a warm site requires much more effort for testing than a hot site. 

Figure 7-11 compares the components deployed in these three sites. 

| | Hot Site | Warm Site | Cold Site |
| — | — | — | — |
| Electrical Connection | Yes | Yes | Yes |
| Peripherals | Yes | Some | None |
| Networking | Yes | None | | None |
| Servers and Other Hardware | Yes | None | None |
| Applications | Yes | None | None |

Figure 7-11 Hot Site, Warm Site, and Cold Site Comparison 

### Tertiary Site

A **tertiary site** is a secondary backup site that provides an alternate in case the hot site, warm site, or cold site is unavailable. Many large companies implement tertiary sites to protect against catastrophes that affect large geographic areas. 

For example, if an organization requires a data center that is located on the coast, the organization might have its primary location in New Orleans, Louisiana, and its hot site in Mobile, Alabama. This organization might consider locating a tertiary site in Omaha, Nebraska, because a hurricane can affect both the Louisiana and Alabama Gulf coast. 

### Reciprocal Agreements 

A **reciprocal agreement** is an agreement between two organizations that have similar technological needs and infrastructures. In the agreement, both organizations agree to act as an alternate location for the other if either one of the organization's primary facilities is rendered unusable. Unfortunately in most cases, these agreements are hard to enforce due to various legalities. 

A disadvantage of this alternate site is that it might not be capable of handling the required workload and operations of the other organization. 

**NOTE** A mutual-aid agreement is a prearranged agreement between two organizations in which each organization agrees to provide assistance to the other in the event of a disaster. 

### Redundant Sites 

A **redundant site** (or mirrored site) is one that is identically configured as the primary site. A redundant or mirrored site is not a leased site but is usually owned by the same organization that owns the primary site. The organization is responsible for maintaining the redundant site. Multiple processing sites can also be configured to serve as operationally redundant sites. 

Although redundant sites are expensive to maintain, many organizations today see them as a necessary expense to ensure that uninterrupted service can be provided. 

## Redundant Systems, Facilities, and Power 

In anticipation of disasters and disruptive events, organizations should implement redundancy for critical systems, facilities, and power and assess any systems that have been identified as critical to determine whether implementing redundant systems is cost effective. Implementing redundant systems at an alternate location often ensures that services are uninterrupted. Redundant systems include redundant servers, redundant routers, redundant internal hardware, and even redundant backbones. Redundancy occurs when an organization has a secondary component, system, or device that takes over when the primary unit fails. 

Redundant facilities ensure that the organization maintains a facility at whatever level it chooses to ensure that the organizational services can continue when a disruptuve event occurs. 

Power redundancy is implemented using uninterruptible power supplies (UPSs) and power generators. 

Redundancy on individual components can also be provided. The spare components are either cold spares, warm spares, or hot spares. A cold spare is not powered up but can be inserted into the system if needed. A warm spare is in the system but does not have power unless needed. A hot spare is in the system and powered on, ready to become operational at a moment's notice. 

## Fault-Tolerance Technologies 

Fault tolerance enables a system to continue operation in the event of the failure of one or more components. Fault tolerance within a system can include fault-tolerant adapter cards and fault-tolerant storage drives. One of the most well-known faulttolerant systems is RAID, which is discussed earlier in this chapter. By implementing fault-tolerant technologies, an organization can ensure that normal operation occurs if a single fault-tolerant component fails. 

## Insurance 

Although redundancy and fault tolerance can actually act as preventive measures against failures, insurance is not really a preventive measure. If an organization purchases insurance to provide protection in the event of a disruptive event, the insurance has no power to protect against the event itself. The purpose of the insurance is to ensure that the organization will have access to additional financial resources to help in the recovery. 

Keep in mind that recovery efforts from a disruptive event can often incur large financial costs. Even some of the best estimates might still fall short when the actual recovery must take place. By purchasing insurance, the organization can ensure that key financial transactions, including payroll, accounts payable, and any recovery costs, are covered. 

Insurance actual cost valuation (ACV) compensates property based on the value of the item on the date of loss plus 10 percent. However, keep in mind that insurance on any printed materials covers only inscribed, printed, or written documents, manuscripts, or records. It does not cover money and securities. A special type of insurance called *business interruption insurance* provides monetary protection for expenses and lost earnings. 

Organizations should annually review insurance policies and update them as necessary.

## Backup 

Data backup provides prevention against data loss but not prevention against disruptive events. All organizations should ensure that all systems that store important files are backed up in a timely manner. Users should also be encouraged to back up personal files that they might need. In addition, periodic testing of the restoration process should occur to ensure that the files can be restored. 
Data recovery, including backup types and schemes and electronic backup, was covered in detail earlier in this chapter. 

## Fire Detection and Suppression 

Organizations should implement fire detection and suppression systems as part of any BCP. Fire detection and suppressions vary based on the method of detection/ suppression used and are discussed in greater detail in the “Environmental Security and Issues” section of Chapter 3. 

## High Availability 

**High availability** in data recovery is a concept which ensures that data is always available using redundancy and fault tolerance. Most organizations implement high-availability solutions as part of any DRP.

High-availability terms and techniques that you must understand include the following: 

⁃
**Redundant Array of Independent Disks (RAID)**: A hard-drive technology in which data is written across multiple disks in such a way that a disk can fail and the data can be quickly made available from the remaining disks in the array without restoring from a backup tape or other backup media.
⁃
**Storage-area network (SAN)**: High-capacity storage (several petabytes) devices that are connected by a high-speed private network using storagespecific switches.
⁃
**Failover**: The capacity of a system to switch over to a backup system if a failure In the primary system occurs. 
⁃
**Failsoft**: The capability of a system to terminate noncritical processes when a failure occurs. 
⁃
**Clustering**: A capability of a software product that provides load-balancing services. With clustering, one instance of an application server acts as a master controller and distributes requests to multiple instances using round-robin, weighted round-robin, or least-connections algorithms.
⁃
**Load balancing**: A capability of a hardware product that provides load-balancing services. Application delivery controllers (ADCs) support the same algorithms but also use complex number-crunching processes, such as per-server CPU and memory utilization, fastest response times, and so on, to adjust the balance of the load. Load-balancing solutions are also referred to as farms or pools. 

## Quality of Service 

**Quality of service (QoS)** is a technology that manages network resources to ensure a predefined level of service. It assigns traffic priorities to the different types of traffic or protocols on a network. QoS deploys when a bottleneck occurs and decides which traffic is more important than the rest. Exactly what traffic is more important than what other traffic is based on rules the administrator supplies. Importance can be based on IP address, MAC address, and even service name. However, QoS works only when a bottleneck occurs in the appropriate location and the settings are bandwidth declarations. For example, if the QoS settings are set beyond the ISP's bandwidth, traffic will not be prioritized if a router thinks there is enough available bandwidth. But what if the ISP's maximums are being met, and the ISP decides what is or is not important? The key to any QoS deployment is to tweak the settings and observe the network over time. 

## System Resilience 

**System resilience** is the ability of a system, device, or data center to recover quickly and continue operating after an equipment failure, a power outage, or another disruption. It involves the use of redundant components or facilities. When one component fails or is disrupted, the redundant component takes over seamlessly and continues to provide services to the users.


