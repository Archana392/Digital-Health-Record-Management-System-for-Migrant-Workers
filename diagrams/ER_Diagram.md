+------------------+
|     PATIENTS     |
+------------------+
| patient_id (PK)  |
| worker_id        |
| first_name       |
| last_name        |
| contact_number   |
| email            |
| blood_type       |
| aadhaar_number   |
| home_state       |
| current_state    |
| occupation       |
+------------------+
          |
          | 1
          |
          | M
+------------------+
|   APPOINTMENTS   |
+------------------+
| appointment_id   |
| patient_id (FK)  |
| doctor_id (FK)   |
| appointment_date |
+------------------+
          |
          | M
          |
          | 1
+------------------+
|     DOCTORS      |
+------------------+
| doctor_id (PK)   |
| doctor_name      |
| specialization   |
| contact_number   |
+------------------+

          |
          | 1
          |
          | M
+------------------+
|  DOCTOR_NOTES    |
+------------------+
| note_id (PK)     |
| patient_id (FK)  |
| doctor_id (FK)   |
| diagnosis        |
| prescription     |
+------------------+
