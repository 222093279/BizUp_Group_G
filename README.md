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
•	Appropriate authentication credentials.
Developers will require suitable development environments for Flutter/Dart and ASP.NET.
