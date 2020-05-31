# 31257 IS Development Methodologies - Group Project

## Students
* Arezva Aiser (13408570)
* Mehmet Ata Bal (13396700)
* Saurab Bhave (12577589)
* Ryan Dawson (13270006)

## Project Group
* Group 1

## Tutor and Tutorial Time
* Juan Castilla Rho
* Tutorial Group 7, Friday 12:00PM - 1:30PM 

# Executive Summary
The following report contains an analysis on an information systems development project. The project concerns a major travel company that wants to develop an IS to improve the operations of their CMC. The report has found the major issues faced by Inbound Callers, Outbound Call Customers and Relationship Managers. This report has captured the perspectives of these stakeholders and produced system models that outline how the proposed IS operates. The report has been produced following SCRUM methodology and references the design thinking approach applied during development.

# Problem Definition
## Problem Analysis
The Travel Agency Information System (IS) project is focused on improving the operation of their Call Management Centre (CMC). To accurately assess the problem at hand, the ‘empathy’ analysis framework, as outlined by Hasso Platner Institute of Design at Stanford (n.d.) has been utilised. Through analysing the project brief, three key stakeholders have been identified: Inbound Callers, Outbound Call Customers and Relationship Managers (RM). The scope of this analysis will be focused on the CMC. Common problems faced by these stakeholders are listed below.

### Inbound Callers
For Inbound Callers, the following problem areas were identified:
* Inability to reach a resolution for their service issues or enquiries
* Displeasure with long wait times
* Inability to receive the information required for their service enquiry
* Bombarded with sales pitches regardless of the subject matter of the call
* Uninformed RM's
* Complicated answering machine menus

### Outbound Call Customers
For Outbound Call Customers, the following problem areas were identified:
*	Customers are offered holiday packages that are not appropriate for their budget
*	Customers are offered holiday packages to destinations they are not interested in
*	Customers are receiving multiple sales calls, even after rejecting previous offers
*	Customers are receiving calls at unsuitable times
*	Customers are unaware of the caller ID and consequently reject the call
*	Customer service quality has varied between RM’s, leading to inconsistent service

### Relationship Managers
For RM’s, the following problem areas were identified:
*	Lack of customer information and data
*	Difficulties with dealing with inbound calls due to a lack of information
*	Inability to hold the customer’s attention during an outbound call
*	Concerns with their individual performance against KPI benchmarks

The problems faced by these stakeholders have been analysed further, with deeper insights gathered from their unique perspectives. The insights gathered can be found in the Emapthy Maps below.

## Problem Definition
The current CMC system routes RM’s to customers without analysing and considering contextual information regarding both customers and RM’s. The current system poses the risk of high customer churn, poor customer service quality and loss of sales opportunities due to uninteresting, impersonal, and ineffective customer conversations.

## Project Objectives
1.	Improve Sales Pitch
      * Segment customer profiles based on social and cultural parameters
      *	Assess RM’s based on product knowledge and sales performance
      *	Generate a sales pitch guide based on the customer profile
2.	Improve Call Volume Management
      *	Direct customers to an Interactive Voice Response (IVR) system
      *	Reduce wait times for customers
3. 	Improve Customer Service
      *	Provide a skill score for each RM
      *	Create a target customer list for each RM based on their skill score and profile
      *	Match customers and RM’s based on skill scores and profiles
4.	Minimise CMC Costs
      *	Improve RM productivity and efficiency 
      *	Increase CMC sales results

## Stakeholder Analysis
The Stakeholder Register below contains a list of stakeholders and their relationship with the CMC IS in development. Both primary and secondary stakeholders have been identified.

<p> 
<i>Figure 1A: Stakeholder Register</i>
</p>

| Stakeholder                   | Responsibility                                                                                                                      | Concerns or Fears                                                                                        |
|-------------------------------|-------------------------------------------------------------------------------------------------------------------------------------|----------------------------------------------------------------------------------------------------------|
| Relationship Manager      | Handle service enquiries, create sales opportunities, manage customer relations, maintain product knowledge                                                                                       | Low sales performance, poor customer service rating, unsatisfied customers, customer complaints                                                         |
| Inbound Call Customer         | Service enquiries, purchasing holiday packages                                                                    | Unresolved issues, unwanted purchases                                                |
| Outbound Call Customer        | Service enquiries, purchasing holiday packages                                      | Unresolved issues, unwanted purchases, untimely calls                                   |
| CMC Management Team               | Manage RM performance, organise day-to-day business operations, meet performance targets                                               | Poor CMC sales performance, poor financial results, RM’s not performing, high customer churn                                           |
| Travel Agency Directors                  | Supervise business operations, provide vision and direction for the company, create a unique offering, handle finances                                            | Declining revenues, declining profits, unsatisfied investors                                                          |
| Potential Investor                      | Raise capital, attend company votes                                                                                                               | Declining share value, low dividend yields                                                              |
| Accommodation Company         | Provide accommodation for customers                                                                                                | Low number of customers                                                        |
| Transportation Company        | Provide transportation solutions for customers.                                                                                     | Low number of customers                                                       |
| Department of Tourism         | Promote tourism, provide tourism agencies with resources, develop initiatives | Declining tourism industry                                                                              |
| State & Territory Governments |Provide tourism sector with resources and policy, investigate issues across industry                              | Declining tourism industry, misconduct within companies |


## Empathy Maps
### Relationship Managers
<i> Figure 1B: RM Empathy Map 1 </i>
![Empathy Map RMs 1](https://github.com/SaurabBUTS/ISDM-Group-1-Tut-07/blob/master/EmpathyMap_RMs/Empathy%20Map%20RMs%201.png)
<i> Figure 1C: RM Empathy Map 2 </i>
![Empathy Maps RMs 2](https://github.com/SaurabBUTS/ISDM-Group-1-Tut-07/blob/master/EmpathyMap_RMs/Empathy%20Map%20RMs%202.png)
### Inbound Callers
<i> Figure 1D: Inbound Caller Empathy Map 1  </i>
![Empathy Map Inbound Callers 1](https://github.com/SaurabBUTS/ISDM-Group-1-Tut-07/blob/master/EmpathyMap_InboundCalls/Empathy%20Map%20Inbound%20Callers%201.png)
<i> Figure 1E: Inbound Caller Empathy Map 2 </i>
![Empathy Map Inbound Callers 2](https://github.com/SaurabBUTS/ISDM-Group-1-Tut-07/blob/master/EmpathyMap_InboundCalls/Empathy%20Map%20Inbound%20Callers%202.png)
### Outbound Call Customers
<i> Figure 1F: Outbound Call Customer Empathy Map 1 </i>
![Empathy Map Outbound Callers 1](https://github.com/SaurabBUTS/ISDM-Group-1-Tut-07/blob/master/EmpathyMap_OutboundCalls/Empathy%20Map%20Outbound%20Callers%201.png)
<i> Figure 1G: Outbound Call Customer Empathy Map 2 </i>
![Empathy Map Outbound Callers 2](https://github.com/SaurabBUTS/ISDM-Group-1-Tut-07/blob/master/EmpathyMap_OutboundCalls/Empathy%20Map%20Outbound%20Callers%202.png)


# Design Thinking Approach
## Reflection and Brainstorming


## Project Assumptions
The following assumptions have been made to guide the creation of the Empathy Maps and UML Models.
* The current IVR system features a complicated menu for customers to navigate
* The current IVR system averages long wait times (>10 minutes)
* The current CMC IS does not collect customer data and information
* The current CMC IS does not record RM performance metrics 
* The current CMC IS randomly assigning RM’s to customers for both outbound and inbound sales calls
* The Travel Agency has a large budget to complete the IS project
* The Travel Agency is somewhat flexible on project completion timelines 


## SCRUM Methodology
The SCRUM Methodology is defined as a framework within which people can address complex adaptive problems, while productively and creatively delivering products of the highest possible value (Schwaber & Sutherland 2017). The following section will explain the key elements of SCRUM and explain how the methodology was used in this project.

### User Stories
User stories are high level product features that are written from different stakeholders' perspectives. It is important to note that User stories typically aim to capture user perspective functionality (or High-Level functionality) rather than technical details. User stories commonly follow a predefined structure and are written as follows:
<p>"As a [persona], I [want to], [so that]." (Rehkopf M. n.d.)</p>
User stories aim to encourage developers to empathise with stakeholders involved with the system in development. It is presumed that if developers can empathise with stakeholders, the system will accurately reflect the needs and wants of stakeholders. Lucassen G et al. (2016) cites the simple structure of user stories to facilitate a common understanding concerning the project requirements.
The group utilised user stories to empathise with the stakeholders involved within the CMC IS. The user stories assisted in the ideation process, enabling the team to visualise the required functionality from an end-user’s perspective.

### Product Backlog
The Product Backlog is a collection of user stories. The product backlog is also used to register task statements that are not written from a user perspective. The backlog is a tool that assists with project tracking, identifying the functionalities that have been implemented and those still to be implemented. Typically, the Product Owner manages the backlog with assistance from the Scrum Master. A product backlog is updated continuously throughout the product lifecycle, as new feedback from stakeholders is incorporated (Schwaber & Sutherland 2017). 
<p>The group produced a product backlog that only included User Stories, as well as a separate GitHub Issues Page, where member independent tasks were listed. Configuring the backlog in this manner helped in visualising the final product and the required functionality. The backlog was used for sprint planning, where the team estimated an approximate time of implementation for each user story and therefore an estimate for the length of each sprint. The backlog was a useful tool for time management.  
The team’s product backlog and issues page can be viewed below.</p>

<i> Figure 2A: Product Backlog </i>
![Product Backlog](https://github.com/SaurabBUTS/ISDM-Group-1-Tut-07/blob/master/static/images/product_backlog.png)

<i> Figure 2B: Issues Pages </i>
![Issues](https://github.com/SaurabBUTS/ISDM-Group-1-Tut-07/blob/master/static/images/issues.png)

### Sprints
Sprints are defined as a timebox of one month or less during which the team produces a potentially shippable product increment (The Agile Alliance n.d.). Sprints involve the development and implementation of select user stories that are contained in the Sprint Backlog. Sprints enables early testing and continuous improvement during the development process. Typically, sprints start with a planning session to determine the contents of the Spring Backlog. Sprints conclude with a review and retrospective meeting, where the product is presented to the Product Owner and stakeholders.   
<p>The team divided User Stories across three sprints. Working in Sprints enabled the team to conduct regular meetings and keep each other updated on the progress of their assigned tasks. Finally, sprints were useful for time management, as the required completion times were estimated during sprint planning.</p>

### Sprint Backlogs
Sprint Backlogs are a subset of the product backlog, where user stories that are to be implemented in an active sprint are listed. The team modifies the Sprint Backlog during a Sprint. Ideally, the backlog should be organised so that all User Stories should result in a shippable increment of the product.
<p>The group utilised Sprint Backlogs when dividing the User Stories across the three Sprints. The backlog allowed the group to visualise the shippable product across different stages of development.</p>

### SCRUM Roles
1. <b>Product Owner</b>

The Product Owner clarifies what issues the final product should solve. The Product Owner manages and edits the product backlog, ideally in conjunction with the Scrum Master and Development Team. The Product Owner’s main responsibility is to maximise the value of product resulting from the work of the development team (Schwaber & Sutherland 2017).
<p>The Product Owner for the CMC IS was Juan Castilla Rho. Sprint Planning and changes to the final product were discussed with him. However, unlike in traditional SCRUM practice, Juan was not managing The Product Backlog - rather, the project group did.</p>

2. <b>SCRUM Master</b>

The Scrum Master is responsible for ensuring the team follows agile values and principles (The Agile Alliance n.d.). The Scrum Master’s purpose is to lead the development team using SCRUM practices and serves as a bridge between developers and the product owner and stakeholders.
<p>The team did not assign a Scrum Master, rather the responsibility was divided equally amongst members. However, it should be noted that this was only due to the project being an assessment task. It is good practice to assign a Scrum Master and it is recommended for project development cycles.</p>

3. <b>Development Team Member</b>

The Development Team conducts the technical development for the project. Team members typically have different roles such as programmer, systems architect, and tester. The SCRUM methodology expects a high degree of self-organisation from the development team. As such, the team is required to adjust to each other and display a high degree of teamwork.                                                        <p>Besides the UML diagrams, group members were not assigned tasks based on their technical expertise. All members were responsible for delivering several sections of the final report. This was decided as the project is not intended to move to a real development stage. Accordingly, all members were apart of design process.</p>

### Daily Scrum
Daily SCRUMs are short meetings at the beginning of each day. The purpose is to update the SCRUM team on each member’s progress, identify obstacles, incorporate new ideas and receive feedback. Typically, each team member must answer a certain set of questions during the meeting (Schwaber & Sutherland 2017), including:
* What did I do yesterday that help the Development Team meet the Sprint Goal?
* What will I do today to help the Development Team meet the Sprint Goal?
* Do I see any impediments that prevent me or the Development Team from meeting the Sprint Goal?
<p>Our project team conducted SCRUM meetings twice a week. The meetings allowed for each member to be updated about each other’s progress, review obstacles and suggestions for improvement.</p>

### Sprint Retrospective
A Sprint Retrospective is a meeting that discusses how the successes and failures of the previous sprint and identifies adjustments for the next Sprint (The Agile Alliance n.d.). The Sprint Retrospective marks the end of each Sprint. It is a useful tool for self-improvement.
The project team did not complete a traditional Sprint Retrospective. The Sprint Retro was completed via online messaging platforms, where each member reflected upon their progress at the end of each sprint. As such, the group’s sprint retrospectives were documented and accessible to all team members.

## How Might We Statements
The following HMW statements were generated using the POV statements. Note, POV statements can be found in the Product Backlog in the GitHub Repository. 
* HMW minimise call waiting times?
* HMW generate skill scores for RM’s?
* HMW create RM profiles?
* HMW create Customer Profiles?
* HMW decide which RM to match a customer to
* HMW calculate the likelihood of an outbound call customer to purchase a holiday package?
* HMW create a list of target customers?
* HMW direct customers using the IVR? 

# Workproducts and Models
## Use Case Diagram
<i>Figure 3A: CMC Use Case Diagram</i>
![CMC Use Case Diagram](https://github.com/SaurabBUTS/ISDM-Group-1-Tut-07/blob/master/Diagrams/CMC%20Use%20Case%20Diagram.png)

## Class Diagram
<i>Figure 3B: CMC Class Diagram</i>
![ClassDiagram](https://github.com/SaurabBUTS/ISDM-Group-1-Tut-07/blob/master/Diagrams/Class%20Diagram/ClassDiagram.png)

## Activity Diagrams
<i>Figure 3C: CMC Activity Diagram - Inquiry</i>
![activityDiagram_Inquiry](https://github.com/SaurabBUTS/ISDM-Group-1-Tut-07/blob/master/Diagrams/Activity%20Diagrams/activityDiagram_Inquiry.PNG)

<i>Figure 3D: CMC Activity Diagram - Confirm Booking</i>
![activityDiagram_ConfirmBooking2](https://github.com/SaurabBUTS/ISDM-Group-1-Tut-07/blob/master/Diagrams/Activity%20Diagrams/activityDiagram_ConfirmBooking2.PNG)

<i>Figure 3E: CMC Activity Diagram - Make Booking</i>
![activityDiagram_MakeBooking2](https://github.com/SaurabBUTS/ISDM-Group-1-Tut-07/blob/master/Diagrams/Activity%20Diagrams/activityDiagram_MakeBooking2.PNG)

<i>Figure 3F: CMC Activity Diagram - Cancel Booking</i>
![activityDiagram_Cancel2](https://github.com/SaurabBUTS/ISDM-Group-1-Tut-07/blob/master/Diagrams/Activity%20Diagrams/activityDiagram_Cancel2.PNG)

<i>Figure 3G: CMC Activity Diagram - Outbound Call</i>
![activityDiagram_Call](https://github.com/SaurabBUTS/ISDM-Group-1-Tut-07/blob/master/Diagrams/Activity%20Diagrams/activityDiagram_Call.PNG)

<i>Figure 3H: CMC Activity Diagram - Customer and RM Matching</i>
![activityDiagram_Matching](https://github.com/SaurabBUTS/ISDM-Group-1-Tut-07/blob/master/Diagrams/Activity%20Diagrams/activityDiagram_Matching.PNG)

<i>Figure 3I: CMC Activity Diagram - Target List</i>
![activityDiagram_TargetList](https://github.com/SaurabBUTS/ISDM-Group-1-Tut-07/blob/master/Diagrams/Activity%20Diagrams/activityDiagram_TargetList.PNG)

## Collaboration Diagrams
<i>Figure 3J: CMC Collaboration Diagram - Inbound Calls</i>    
![Collaboration Diagram - Inbound Calls](https://github.com/SaurabBUTS/ISDM-Group-1-Tut-07/blob/master/Diagrams/Collaboration%20Diagrams/Collaboration%20Diagram%20-%20Inbound%20Calls.PNG)

<i>Figure 3K: CMC Collaboration Diagram - Outbound Calls</i>
![Collaboration Diagram - Outbound Calls](https://github.com/SaurabBUTS/ISDM-Group-1-Tut-07/blob/master/Diagrams/Collaboration%20Diagrams/Collaboration%20Diagram%20-%20Outbound%20Calls.PNG)

# Competitive Advantages
## Customer Satisfaction
* <b>Skills-based Routing</b>

The CMC IS implements a skills-based routing system for inbound calls that matches the RM’s with customers based on their previous call history, profile and skill score. Accordingly, the CMC can expect an increase in first-call resolution rates as the most appropriate RM will be matched with customers to ensure service enquiries are resolved quickly. If service enquiries are resolved on first contact, there will be an increase in the number of sales opportunities for the CMC, as RM’s are able to efficiently allocate their time to sales calls and enquiries. Outbound calls are assigned to RM’s via a customer target list that matches the customer’s profile with an RM. RM’s are provided a system-generated sales pitch that matches the customer’s profile. Resultantly, RM’s can provide a personalised and rewarding experience for customers, thereby improving customer relations and sales conversion rates. 

* <b>Call Volume Management</b>

The CMC’s Interactive Voice Response (IVR) System will significantly improve load management during busy periods. Customers will be redirected to the most suitable RM who are already privy to their customer profile and enquiry details. The IVR system ensures that customers feel that their enquiries are treated with care and provides a timeline for resolution, resulting in a higher quality customer experience.  

## Highly Skilled Labour

* <b>Measuring Performance</b>

The IS provides the CMC management team with information regarding RM performance based on previous calls, sales conversions and problem resolution rates. Management will be able to determine how their RM’s follow company policies and procedures and how their RM’s are performing against KPI measures. 

*  <b>Training and Development</b>

The performance measures output by the IS provides management with training and development opportunities for their RM’s. Management will be able to identify problem areas and challenging scenarios that impact an RM’s sales and service performance. Management will be able to develop a training plan to improve RM performance so that the customer experience is enhanced and sales goals are met.     

## Cost Savings

The IS offers an opportunity to improve the productivity and efficiency of the RM’s. The CMC will witness a more efficient use of time and more productive allocation of resources to income generating activities, such as sales calls. An improvement in the quality of service provided by RM’s is likely to have the residual impact of attracting more customers to the travel agency due to high customer satisfaction and approval ratings. 

## Enhanced Reporting and Analytics

The travel agency can derive meaningful business insights from the IS. The IS will inform management about the number of calls, average call and wait times, average speed of answer and customer churn rates. Management will be able to easily identify problem areas, rectify issues and undergo process improvement. 

# Risks Posed by Project Failure
## Financial Loss

A failure to deliver an effective IS solution may lead to financial losses for the travel agency. The travel agency would have raised capital and allocated project costs for the IS solution. If the system were to fail, the company would not reap the competitive benefits of the system and will suffer a financial loss. Such a loss may result in negative performance reviews, pay cuts and potentially job loss.

## Reputational Risk

The IS developers may face a loss in reputation due to their inability to deliver the solution on time, within budget and as per client specifications. Consequently, the developers may face a reduction in clients and new project opportunities. 


# References
Cisco 2015, Advantages of Call Management System Services, viewed 20 May 2020, < https://community.cisco.com/t5/collaboration-voice-and-video/advantages-of-call-management-system-services/ba-p/3105615 >.

Hasso Platner Institute of Design at Stanford n.d., An Introduction to Design Thinking Process Guide, Stanford University ,Palo Alto, CA, United States.

Monster, B. 2020, ‘5 Ways to Avoid Putting Customers on Hold’, The Plum Voice, weblog, The Plum Group, < https://www.plumvoice.com/resources/blog/5-ways-avoid-putting-customers-hold-ever/>

Rehkopf M. n.d., The Agile Coach, Atlassian, viewed 25 May 2020, < https://www.atlassian.com/agile/project-management/user-stories > Lucassen G., Dalpiaz F., van der Werf J. M. E. M., Sjaak Brinkkemper 2016, 'The Use and Effectiveness of User Stories in Practice', Requirements Engineering: Foundation for Software Quality: 22nd International Working Conference, Gothenburg, Sweden, pp.205-222.

Schwaber K. & Sutherland J. 2017, The Scrum Guide, Scrum Guides, viewed 25 May 2020, < https://www.scrumguides.org/scrum-guide.html >.

The Agile Alliance n.d., Agile Glossary: Scrum, viewed 26 May 2020, < https://www.agilealliance.org/glossary/scrum/# >.
