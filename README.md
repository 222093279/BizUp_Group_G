# Group-G-
Educational ITC ASSESSMENT
LP Moloi 222093279,
TW Kayane 219015324,
KI Kalo  220046482,
DE Radile 219008327,
MV Tshabalala 222044346,

[ITC.Group.Assessment.Group.G.pdf](https://github.com/user-attachments/files/31424406/ITC.Group.Assessment.Group.G.pdf)


TW Kayane 219015324

10.1 Flutter Functions
The Flutter application shall provide:
•	User registration/sign-in where applicable.
•	Company dashboard.
•	Compliance status viewing.
•	Document viewing.
•	Certificate expiry viewing.
•	Tender opportunity viewing.
•	Tender qualification status viewing.
•	Tender submission status viewing.
•	Tender follow-up viewing.
•	Tender outcome viewing.
•	Notifications or reminders where implemented.
10.2 ASP.NET Functions
The ASP.NET web application shall provide:
•	Secure web access.
•	Company information management.
•	Compliance document management.
•	Certificate management.
•	Expiry-date management.
•	Tender opportunity management.
•	Tender requirement management.
•	Qualification assessment recording.
•	Tender submission management.
•	Follow-up management.
•	Tender outcome management.
•	Dashboard and reporting views where applicable.
10.3 Supabase Functions
Supabase shall provide:
•	User authentication.
•	Database connectivity.
•	Backend services.
•	Data storage access.
•	Secure communication between applications and the database.
•	User-specific data access.
________________________________________
11. Functional Requirements
Functional requirements define what the system must do.
FR1 — User Authentication
The system must allow authorised users to securely sign in.
FR2 — Company Information
The system must allow authorised users to manage relevant company information.
FR3 — Compliance Document Management
The system must allow users to add, view and manage company compliance documents.
FR4 — Certificate Management
The system must allow users to record certificate information.
FR5 — Document Expiry Tracking
The system must allow users to record and monitor document and certificate expiry dates.
FR6 — Compliance Monitoring
The system must allow users to determine which company compliance documents are current or require attention.
FR7 — Expiry Reminders
The system should notify or remind users when important documents are approaching their expiry dates.
FR8 — Tender Opportunity Management
The system must allow users to record and manage tender opportunities.
FR9 — Tender Requirements
The system must allow users to record tender requirements.
FR10 — Tender Qualification
The system must allow users to record whether the company meets the requirements of a tender.
FR11 — Tender Selection
The system must allow users to identify tenders that they intend to pursue.
FR12 — Tender Submission
The system must allow users to record submitted tender applications.
FR13 — Tender Deadline Tracking
The system must allow users to record and monitor tender deadlines.
FR14 — Tender Follow-up
The system must allow users to record follow-up dates and actions for submitted tenders.
FR15 — Tender Outcome
The system must allow users to record tender outcomes, including:
•	Awaiting outcome.
•	Appointed / successful.
•	Unsuccessful.
FR16 — Tender Status
The system must display the current status of each tender.
FR17 — Dashboard
The system should provide a centralised dashboard showing important compliance and tender information.
FR18 — Secure Data Access
The system must prevent unauthorised users from accessing another company's information.
________________________________________
12. Non-Functional Requirements
Non-functional requirements define how the system should operate.
NFR1 — Security
The system must protect company information from unauthorised access.
NFR2 — Usability
The interfaces must be understandable and easy for users to navigate.
NFR3 — Performance
The system should respond efficiently to normal user actions under suitable network conditions.
NFR4 — Availability
The system should be available when the required backend and network services are operational.
NFR5 — Data Integrity
The system must maintain accurate relationships between companies, documents, certificates and tender records.
NFR6 — Reliability
The system should reliably store and retrieve compliance and tender information.
NFR7 — Scalability
The system should be capable of supporting additional users, documents, certificates and tender opportunities as the project grows.
NFR8 — Maintainability
The application should use a structured architecture that allows future improvements and additional functionality.
NFR9 — Cross-Platform Support
The mobile component must use Flutter to support cross-platform development.
NFR10 — Privacy
The system must protect confidential company information and should not require unnecessary personal information.
________________________________________
13. System Requirements
13.1 Software Requirements
The proposed system will use:
•	Flutter Framework SDK.
•	Dart programming language.
•	ASP.NET.
•	Supabase.
•	PostgreSQL.
•	Supabase Authentication.
•	GitHub for source-code management.
•	Microsoft Project for project scheduling.
The existing SRS identifies Flutter/Dart, Supabase, PostgreSQL and Supabase Authentication as core technologies.
13.2 Database Requirements
The database should contain structured records for:
Data Area	Example Information
Company	Company name, registration information, contact information
Compliance Documents	Document name, type, status
Certificates	Certificate name, issue date, expiry date
Tender Opportunities	Tender title, reference number, organisation, deadline
Tender Requirements	Qualification requirements and required documents
Tender Qualification	Qualified, not qualified, under review
Tender Submissions	Submission date and status
Tender Follow-ups	Follow-up date, notes and action
Tender Outcomes	Appointed, unsuccessful, awaiting outcome
Each record must be associated with the appropriate company or authorised user.
13.3 Hardware / Environment Requirements
Users should have:
•	A smartphone or compatible mobile device for the Flutter application.
•	A computer with a modern web browser for the ASP.NET web application.
•	Internet connectivity.


LP Moloi 222093279

1. Project Title
Entrepreneurial Compliance and Tender Management System
The Entrepreneurial Compliance and Tender Management System is a proposed mobile and web-based application designed to help companies manage compliance documents, certificates, tender opportunities, tender qualification requirements, submissions, follow-ups and tender outcomes.
The proposed system will provide a centralised digital workspace where companies can monitor the validity of important documents, identify suitable tender opportunities, determine whether they meet tender requirements, track applications and follow up on tender outcomes.
The proposed technical architecture will use Flutter/Dart for the mobile application and ASP.NET for the web application, with Supabase/PostgreSQL providing shared backend and database services.
________________________________________
2. Problem Statement
The company currently faces challenges in managing its compliance documents, certificates and tender application processes.
The company needs to keep track of multiple documents and certificates, including their validity periods and expiry dates, to ensure that they remain current and meet the requirements of different tender opportunities. Managing these documents manually creates a risk that important certificates may expire without being renewed or that required documentation may not be available when a tender needs to be submitted.
The company also needs to identify which tender opportunities it qualifies for. Different tenders have different requirements, and the company needs to review these requirements before deciding whether an opportunity is suitable. Without an organised process, time and resources may be spent on opportunities for which the company does not meet the required criteria.
Another problem is keeping track of available tender opportunities, tenders that the company intends to pursue, tenders that have already been submitted and tenders that require follow-up. If submitted tenders are not followed up, the company may not know whether it has been appointed or whether the application was unsuccessful. This can result in missed business opportunities and wasted resources.
The company may also incur printing and preparation costs when producing the large number of documents required for tender applications. If these documents are repeatedly printed, prepared and submitted without an organised tracking process, unnecessary administrative costs can occur.
Therefore, there is a need for a centralised digital system that can assist the company in managing compliance documents, monitoring certificate expiry dates, identifying and assessing tender opportunities, tracking tender submissions, following up on applications and recording tender outcomes.
________________________________________
3. Purpose
The purpose of the proposed system is to provide a centralised digital platform for managing company compliance documents and tender opportunities.
The system is intended to improve the way the company:
•	Stores and manages compliance documents.
•	Monitors certificate validity periods.
•	Identifies documents that need to be renewed.
•	Records compliance requirements.
•	Identifies tender opportunities.
•	Determines which tenders the company may qualify for.
•	Tracks tenders that the company intends to pursue.
•	Records submitted tenders.
•	Monitors tender deadlines.
•	Follows up on submitted applications.
•	Records tender outcomes.
•	Reduces unnecessary printing and administrative work.
The purpose of the prototype is therefore to improve the organisation, visibility and management of compliance and tender-related activities.
________________________________________
4. Project Scope
4.1 Project Aim
The aim of the project is to develop an efficient digital compliance and tender-management platform that enables companies to maintain up-to-date compliance documentation, identify suitable tender opportunities, assess tender requirements, track applications and monitor tender outcomes from a centralised workspace.
4.2 Project Objectives
The system aims to:
1.	Allow companies to securely store and manage compliance documents and certificates.
2.	Allow users to record document issue dates and expiry dates.
3.	Monitor certificate and document validity periods.
4.	Identify documents and certificates that are approaching expiry.
5.	Help users maintain up-to-date company compliance information.
6.	Allow users to record tender opportunities.
7.	Allow users to record tender requirements and qualification criteria.
8.	Help users determine whether their company meets the requirements of a tender.
9.	Allow users to record tender opportunities they intend to pursue.
10.	Allow users to record tenders that have already been submitted.
11.	Allow users to track tender submission deadlines.
12.	Allow users to record tender follow-up dates.
13.	Allow users to record whether a tender is awaiting an outcome, successful or unsuccessful.
14.	Help users monitor whether the company has been appointed after submitting a tender.
15.	Reduce reliance on physical document management and unnecessary printing.
16.	Provide a centralised view of compliance and tender information.
17.	Reduce the risk of missing document renewal dates, tender deadlines and follow-ups.
4.3 Deliverables
The project deliverables will include:
1.	Flutter mobile application.
2.	ASP.NET web application.
3.	Supabase backend.
4.	PostgreSQL database.
5.	User authentication.
6.	Compliance document management functionality.
7.	Certificate expiry tracking.
8.	Tender opportunity management.
9.	Tender qualification tracking.
10.	Tender submission tracking.
11.	Tender follow-up tracking.
12.	Tender outcome tracking.
13.	Centralised company workspace.
14.	Initial Software Requirements Specification.
15.	Stakeholder interview evidence.
16.	Project documentation.
17.	GitHub project repository.
18.	Microsoft Project schedule.
4.4 Acceptance Criteria
The system will be considered acceptable when:
•	An authorised user can securely access the system.
•	A user can add company compliance documents.
•	A user can view stored compliance documents.
•	A user can record certificate expiry dates.
•	The system can identify certificates approaching expiry.
•	A user can record tender opportunities.
•	A user can record tender requirements.
•	A user can record whether the company qualifies for a tender.
•	A user can record tenders they intend to pursue.
•	A user can record submitted tenders.
•	A user can record tender deadlines.
•	A user can record tender follow-up dates.
•	A user can record tender outcomes.
•	A user can identify tenders that are awaiting an outcome.
•	Users cannot access unauthorised company information.
•	The mobile and web applications can communicate with the shared backend.
•	The system stores and retrieves information correctly.
4.5 Exclusions
The following features are excluded from the initial prototype unless confirmed by the stakeholder:
•	Automatic submission of tenders to external tender portals.
•	Guaranteeing that a company qualifies for a tender.
•	Guaranteeing successful tender applications.
•	Automatic legal interpretation of tender requirements.
•	Online payment processing.
•	Complete marketplace functionality.
•	Automated communication with tender issuing organisations.
•	Full accounting functionality.
•	Automatic generation of every tender document.
•	Integration with every external tender platform.
•	Automated appointment or contract award processing.
4.6 Constraints
The project is constrained by:
•	Available development time.
•	Available group resources.
•	Network connectivity.
•	Supabase availability.
•	Accuracy of information entered by users.
•	Different tender organisations having different requirements.
•	Availability and reliability of tender information.
•	Flutter/Dart application architecture.
•	ASP.NET web application architecture.
•	PostgreSQL database structure.
•	Authentication and security requirements.
4.7 Assumptions
The system assumes that:
•	Users have authorised accounts.
•	Users provide accurate company information.
•	Users enter correct certificate expiry dates.
•	Users upload valid compliance documents.
•	Users verify tender requirements before submitting applications.
•	Users update tender outcomes when information becomes available.
•	The system is used as a management and tracking tool rather than a replacement for official tender portals.
•	Users remain responsible for verifying official tender requirements and deadlines.



MV Tshabalala 222044346


14. Integration Requirements
IR1 — Authentication Integration
The Flutter and ASP.NET applications must use the selected authentication system to identify authorised users.
IR2 — Flutter to Supabase
Information submitted through the Flutter application must be stored through the backend.
IR3 — ASP.NET to Supabase
Information submitted or updated through the ASP.NET application must be stored through the backend.
IR4 — Shared Database
Both applications must use the shared PostgreSQL database where applicable.
IR5 — Compliance Data Integration
Compliance information entered into one application must be available to authorised users through the other application.
IR6 — Tender Data Integration
Tender opportunities, qualification information, submissions, follow-ups and outcomes must be stored centrally.
IR7 — Security Integration
The backend must enforce authorised access to company records.
IR8 — Data Retrieval
The applications must be able to retrieve stored information and display it to authorised users.
IR9 — Data Updates
Changes made to compliance or tender records must be reflected in the shared database.
The original SRS already establishes the principle that the client should authenticate the current user, obtain the user's ID, retrieve records, insert records, delete/update records and receive database responses.
________________________________________
15. Requirements Prioritisation
Priority	Requirement	Reason
Must Have	User authentication	Protects company information
Must Have	Compliance document management	Addresses the main stakeholder problem
Must Have	Certificate management	Required to manage compliance
Must Have	Certificate expiry tracking	Reduces the risk of expired certificates
Must Have	Tender opportunity management	Required to manage tender opportunities
Must Have	Tender qualification tracking	Helps determine suitable tenders
Must Have	Tender submission tracking	Prevents loss of submission information
Must Have	Tender follow-up tracking	Helps prevent missed outcomes
Must Have	Tender outcome tracking	Allows the company to know the result of applications
Must Have	Secure company data	Protects confidential business information
Should Have	Expiry reminders	Helps users renew documents before expiry
Should Have	Tender deadline reminders	Helps prevent missed deadlines
Should Have	Centralised dashboard	Provides an overview of company activities
Should Have	Tender cost tracking	Helps monitor printing and preparation costs
Could Have	Advanced reports	Provides additional management information
Could Have	Automated tender-source integration	Could reduce manual tender searching
Could Have	Document analytics	Could provide additional compliance insights
Won't Have — Initial Version	Automatic tender submission	External portal integration is outside the initial scope
Won't Have — Initial Version	Guaranteed qualification	The system cannot guarantee tender eligibility
Won't Have — Initial Version	Guaranteed tender success	Tender outcomes depend on external organisations
________________________________________
16. Requirements Traceability
The requirements are derived from the stakeholder problems identified through the interview questions.
Stakeholder Need	Related Requirement
Track document validity periods	FR5
Know which documents need renewal	FR5, FR6, FR7
Manage many compliance documents	FR3, FR4
Identify tender opportunities	FR8
Know which tenders the company qualifies for	FR9, FR10
Track tenders to pursue	FR11
Track submitted tenders	FR12
Follow up on submitted tenders	FR14
Know whether the company was appointed	FR15
Reduce missed tender outcomes	FR14, FR15, FR16
Reduce administrative work	FR17
Reduce unnecessary printing and preparation costs	FR3, FR17
Protect company information	FR18, NFR1
________________________________________
17. Supporting Evidence
Appendix A — Stakeholder Interview
Stakeholder Name: [Anele Tyeni]
Position/Role: [Director]
Date of Interview: [24-08-2026]
Interview Method: [Face-to-face ]
________________________________________
Appendix B — Stakeholder Confirmation
Stakeholder Name: [Anele Tyeni]
Confirmation Date: [24-08-2026]
Confirmation Method: [Verbal agreement]
The stakeholder should confirm that the documented problem, current process and identified needs accurately represent the company's situation.
Stakeholder Confirmation:
[Signature provided on meeting minutes]
________________________________________
Conclusion
The proposed Entrepreneurial Compliance and Tender Management System addresses the identified need for a centralised way to manage company compliance documents, certificates and tender opportunities.
The system will allow users to monitor document validity, manage certificate expiry dates, record tender opportunities, assess tender qualification, track submitted tenders, follow up on applications and record tender outcomes.
The proposed solution will use a Flutter mobile application and an ASP.NET web application connected to a shared Supabase/PostgreSQL backend. This architecture will provide a centralised platform while allowing users to access relevant information through mobile and web interfaces.
The initial SRS establishes the project's problem, purpose, scope, stakeholders, current process, product perspective, functions, requirements, system architecture, integration requirements and priorities.
The stakeholder interview responses, stakeholder confirmation and project-management evidence must be added as they become available. The original SRS also identifies stakeholder interview evidence and project-specific information as areas requiring actual stakeholder input.



DE Radile 219008327

6. Stakeholders and User Groups
6.1 Company Owners / Entrepreneurs
Company owners and entrepreneurs are the primary stakeholders. They require visibility of company compliance status and tender opportunities and may use the system to manage the entire tender process.
6.2 Administrative Staff
Administrative staff may manage company documentation, certificate information, expiry dates and tender records.
6.3 Tender / Procurement Staff
Tender or procurement staff may search for tender opportunities, review tender requirements, determine qualification, prepare submissions and track tender outcomes.
6.4 Company Management
Management may use the system to monitor compliance, tender opportunities, submitted applications and outstanding follow-ups.
6.5 System Administrator
The system administrator will be responsible for technical administration, authorised access and maintenance of the application.
________________________________________
7. Stakeholder Interview Evidence
The stakeholder interview focuses on understanding how the company currently manages compliance documents, certificates and tender opportunities.
7.1 Stakeholder Interview Questions
Company Compliance and Document Management
Question 1:
How does your company currently monitor and manage the validity periods of its compliance documents and certificates?
Question 2:
Approximately how many documents and certificates does your company typically need to maintain and submit when applying for business opportunities or tenders?
Question 3:
What process does your company currently use to monitor compliance requirements and ensure that all required certificates and documents remain valid and up to date?
Question 4:
How does your company identify which certificates or compliance documents need to be renewed before or after their expiry dates?
Tender Identification and Management
Question 5:
How does your company currently identify and receive information about new tender opportunities?
Question 6:
How do you currently keep track of tenders that your company has already submitted, as well as tender opportunities that you are considering applying for?
Question 7:
Does your company review all available tender opportunities on a weekly basis? If so, how do you determine which tenders to pursue, and how do you keep track of the opportunities that you decide to pursue or not pursue?
Question 8:
How does your company determine which tenders it qualifies for, and what criteria or requirements do you use to assess whether you are eligible to apply?
Question 9:
What challenges does your company currently experience when managing compliance documents, certificate expiry dates, tender qualifications and tender opportunities?
Question 10:
Approximately how much does your company spend on printing and preparing documents for tender applications, and what financial losses or costs do you experience when tenders are not followed up to determine whether your company has been appointed or unsuccessful?
7.2 Stakeholder Responses
Question	Stakeholder Response
Question 1	[I keep my validity period on a per case basis. Although the general quotation validity in our sector is 30 days, some clients request 60 to 90 days. I don’t have a fixed mechanism where I record validity for open and closed RFQ/Tender Bid requests.]

Question 2	[⁠The question is a little vague, but if your question is referring to the number of quotations I submit daily/weekly/monthly/annually, it varies according to budget availability and allocation from DOH. It also depends on the rate at which end-users from the specific DOH institutions request SCM practitioners to source their tools of trade for them. With those variables constantly at play, the amount of documents I submit vary between 3-8 quotations/bids per week. If you meant documents per invitation, then it’s 23 standard bidding documents for RFQ plus 5 supporting company documents. 94-115 documents in a standard tender bid.]
Question 3	[I don’t have set mechanisms to assist in checking my company compliance. I check manually every Monday morning and refresh my profiles on the respective government compliance systems. By doing that, I’m always aware of the expiry dates on my CIPC annual returns, SARS annual returns, Beneficial Ownership Declarations on CIPC and annual SAHPRA wholesale medical devices,  surgical consumables and equipment licence fees, then renew accordingly. I don’t have an automated system that helps me track them.]
Question 4	[⁠I search manually on Monday’s when I reconcile my administrative accounts and profiles. I also get direct invitations via email from various hospitals and health district offices. I also note them down from various websites and sort them according to what closes first to last. I have them in digital folders to be able to pull them when I need to reference them or cross check according to the purchase orders received.]
Question 5	[I only tender for adverts that match my commodities on CSD and for only those that are part of my stock items.]
Question 6	[The biggest challenge we face in the company is that the analog way of identifying, submitting and manually following up is very time consuming and sometimes certain quotes slip through the cracks. Tracking expiration dates of the mandatory accreditations of trade the way we currently do, is also a tedious exercise that can be automated and streamlined for convenience.]
Question 7	[No, my company only reviews the tender opportunities that falls within it’s scope of deliverables. This can be determined by the commodities that the entity is registered for on CSD and the scope which the SAHPRA licence allows. The way I track what we decide to pursue, is by saving submitted opportunities in digital files to be able to revisit when the need arises. We don’t track what we decide not to pursue or don’t qualify to pursue.]
Question 8	[The RFQ/Tender description and specifications of the items requested, is certified indication of whether we qualify or not. It helps discern whether the items requested are part of our stock items or can be sourced via a third party at our behest for our client. The basically how how we assess eligibility.]
Question 9	[⁠The biggest challenges are that our system is outdated and analog in a digital society. It’s time consuming and not error proof like we would like such administrative practices should be. Streamlining all these functions would be ideal for optimal operation.]
Question 10	[We approximately spend R1000 - R2000 on printing and preparing documents for tenders on a month to month basis. We don’t experience financial losses for not following up whether our bid was successful or not. The DOH has mechanisms in place to follow up on whether are successful or not, after a certain amount of time has passed and it can be done remotely if you can’t physically go to these institutions. Where we experience loss is by virtue of being unsuccessful on all the ones we submitted for. If we even just get awarded one out of 10 submissions, 10% out of 100% strike rate ratio still balances out because of how relatively low the printing costs are compared to profit made per purchase order. So it’s a necessary trade-off that comes with the business demands.]
Important: The stakeholder responses must be replaced with the actual responses obtained during the interview. They should not be invented.

