# Database Requirement Analysis

## Overview

The Smart Hospital Patient Management System requires a centralized database to manage patients, doctors, appointments, prescriptions, departments, and hospital administration activities. The database is designed to ensure data consistency, security, and efficient retrieval of healthcare information.

## Database Requirements

### Functional Requirements

- Store patient information and medical history.
- Store doctor details and specialization information.
- Manage appointment scheduling and tracking.
- Maintain prescription records.
- Manage hospital departments.
- Support user authentication and authorization.
- Generate reports for administrative purposes.
- Send notifications and appointment reminders.

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
| 2 | Patients | Stores patient personal and medical information |
| 3 | Doctors | Stores doctor information and specialization details |
| 4 | Admins | Stores administrator information |
| 5 | Nurses | Stores nurse/staff information |
| 6 | Departments | Stores hospital department details |
| 7 | Appointments | Stores appointment booking information |
| 8 | Medical_Records | Stores patient diagnosis and treatment history |
| 9 | Prescriptions | Stores medicines prescribed by doctors |
| 10 | Notifications | Stores appointment reminders and alerts |

---

# Entity Relationships

### Patient
- Can book multiple appointments.
- Can have multiple medical records.
- Can receive multiple prescriptions.

### Doctor
- Can attend multiple appointments.
- Can create multiple prescriptions.
- Belongs to a department.

### Appointment
- Links a patient and a doctor.
- Stores appointment date and status.

### Prescription
- Created by a doctor.
- Assigned to a patient.

### Department
- Contains multiple doctors.
- Managed by the administration.

---

# Deliverable

➜ Database Requirement Analysis Completed

➜ Table List Prepared

➜ Database Entities Identified

➜ Ready for ER Diagram Design
