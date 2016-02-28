# SAP-HANA

HANA technically refers to the <strong>in-memory</strong> columnar database
built for high performance with multi-core CPUs with parallelization of execution.

The big data and IoT components is deployable as an on-premise appliance or as a cloud edition.



Its customer proof points (such as
![USHR](https://www.youtube.com/watch?v=YVsJA1CaXqE&t=1m55s)
claim 80X faster speeds.
Speed also comes from guided configuration, a simpler data model, and SAP's Fiori UX.

Faster speeds enables HANA to be marketed for supporting real-time decision making
and fast change rate. 
The change is to "Digital Transformation" toward hyper-customization at scale
(lot sizes of 1, customer segmentation of 1, etc.).
Quick yet complex analytics support yield predictions and simulations for better decision making.
Removing obstacles yields more transparency for better collaboration. 

## Measurement
This means measurement of the actual payback from migration to HANA needs to focus not on just on the technical
speed such as how quickly batches can process transactions within a period of time,
but the increase in employee responsiveness and resultant incrase in customer capture and satisfaction.

## S4HANA
http://sap.com/S4HANA
based on the SAP Fiori UI across mobile, desktop, tablet
for End-to-end business processes:

* Procure to Pay
* Plan to Product
* Order to Cash
* Request to Service
* Core Human Resources
* Core Finance

http://www.experiencesaphana.com/community/resources/use-cases
Use Case Repository


## Learning
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


