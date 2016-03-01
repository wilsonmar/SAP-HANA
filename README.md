# SAP-HANA

HANA technically refers to the <strong>in-memory</strong> columnar database
built for high performance with multi-core CPUs with parallelization of execution.

So HANA enables SAP to earn database license revenue
instead of Oracle. 

![SAP's offcial Roadmap](http://service.sap.com/saproadmaps)
on SAP Service Marketplace (SMP).

## HANA for business

Its customer proof points (such as
![USHR](https://www.youtube.com/watch?v=YVsJA1CaXqE&t=1m55s)
claim 80X faster speeds.

![hana proof points](https://cloud.githubusercontent.com/assets/300046/13432866/3e2f9610-df84-11e5-865d-cbbfec4ddbfd.JPG)

Speed also comes from guided configuration, a simpler data model, 
and ![SAP's Fiori UI](https://experience.sap.com/fiori-design/).

![Types of fiori apps](https://cloud.githubusercontent.com/assets/300046/13432832/15738466-df84-11e5-8eb4-61f8db2392bd.JPG)

Faster speeds enables HANA to be marketed for supporting real-time decision making
and fast change in business processes. 
What SAP calls "Digital Transformation" is toward hyper-customization at scale
(lot sizes of 1, customer segmentation of 1, etc.).
Quick yet complex analytics support yield predictions and simulations for better decision making.
Removing obstacles yields more transparency for better collaboration. 

## Measurement
Because one of the objectives to HANA adoption is to replace
traditional overnight batch processing with real-time processes, 
measurements of batch processing has become an obsolete concept.

Measurements under HANA 
needs to focus not on just on the technical
speed such as how quickly batches can process transactions within a period of time,
but the increase in employee responsiveness 
and resultant increase in customer capture and satisfaction
that justify payback from migration to HANA.

The promise of fast change means that measurements include
the <strong>time from conception to realization</strong>
rather than just traditional SLAs from static system structures.



### Availability
A proactive approach to measure productivity 
must continue to include at its core
<strong>availability</strong>, but to do it throughout the deployment lifecycle
as a predictor of future availability.
Systems do not magically stabilize overnight, but gradually over time.

QUESTION: With cloud deployments, would the company have 
access to low-level CPU and memory statistics per server
since SAP maintains those servers?

## On-premise or cloud?

Although SAP makes a blanket statement that the 
Big Data and IoT components is deployable on-premise 
(through SAP partners such as HP) or as a cloud edition,
different existing Business Suite modules may 
migrate to the new landscape at different rates
using different approaches.

Moreover, cloud adoption means use of HCP (HANA Cloud Platform)
extensions for <strong>Node.js</strong> (JavaScript running on Chrome V8 engine on browsers
using SAPUI5 JavaScript library)
working on the browser-based SAP Web IDE 
instead of traditional ABAP Z coding.



## SAP S/4HANA

Traditional SAP Business Suite users move to SAP Business Suite on SAP HANA,
then transition to SAP S/4HANA?

http://sap.com/S4HANA
based on the SAP Fiori UI across mobile, desktop, tablet
for End-to-end business processes:
(SAPUI5 is the Javascript framework using HTML5 and CSS3)

* Procure to Pay
* Plan to Product
* OTC (Order to Cash)
* RTS (Request to Service)
* Core Human Resources
* Core Finance

* ATP (Availability to Promise) integrated into S/4HANA.

Separately in SAP HANA Platform are:

* APO (Advanced Planning &amp; Optimization)
* SNC (Supply Network Collaboration)

CRM 7 is an add-on to S/4.


http://www.experiencesaphana.com/community/resources/use-cases
Use Case Repository


## Learning and Certification
https://open.sap.com/

https://open.sap.com/courses/s4h4
over 4 weeks
SAP Activate is the unique adoption framework

![S4/HANA Cookbook](http://scn.sap.com/docs/DOC-64980)

Deep Dive
https://open.sap.com/courses/s4h2

Use Cases 4 hours over 3 weeks
https://open.sap.com/courses/s4h3

SAP videos on Youtube
https://www.youtube.com/channel/UC8cXSTGDhiZK5229zi-KTXA

https://training.sap.com/shop/certification-hub/


## About SAP
* http://sapterm.com/

* http://help.sap.com/saphelp_glossary/en/index.htm

## Versions

* First delivered November 2010, 
Solution releases:
* SPS11
* SPS10
* SPS09


## Development
The developer portal is at 
http://help.sap.com/hana_platform

SAP HANA Studio 

WIPE is the query and manipulation language

AFL (App Functional Library)
LCAPP (Light Cache Application)

HANA is written mainly in C++ and runs on the Linux operating system,
new SAP architecture framework of LSA++ (Layered Scalable Architecture).


## Operations
Guided Configuration

The HDB LCM (LifeCycle Manager) GUI is used to define typology components.

Each  HANA system consists of
* "XS" (for eXtended app Services) server is the web app server that hosts services
   such as statistics gathering, analytical queries and data replication
* Index server handles SQL MDX from client apps
* Name server
* option host


