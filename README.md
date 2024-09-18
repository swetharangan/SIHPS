# Smart India Hackathon Workshop
# Date: 23 - 09 - 2024
## Register Number: 212223040221
## Name: swetha.R
## Problem Title
Development of e-Portal for facilitating Case Management Hearing of various types of cases
## Problem Description
Case Management Hearing, known as a Pre-Trial Conference" in other jurisdictions". This application is used for managing case files since filing to disposal and to complete all its related processes. The CMS keeps the records of all the cases filed in Delhi High Court. The system has following features: Filing of Case, Caveat matching, Allocation of case, Daily Case Proceedings, Notice Generation, Case Transfer, Case Status Search, Report, etc.
## Problem Creater's Organization
Ministry of Law and Justice

## Idea
The e-Portal aims to streamline the management of case files from filing to disposal, covering all related processes. It is specifically tailored for the Delhi High Court but can be adapted for other jurisdictions. The system will feature functionalities such as filing cases, matching caveats, case allocation, daily case proceedings, notice generation, case transfers, case status searches, and report generation.

## Proposed Solution / Architecture Diagram
![image](https://github.com/user-attachments/assets/2094de80-9ee7-4ade-865f-09479e106fe7)

Case Filing Module: Allow users (lawyers, court staff) to file cases online with necessary documentation.
Caveat Matching Module: Automatically check and match caveats to cases being filed.
Case Allocation: Assign cases to judges based on predefined rules or manual allocation by court administration.
Daily Case Proceedings: Manage daily case activities, updates, and proceedings logs.
Notice Generation: Generate and dispatch notices related to case hearings, judgments, and other court orders.
Case Transfer: Facilitate the transfer of cases between different courts or judges.
Case Status Search: Provide an easy-to-use interface for users to search the status of cases.
Reports: Generate reports for various stakeholders like lawyers, judges, and court administration for insights and record-keeping.



## Use Cases
Filing a New Case: A lawyer files a new case through the portal, uploading required documents.
Checking Case Status: Users can search for their case status by entering the case number or party names.
Daily Updates: Judges and court staff update the case status and proceedings at the end of each hearing.
Notice Generation and Dispatch: Upon certain events (like hearing dates or judgments), the system automatically generates notices.
Case Transfer Requests: Cases can be requested for transfer to another judge or court, processed through administrative approval.
Report Generation: Court administrators generate periodic reports for analysis of case flow and backlog.

## Technology Stack
Frontend: React, Redux, Material-UI
Backend: Spring Boot, Spring Security, RESTful APIs
Database: PostgreSQL
Authentication: OAuth 2.0, JWT
Cloud Hosting: AWS / Azure
CI/CD: Jenkins / GitHub Actions
Version Control: Git, GitHub
Testing: JUnit, Selenium for automated testing


## Dependencies
React Libraries: React Router, Axios, Formik
Spring Boot Modules: Spring Data JPA, Spring Security, Spring Cloud for microservices
Database: PostgreSQL JDBC Driver
Authentication: Spring Security OAuth2 Client
Cloud SDKs: AWS SDK / Azure SDK
Others: Docker for containerization, Kubernetes for orchestration if scaling is required

