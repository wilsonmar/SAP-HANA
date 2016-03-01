# SAP-HANA

HANA technically refers to the <strong>in-memory</strong> columnar database
built for high performance with multi-core CPUs with parallelization of execution.

So HANA enables SAP to earn database license revenue
instead of Oracle. 

* ![SAP's Roadmaps on Service Marketplace](http://service.sap.com/saproadmaps)
   on SAP Service Marketplace (SMP).
* ![SAP's product and solutions roadmap](http://scn.sap.com/community/product-and-solution-road-maps)

## HANA for business

SAP's customer proof points (such as
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
One of the objectives to HANA adoption is to replace
traditional overnight batch processing with real-time processes.



HANA renders measurements of batch processing mostly obsolete.

Thus, measurements of improvement under HANA 
needs to focus not on just on the technical
speed such as how quickly batches can process transactions within a period of time,
but the increase in employee responsiveness 
and resultant increase in customer capture and satisfaction
that justify payback from migration to HANA.

![hana real-time atp times](https://cloud.githubusercontent.com/assets/300046/13437095/5803898a-df97-11e5-8e27-ece55c708c40.JPG)

The promise of fast change means that measurements include
the <strong>time from conception to realization</strong>
rather than just traditional SLAs from static system structures.



### Availability
A proactive approach to measure productivity 
must continue to include at its core
<strong>availability</strong>, but to do it throughout the deployment lifecycle
as a predictor of future availability.
Systems do not magically stabilize overnight, but gradually over time.

Availability (and underlying capacity) is critical for real-time servers, especially the
<a target="_blank" href="http://scn.sap.com/docs/DOC-59784">
SLT (SAP Landscape Transformation)</a> replication server which runs on the NetWeaver Platform
which provide a stream of data from SAP ERP or non-SAP systems into HANA.
As a rule of thumb, one dedicated replication job per large table is recommended.

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



## SAP S/4HANA Components

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

Separately in SAP HANA Platform but not S/4HANA:

* APO (Advanced Planning &amp; Optimization)
* SNC (Supply Network Collaboration)

CRM 7 is an add-on to S/4HANA.

http://www.experiencesaphana.com/community/resources/use-cases
Use Case Repository


## About SAP
* http://sapterm.com/

* http://help.sap.com/saphelp_glossary/en/index.htm

## Versions

* First delivered November 2010, 
Solution releases:
* SPS11
* SPS10
* SPS09

