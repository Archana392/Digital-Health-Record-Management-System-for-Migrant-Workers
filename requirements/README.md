# Database Requirement Analysis

## Overview

The Digital Health Record Management System for Migrant Workers requires a centralized database to manage migrant worker health records, healthcare providers, appointments, prescriptions, departments, notifications, and administrative activities. The database is designed to ensure data security, consistency, and efficient access to healthcare information across different locations.

## Database Requirements

### Functional Requirements

- Store migrant worker personal and health information.
- Store healthcare provider details and specialization information.
- Manage appointment scheduling and tracking.
- Maintain digital health records and prescriptions.
- Manage healthcare departments.
- Support user authentication and authorization.
- Generate healthcare reports and analytics.
- Send health alerts and appointment notifications.

### Non-Functional Requirements

- Data Security
- Scalability
- Data Integrity
- High Availability
- Performance Optimization

---

# Table List

| S.No | Table Name | Description |
|-------|------------|-------------|
| 1 | Users | Stores login credentials and user roles |
| 2 | Migrant_Workers | Stores migrant worker personal and health information |
| 3 | Healthcare_Providers | Stores healthcare provider details and specialization information |
| 4 | Admins | Stores administrator information |
| 5 | Healthcare_Staff | Stores healthcare staff information |
| 6 | Departments | Stores healthcare department details |
| 7 | Appointments | Stores appointment booking information |
| 8 | Health_Records | Stores diagnosis and treatment history |
| 9 | Prescriptions | Stores medicines prescribed by healthcare providers |
| 10 | Notifications | Stores health alerts and appointment reminders |

---

# Entity Relationships

## Migrant Worker

- Can book multiple appointments.
- Can have multiple health records.
- Can receive multiple prescriptions.
- Can receive multiple notifications.

## Healthcare Provider

- Can manage multiple appointments.
- Can create multiple prescriptions.
- Can maintain multiple health records.
- Belongs to a department.

## Appointment

- Links a migrant worker and a healthcare provider.
- Stores appointment date and status.

## Prescription

- Created by a healthcare provider.
- Assigned to a migrant worker.

## Health Record

- Maintained for a migrant worker.
- Updated by a healthcare provider.

## Department

- Contains multiple healthcare providers.
- Managed by the administration.

---

# Outcome

- Database requirements identified and documented.
- 10 core tables finalized for implementation.
- Relationships between entities defined clearly.
- Schema prepared for ER diagram and database creation.
- Foundation established for secure health record management.
