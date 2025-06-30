# Smart-Irrigation-Management-System-
3 		- SIMS Team 
4 		- Project Overview
5 		- Problem Statement
6		- Application flow
7		- Solution Architecture
8		- Application Prototype
9		- Functional Analysis
10-12 	- Storyboard
13		- Business Model Canvas
14		- MoSCOW Analysis 
15		- Risk Assessment Log
16		- Technical Feasibility
17-18	- LSEPI Analysis
19		- Conclusion
20-21	- References
22-24    	- Appendices

Optimising water use in agriculture. Provide recommendations through machine learning technology. Provide a hardware and software based solution, tailored to specific farming requirements.

Project Overview
High population growth rates, increased food consumption and expansion of irrigated farm land are putting pressure on water and land resources globally (Rosa et al., 2020).

With 92% of UK landmass having at least 4G coverage, the UK is a feasible location for initial application of this system (GOV.UK, 2022)

Smart Irrigation Management System;

Optimising water use in agriculture.
Provide recommendations through machine learning technology.
Provide a hardware and software based solution, tailored to specific farming requirements.
UN sustainable goal 6 contributing to a sustainable future through effective water management.
Contributes to UN sustainability goal 12, by contributing to sustainable agricultural practice.

Problem Statement
According to the World Bank (Bank, 2020), farms utilising irrigation practices have proved to be twice as productive compared to rainfed agriculture.
However, inefficient irrigation practices can lead to the following;

Excessive water wastage
Insufficient crop yield
Land degradation
Poor crop quality
Strain on local ecosystems
Drought

Functional Analysis
Functional Requirements

Mobile Application

User Registration.
User Billing and Subscription management.
View ML driven irrigation recommendations.
Realtime/Historical infographics
User configured Notifications 

Receiver/Transmitter and Sensor

Measure soil moisture levels using capacitive sensors.
Data sent from sensors to receivers

Cloud System Infrastructure

Must support the integration of multiple data source apis for machine learning processing.
 
External Data APIs 

Must display relevant weather information: Temperature, humidity, wind speed, and weather event tracking. 
Water source information
Crop type information API: Growth stages, Crop coefficient 
Soil Information API: User-input for soil type.

Non-functional Requirements:

Performance

Sensors must be accurately calibrated to measure soil moisture levels. 
Application should be able to cope with a large volume of users without noticeable performance impact.

Portability

Application must be usable in regions with cellular data.

Scalability	
Application must be able to support up to 500,000 simultaneous users.
Compatibility 
Compatible on  both IOS and Android devices, potentially using React Native framework. 
Availability 
Accessible 24/7 on Mobile and Desktop devices.
System must have extensive disaster recovery and backup plans in the event of server shutdown. 
Security
Secure storage of sensitive user data. 
Compliance
System must comply with UK regulations for farming management tools and Data Protection regulation. 

