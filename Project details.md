# Project Title

Hospital Appointment Booking System

# Problem Statement

Many hospitals and clinics still manage patient appointments manually using registers or phone calls. This can lead to scheduling errors, long waiting times, appointment conflicts, and difficulty in maintaining patient records. A Hospital Appointment Booking System helps automate appointment scheduling, improve efficiency, and provide better healthcare services.

# Project Objectives

- Maintain patient appointment records efficiently.
- Allow patients to book appointments online.
- Manage doctor schedules and availability.
- Reduce waiting time and appointment conflicts.
- Generate appointment and patient reports.
- Improve hospital management and patient satisfaction.

# Technologies Used

## Front End

- HTML
- CSS
- JavaScript

## Back End

- Python (Flask/Django)

## Database

- MySQL

# Modules

- User Management
- Patient Management
- Doctor Management
- Appointment Booking
- Schedule Management
- Notification Management
- Report Generation

# Database Tables

## User

| Field Name | Data Type |
|------------|-----------|
| user_id | INT |
| username | VARCHAR |
| password | VARCHAR |
| role | VARCHAR |

## Patient

| Field Name | Data Type |
|------------|-----------|
| patient_id | INT |
| patient_name | VARCHAR |
| age | INT |
| gender | VARCHAR |
| contact_number | VARCHAR |

## Doctor

| Field Name | Data Type |
|------------|-----------|
| doctor_id | INT |
| doctor_name | VARCHAR |
| specialization | VARCHAR |
| contact_number | VARCHAR |

## Appointment

| Field Name | Data Type |
|------------|-----------|
| appointment_id | INT |
| patient_id | INT |
| doctor_id | INT |
| appointment_date | DATE |
| appointment_time | TIME |
| status | VARCHAR |

# Expected Outcome

The system will provide an easy and efficient way for patients to book appointments, manage doctor schedules, reduce waiting time, and maintain accurate appointment records. It helps improve hospital operations and patient care.

# Conclusion

The Hospital Appointment Booking System improves appointment management, reduces manual work, and enhances communication between patients and doctors. It provides a reliable solution for efficient healthcare service management.
