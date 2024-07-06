# Clinic/Hospital Management System

Welcome to the Clinic/Hospital Management System! This project is designed to efficiently store and manage patient data, as well as handle appointment bookings and cancellations. The system is built using Python and Tkinter, with MySQL as the database backend.

## How to Run the Project

1. **Run the `main.py` file.**
2. **Login Credentials:**
   - **Username:** abc
   - **Password:** pqr

## Database Setup

To set up the database for the system, follow these commands in the MySQL command line:

```sql
CREATE DATABASE PATIENTS_DB;

USE PATIENTS_DB;

CREATE TABLE patients (
    MOBILE varchar(200) NOT NULL,
    NAME varchar(200) NOT NULL,
    DOB varchar(200) NOT NULL,
    HISTORY varchar(200) NOT NULL,
    MEDICINES varchar(200) NOT NULL,
    PRIMARY KEY (MOBILE)
);
```

## Key Features

### Patient Database
- **Comprehensive Patient Records:**
  - Mobile number (primary key)
  - Name
  - Date of Birth
  - Medical History
  - Prescribed Medicines

### Patient Management
- **Add New Patients:**
  - Easily add new patients to the database with all necessary details.
- **View Patient Records:**
  - Select and view specific patient records as needed.
- **Search Patients:**
  - Search for patients based on their mobile number, name, or other criteria.
- **Delete Patient Records:**
  - Delete patient records if needed, such as upon request or when a patient is discharged.

### Appointment Management
- **Schedule Appointments:**
  - Patients can book appointments at their preferred date and time.
- **Cancel Appointments:**
  - Patients can cancel appointments in case of schedule changes or conflicts.
- **View Appointments:**
  - Search for upcoming or past appointments for any patient.

## Screenshots

To give you a better understanding of the system's interface and functionality, here are some screenshots:

https://private-user-images.githubusercontent.com/97177344/301062555-40392e22-41e4-4a3b-ad60-a8c40ab7e808.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjAzMDg3NTIsIm5iZiI6MTcyMDMwODQ1MiwicGF0aCI6Ii85NzE3NzM0NC8zMDEwNjI1NTUtNDAzOTJlMjItNDFlNC00YTNiLWFkNjAtYThjNDBhYjdlODA4LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MDYlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzA2VDIzMjczMlomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTVmNTA5MjkwNzM3NTk4MTllNTNkOTIyMjQyMmRkZmEyODc4MDdiZjU2NGExMTExYmVlMzFmMDQxZDc5MWI1ZWMmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.wA5AkUVd1ojYPxgZeTUSN9omqe4zmvJrezDcqJltQ60

https://private-user-images.githubusercontent.com/97177344/301062466-40d4eb4c-0805-476a-866e-272502284c99.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjAzMDg3NTIsIm5iZiI6MTcyMDMwODQ1MiwicGF0aCI6Ii85NzE3NzM0NC8zMDEwNjI0NjYtNDBkNGViNGMtMDgwNS00NzZhLTg2NmUtMjcyNTAyMjg0Yzk5LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MDYlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzA2VDIzMjczMlomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTQ5YzIxMTA5ZDEwOGRjNmUwMTc3YTI3ODNhMWViYmQxZjc3MTdmMWQwYWZlYzAxOGFmNzkwMGMxZTJhNzI0MTcmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.7B7DqDNPXxwUvHVNgsnQua1CcP7SJjeoKRh44vr_9Fk

https://private-user-images.githubusercontent.com/97177344/301062368-ce25963e-d482-44e5-8245-6b80ab87fc13.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjAzMDg3NTIsIm5iZiI6MTcyMDMwODQ1MiwicGF0aCI6Ii85NzE3NzM0NC8zMDEwNjIzNjgtY2UyNTk2M2UtZDQ4Mi00NGU1LTgyNDUtNmI4MGFiODdmYzEzLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MDYlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzA2VDIzMjczMlomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWVkNDJiMWM3MTM5MjA0M2UyMjZhZGNiZmIzYzUwNDEzYmY2NDEwMTRlYmJmMjc2ZjE5NWIzOTM2OTA0ODE5ZWUmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.Oddm5LJ25XATteM_O48xIB48CdCTKGyMpA68VR5CfPg

https://private-user-images.githubusercontent.com/97177344/301062366-6d39da94-d4b2-488b-bcea-7090b408e3be.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjAzMDg3NTIsIm5iZiI6MTcyMDMwODQ1MiwicGF0aCI6Ii85NzE3NzM0NC8zMDEwNjIzNjYtNmQzOWRhOTQtZDRiMi00ODhiLWJjZWEtNzA5MGI0MDhlM2JlLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MDYlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzA2VDIzMjczMlomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTE3MGIyZTAyYzY0OGQ5YWUzYWM4YmY4YjcwODEzMjZkNTEzM2I5N2YxYTFjMjg5ZDcwNGJiZWMxOTE0MWM0YzQmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.zjYRkS4sach3UiAQGJojFqpT5AXNdQ1vTdvwGfla1IU

https://private-user-images.githubusercontent.com/97177344/301062358-fe5d0d24-a69b-4b33-b887-156899d21bc9.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjAzMDg3NTIsIm5iZiI6MTcyMDMwODQ1MiwicGF0aCI6Ii85NzE3NzM0NC8zMDEwNjIzNTgtZmU1ZDBkMjQtYTY5Yi00YjMzLWI4ODctMTU2ODk5ZDIxYmM5LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDA3MDYlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQwNzA2VDIzMjczMlomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTAwZmY0YzUwZTA5MmJkZjQxNjkyYjkyNzE3MWEzMzk2ZmEzY2U5MTUzMmU2NjViYzRmMTIzMTA3OTA3ZDBlNTEmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0JmFjdG9yX2lkPTAma2V5X2lkPTAmcmVwb19pZD0wIn0.MmSnVf5liblpwBJKKXNBpPiFunFh6hvQhtao1hPxPvg

## Overview

The Clinic/Hospital Management System is designed to streamline administrative tasks, improve patient record-keeping, and enhance the overall appointment management process. It ensures that essential patient information and appointment details are readily accessible and efficiently managed.

If you have any questions or need assistance, feel free to ask!

---

This README file provides clear instructions on setting up and using the Clinic/Hospital Management System, highlights its key features and functionalities, and includes a section for screenshots to visually demonstrate the system's interface and operations.
