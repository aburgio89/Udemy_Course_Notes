*Course link: https://www.coursera.org/specializations/ibm-it-systems-administration-and-cloud-operations

# IBM IT Systems Administration and Cloud Operations Professional Certificate
## Foundations of IT Systems Administration
#### Module 1: Read and Inventory an Environment / "What do we have?"

The "IT Estate" includes all technology assets and resources an organization owns and/or uses to support its operations. This can include: servers, PCs, networking devices, software, cloud services, storage and virtualization and security controls. 

Three defining questions will help us structure an unfamiliar estate:
1. What counts as an asset?
2. Who owns it?
3. Where does the boundary end?

When faced with an unfamiliar and undefined estate:
* Define the boundaries of the estate so that the data collected is subjective.  
* Define each asset as a single item in an environment that can be told apart from any other item and pointed at on its own.
* Define discovery routes and blind spots. Which routes are available and what can they possible miss? 
* Define accountable roles, as in who is responsible for assets within the company. Defining owners provides crucial context and accountability. 

**Asset**: A single thing in the environment that can be told apart from every other thing and pointed out on its own: a host, a service, a volume, an application.
* Each asset needs identifying details such as version, address, or associated system.
* Assets may be counted by different approaches, but the approach must be chosen before the count begins. 

**Asset owner**: The role accountable for the asset, what it does, its condition and the decisions surrounding it. Not necessarily the heaviest user of the asset nor the budget that purchased it. 

**Discovery**: Any method by which you learn that something in the environment exists. Every method has a matching blind spot. 
* Self-reporting systems can only identify assets that are switched on and reachable. 
* Platform inventories can only identify assets visible within that platform.
* Purchase records can only identify assets tracks through purchases. 
* Handover notes can only identify prior recorded knowledge.

**Scope boundaries**: Define which parts of an organization are included in an inventory. May identify a physical site, a platform or tech stack, an environment, or a category of assets. 
* The scope boundary must be defined before counting begins.
* An inventory's boundary should be defined in a single boundary statement. An example is "the inventory covers every device issued to full-time employees, and excludes devices issued to contractors and visitors". 

Th inventory register should contain these 6 essential fields:
* Name, platform, ID, date, function, owner. 
___

#### Module 2: Servers, Services, Clients and Network Basics / "How does it all communicate?

Five questions to diagnose any connection:
* Which client is affected?
* What name does it use -- and does it resolve correctly?
* Can traffic reach the host and port?
* Is the service listening?
* Which conditions are checked vs. still unknown?

Quick terminology:
* **Host** --> The machine itself, physical or virtual. A host has an IP address.
* **Service** --> A program running on a host. One host can run many services. 
* **Server** --> A host that provides services.
* **Client** --> The device/program that makes a request. 
* **Listening service** --> A service waiting for connections on a specific port. 
* **Port** --> Number identifying which service on a host gets traffic. 
>  IP is the building, port is the apartment.
* **Protocol** --> Agreed upon rules for the conversation. 
	* TCP -> Reliable, connection-based.
	* UDP -> Fast, no guarantee of accuracy.
* **Name resolution** --> Turning a website name (URL) into an IP address.
* **DNS (Domain Name System)** --> The system that transmutes name resolutions.
* Layered thinking: Every request passes through layers (name 

There are a number of reasons a page can fail to load:
* DNS Failure
* Unreachable Address
* Firewall Block
* No Service Answer

The following checks should be made to separate the possible causes:
* Identify the host and service running on it. 
* Check the name/address returned by the client's resolver.
* Check whether a request reaches the far end and does a response return?
* Check whether the traffic is permitted to the services port. 


<!--stackedit_data:
eyJoaXN0b3J5IjpbLTE5OTE2MTQwNywxMTI3MTYzNTgxLC0xNT
k4OTIzMDcsOTk5NTkyNTA0LC0xODkzNzc0NzQ4LDI4ODk3ODcw
NSwtMTMyNDM1NDcxMywtMzgyNTk1Njg5LDk4NzgzMDQ5NSwyMD
c0MTY2MTI5LDE1NTA0NDEzNyw2MjY1ODY5NzksNjAxMTExMTE3
LC00OTY1MzMzNjQsLTE4OTIxNzczMjUsLTY2MTk1ODcyOSwtOD
A5MjI5NDMyLDcyMDg4OTUsLTE1OTg1OTE0MTFdfQ==
-->