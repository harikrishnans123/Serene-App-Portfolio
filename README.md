# Serene-App-Portfolio
Technical analysis portfolio for "Serene," a digital wellbeing startup. Includes Entity Relationship Diagrams (ERD), REST API Specifications (OpenAPI), and SQL Data Analysis for KPI tracking.

[Click here to view the Data Model PDF](Serene_Data_Model.pdf)

Serene: Digital Wellbeing Application
Focus:Data Modeling, API Design, Business Intelligence (SQL)  

Executive Summary

Serene is a "Slow Social" mobile application designed to reduce screen time anxiety through finite, curated daily content. Unlike traditional infinite-scroll platforms, Serene delivers a fixed set of 3-6 multimedia moments per day, encouraging mindful consumption over dopamine addiction.

This repository serves as a Technical Analysis Portfolio, documenting the backend logic, data architecture, and integration standards required to build the platform at scal

Technical Artifacts

1. Data Architecture (ERD)
Designed a normalized relational database schema to ensure data integrity across User Subscriptions, Content Delivery, and Journaling modules.
Key Challenge: Mapping a flexible "Freemium" model where content visibility changes dynamically based on subscription status.
Solution: Implemented a 1:1 relationship for Subscriptions and a 1:N relationship for Journal Entries with proper Foreign Key constraints.

2. API Specifications (OpenAPI/Swagger)
Authored a "Contract-First" API specification to reduce ambiguity between frontend and backend development teams.
Logic: Defined precise JSON response payloads for "Locked" vs. "Unlocked" content states.

3. Business Intelligence & SQL Analysis
Wrote SQL queries to measure product success and guide feature prioritization.
KPIs Tracked:Premium Conversion Rate, User Churn Risk, Regional Engagement.

