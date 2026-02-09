# Task-1-Doctor-appointment-scheduling-ER-diagram
# Appointment Booking System

A backend system for managing doctor appointments, availability, scheduling types, and patient bookings.

## Project Overview

The Appointment Booking System is designed to:

- Manage user authentication (Sign-up / Sign-in)
- Allow doctors to define availability
- Enable patients to book appointments
- Support family bookings (multiple patients per appointment)
- Handle cancellations and rescheduling
- Manage doctor leaves
- Support different scheduling types (Wave & Stream)
  
### ER Diagram:

The database design includes the following main entities:

- Users
- Doctors
- Patients
- Availability
- Appointments
- Appointment Patients (Family booking)
- Doctor Leaves
- Schedule Types

### Relationship Summary:

- One User → One Doctor or Patient
- One Doctor → Many Availabilities
- One Doctor → Many Appointments
- One Appointment → Multiple Patients
- One Schedule Type → Many Appointments

## Tools Used:
### dbdiagram.io – ER diagram design



