# Group-G-
Educational ITC ASSESSMENT
LP Moloi 222093279,
TW Kayane 219015324,
KI Kalo  220046482,
DE Radile 219008327,
MV Tshabalala 22204434

[ITC Group Assessment Group D.pdf](https://github.com/user-attachments/files/31422580/ITC.Group.Assessment.Group.D.pdf)

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

•	Appropriate authentication credentials.
Developers will require suitable development environments for Flutter/Dart and ASP.NET.
