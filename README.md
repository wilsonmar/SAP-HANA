# SAP-HANA 

This repo provides a complete package for ensuring that SAP HANA implementions
go quickly and end up with performant apps.

Elements of this project include sample code, code generators, and training materials.

## What is SAP-HANA?

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
This is a whole paradigm change to looking at outcomes
rather than process metrics.

For example, ERP material planners are transitioning from MRP Classic to MRP Live on SAP HANA.
<a target="_blank" href="http://searchsap.techtarget.com/answer/How-is-MRP-Live-MRP-on-SAP-HANA-different-from-MRP-Classic">
TechTarget says:</a> MRP Live enables planners to simulate 
<strong>"what-if" scenarios</strong>
in real time to provide a preview of required capital tie-up, required production capacities, and inventory controlling. 
These features are the same as those available in the SAP Long Term Planning simulation tool.

But MRP Live is far speedier than its predecessor, enabling planners to execute materials planning on shorter planning cycles so that the materials' demand-and-supply situation is visible almost on a real-time basis. 
Moreover, the system enables planners to identify and take actions on urgent issues. To support planners' work using MRP Live, the 
MRP Cockpit 
offers several dashboards that enable them to monitor key performance indicators such as delayed materials deliveries from vendors, delayed shipments to customers or expected materials shortages. 
MRP Live also offers functionality to selectively plan materials or a group of materials, which was not available in MRP Classic. 

### The productivity cost of switching
Where MRP Live is missing functionality -- for example, planning materials of special procurement types are still not fully available in MRP Live -- the system switches to MRP Classic to plan relevant materials. Special procurement types include subcontracting (outsourcing), interplant transfer and direct procurement or production.

### Availability Metrics
A proactive approach to measure productivity 
must continue to include at its core
<strong>availability</strong>, but to do it throughout the deployment lifecycle
as a predictor of future availability.
Systems do not magically stabilize overnight, but gradually over time.

Availability (and underlying capacity) is critical for real-time servers, especially the
<a target="_blank" href="http://scn.sap.com/docs/DOC-59784">
SLT (SAP Landscape Transformation)</a> trigger-based replication server 
running on the NetWeaver Platform
to provide a stream of data into HANA from SAP ERP or non-SAP systems.
As a rule of thumb, one dedicated replication job per large table is recommended.

![hana slt within data input servers](https://cloud.githubusercontent.com/assets/300046/13437736/a555e8ba-df9a-11e5-8c1d-783e68778c85.JPG)

Transaction IUUC_REPL_CONTENT for Data and Structure Transformation specification UI.

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

## UI Testing

SAPUI5 is the Javascript framework using HTML5 and CSS3.

OData is the format which JavaScript uses to transfer data to the HCP.
So a test framework can focus only on data transfer.

## SAP S/4HANA Components

QUESTION: Traditional SAP Business Suite users move to SAP Business Suite on SAP HANA,
then transition to SAP S/4HANA?

http://sap.com/S4HANA
based on the SAP Fiori UI across mobile, desktop, tablet
for End-to-end business processes:

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

## XS Advanced
SAP HANA was first delivered November 2010.

Solution release SPS11 adds Advanced edition of XS (eXtended Services) 
<strong>apps running in the HANA database</strong> (without an additional app server)
with run-time containers running:

* JavaScript on Node.js XSJS (runs on V8 instead of Mozilla SpiderMonkey, but major inconsistencies are not expected) 
* Java on TomEE
* C++ via FastCGI

The xs command-line utility is provided.

Source control is Git/Github with custom support for Containers
with HDI (HANA Deployment Infrastructure)
that integrates with Jenkins and Garret.

## More About SAP
* http://sapterm.com/
  Terms

* http://help.sap.com/saphelp_glossary/en/index.htm

