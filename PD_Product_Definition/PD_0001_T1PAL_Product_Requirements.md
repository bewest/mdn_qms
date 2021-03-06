---
repository: "github.com/ehwest/mdn_qms"
folder: "PD"
title: "PD_0001_T1PAL_Product_Requirements.md"
document_id: "PD_0001"
authors:
- github.com/ehwest
approvers:
- github.com/bewest
revision: "05"
approval_date: "2020-08-24"
effective_date: "2020-08-24"
description: "T1Pal Product Requirements"
---


## T1Pal System Requirements

### Informative Framework Information

This document provides the framework and requirements for T1Pal software
both understood to be as a:
 1. "Medical Device" (an FDA term), and 
 2. "Software "as a service" (SaaS, an Information Technology term)."

T1pal (aka T-one-pal, t1pal.com, T1Pal) is an operating software complex that is entirely
accessed through the Internet for all its purposes and capabilities.  All users of this T1Pal.com software access it 
through the Internet, including administrative users, anonymous users, subscribers, 
security auditors, lawful law enforcement investigators, and maintenance
workers.

T1pal is operated by, and is the product of, Medical Data Networks LLC., and other "partner organizations."
Notably, this includes developers of "Nightscout" project, and multiple open-source software providers.

Copies of the software complex may be deployed in other countries as may
be needed for regulatory purposes.  However, at this writing, all copies
of the software are operated within the United States.

The requirements for T1Pal are intentionally aligned with requirements set forth by the FDA for
"Software as a Medical Device" found in the FDA regulations
[here.](https://www.accessdata.fda.gov/scripts/cdrh/cfdocs/cfpcd/classification.cfm?id=668)

One of the purposes of T1Pal is to create notifications to notify another person, a follower, 
of the patient's continuous glucose monitoring system sensor glucose information in real time. 
Therefore, based on the FDA applicable language, T1Pal is a "Continuous Glucose Monitor Secondary Display".
Please see [PD_0002 Intended Use](./PD_Product_Definition/PD_0002_Intended_Use.md) for a definitive 
statement of T1Pal intended use.

The secondary 
display of T1PAL.COM does not replace primary real time continuous glucose monitoring or standard 
home blood glucose monitoring -- for any purpose whatsoever.
The T1Pal product will be labelled appropriately to convey this important principle.

The complete T1Pal software complex is comprised of a number of semi-independent 
components and "micro-services", each installed on 
one or more 3rd party computing systems.

The T1Pal system receives and then creates displays 
of real-time patient data from one or more continuous glucose monitors (CGMs).

In addition to CGM data, however, 
the T1Pal system receives and displays real-time patient data derived from sources other
than a CGM system sensor. 

Specifically, T1Pal also displays secondary display data transmitted by one or more
infusion pump devices, and one or more control processor
(such as the Tidepool Loop controller).

Like the CGM data, pump infusion data (including settings, changes to settings, and faults), and
contoller data (including settings, changes to settings, and faults) also supporting secondary
display of their own data enabled by T1Pal.

It should be noted that ALL of the displays and reports generated by T1Pal are secondary displays
of data, and the patient is expected to refer to primary device displays for any purposes that involve
computing and/or executing any needed therapy.

Consistent with its role as a secondary display, T1Pal.com requires no prescription.

To use the software, consumers must apply for a monthly subscription-based
access to the server complex to receive the benefits of the service.
Subscribers access the service by using any of the following devices:
 + iPhone cell phone with an interent data service plan
 + Androidcell phone with an internet  data service plan
 + desktop or laptop PC with Firefox browser and Internet connectivity

T1Pal is intended to comply with the FDA definition of 
[Software as a Medical Device](https://www.fda.gov/media/119722/download)

## Enumerated Product Requrements

### REQ_1000
T1Pal is an "Integrated Continuous Glucose Monitoring System" intended to be a secondary display
of real-time measures of bodily fluids frequently. 

### REQ_1010
T1Pal displays data that is securely obtained and delivered by electronic messages from multiple "other" devices that themselves that provide "primary" display data.
These "multiple other" devices include:  
 + insulin dosing systems, 
 + integrated Continuous Glucose Monitoring systems (iCGM).
 + software devices that collect food consumption data
 + software devices that collect exercise and related event data

### REQ_1020
T1Pal provides a display of data that combines data from multiple sources and displays a consolidated view of the data such that the timing of reports of bodily fluids are synchronized in time.
Sources of data displayed on the T1Pal system are required to comply with agreed data communications requirements.  

Products that currently do comply with T1Pal system agrements include:  
 + Dexcom G4, G5 products that use the Dexcom Share Service phone-based application and bluetooth bridge.
 + Dexcom's G6 continuous glucose monitoring system, using Dexcom Follow service. 
 + Insulet's Omnipod Insulin Management system, 
 + MiniMed insulin pump system from Medtronic, 
 + Medtronic's Guardian Connect CGM system.


### REQ_1030
T1Pal, as a "secondary display" depends on the continuous performance and reliability 
of the "primary" sources of data displays.
Since the intended use of the T1Pal software device is to provide supplemental technical support to device users,  the continuous performance and reliability of T1Pal shall exceed that of its data sources.
Therefore, individual medical device outages shall be highlighted on the T1Pal display.

Please see [PD_0002 Intended Use](./PD_Product_Definition/PD_0002_Intended_Use.md) for a definitive 
statement of T1Pal intended use.

### REQ_1040
T1Pal enforces compliance to HIPAA privacy requirements.

### REQ_1050
T1Pal provides for the subscriber to generate secure internet service links that, when transferred to other individuals, enables them to temporarily gain access to view the T1Pal reports.
These links become expired under control of the subscriber.

Please see [PD_0002 Intended Use](./PD_Product_Definition/PD_0002_Intended_Use.md) for a definitive 
statement of T1Pal intended use.

### REQ_1060
T1Pal software shall operate in such a way that new features may be added, existing bugs may be fixed, and performance may be improved without pausing services delivered to subscribers.

### REQ_1070
T1Pal software shall operate in such a way that subscribers may access assistance and report apparant bugs at any time.


## Responsibilities

 1. The CEO and VP-level employees are responsible for overseeing and maintaining this standard operating procedure and for assuring that all employees are trained in its requirements.
 2. It is the responsibility of all employees, contractors and departments at Medical Data Networks to adhere to this procedure.

