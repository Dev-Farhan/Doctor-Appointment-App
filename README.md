# Doctor Appointment System

## Overview

This project is a **Doctor Appointment System** built using the **MERN Stack** (MongoDB, Express.js, React.js, Node.js). The system is designed to handle user registration, authentication, appointment booking, management, and viewing for both patients and doctors.

## Project Description

The **Doctor Appointment System** allows:

### For **Patients**:
- **Registration & Login**: Create an account and log in.
- **Book Appointment**: Search for doctors based on specialties and book appointments.
- **View Appointments**: View all the appointments they have booked.
- **Cancel Appointment**: Patients can cancel any upcoming appointment they have booked.

### For **Doctors**:
- **Registration & Login**: Create an account and log in to the system.
- **View Patients**: Doctors can view a list of all the patients who have booked an appointment with them.
- **View Appointments**: Doctors can see all their upcoming and past appointments.

## Features

- **User Authentication**: JWT-based authentication for both patients and doctors.
- **Doctor Search**: Patients can search for doctors based on specialties.
- **Appointment Management**:
  - Patients can book, view, and cancel appointments.
  - Doctors can view all their appointments and patient details.
- **Admin Dashboard**: (optional for future) Admin users can manage doctors, patients, and appointments.

## Technologies Used

- **Frontend**: React.js, React Router, Tailwind CSS
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Authentication**: JWT (JSON Web Tokens)
- **State Management**: React Context API or Redux
- **API**: RESTful API
- **Deployment**: (optional) Heroku for backend, Vercel for frontend

## Installation

### Prerequisites
- Node.js
- MongoDB (locally or using a cloud service like MongoDB Atlas)

### Clone the Repository
```bash
git clone https://github.com/Dev-Farhan/doctor-appointment-app.git
