# Clinic/Hospital Management System

 This project is designed to efficiently store and manage patient data, as well as handle appointment bookings and cancellations. The system is built using Python and Tkinter, with MySQL as the database backend.The Clinic/Hospital Management System is designed to streamline administrative tasks, improve patient record-keeping, and enhance the overall appointment management process. It ensures that essential patient information and appointment details are readily accessible and efficiently managed.

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
![pic1](https://github.com/Priyanka-2468/Clinic_Management_Sysytem/assets/103355189/c38f45ce-2ed1-46c0-a9e9-92ab0e3cabfb)
![pic2](https://github.com/Priyanka-2468/Clinic_Management_Sysytem/assets/103355189/2a32910f-0cd9-47b2-a534-45745abcef91)
![pic3](https://github.com/Priyanka-2468/Clinic_Management_Sysytem/assets/103355189/8af70635-6639-476c-b248-7291cd3a2feb)
![pic4](https://github.com/Priyanka-2468/Clinic_Management_Sysytem/assets/103355189/e46035be-1d72-4f94-b29f-fa6f75c95c4e)
![pic5](https://github.com/Priyanka-2468/Clinic_Management_Sysytem/assets/103355189/c7330d1b-7d35-4c98-9761-7afa90ee6072)






---


