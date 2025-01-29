# Outpatient Doctor Appointment System
## Project Overview
The e-Doctor Appointment System is a user-friendly web application designed to simplify the process of booking and managing appointments with healthcare professionals. The system allows patients to search for doctors based on their name, location, and specialization, check their availability, book appointments efficiently and can receive notification. It also includes features for doctors to manage their schedules and for administrators to oversee the platform.
## Features
### •	Patient Features:
  -	View detailed doctor profiles, including descriptions and availability.
  -	Book, update, and appointments.
  -	Receive email notifications for appointment updates.
### •	Doctor Features:
  -	Manage appointment schedules.
  -	View appointment information.
### •	Admin Features:
  -	Manage users (patients and doctors).
  -	Monitor appointment activities.
### •	Role-Based Authentication and Authorization:
  -	Secure access to features based on user roles (Admin, Doctor, Patient).
## Technology Stack
### Frontend:
  -	Framework: Angular
  -	Styling: CSS
### Backend:
  -	Framework: Spring Boot
  -	Database: MySQL
  -	Features: Secure API integration, email notifications for appointment updates.
## Installation and Setup
### Prerequisites:
  -	Node.js
  -	Angular CLI
  -	Java Development Kit (JDK)
  -	MySQL Server
### Steps to Set Up:
  1.	Clone the repository:
  -	git clone https://github.com/ananyakrishnaeemani/Doctor.git
  2.	Set up the Frontend:
        -	cd frontend
   	    - npm install -g @angular/cli.
        -	npm install
        -	in case of issue with angular version: 
        -	set NODE_OPTIONS=--openssl-legacy-provider 
        -	$env:NODE_OPTIONS="--openssl-legacy-provider"
        -	ng serve
  Access the application at http://localhost:4200.
  3.	Set up the Backend:
    -	Import the Spring Boot project into your IDE (e.g., IntelliJ, Eclipse).
    -	Configure the application.properties file with your MySQL database credentials.
    -	Run the backend server.
  4.	Initialize the Database:
    -	Use the required SQL scripts to set up the required tables and initial data.
## Usage
 ### 1.	Sign Up:
  -	Choose a role (Patient, Doctor) during registration.
  -	Log in to access your personalized dashboard.
 ### 2.	Book Appointments:
  -	View doctor availability and book an appointment.
  -	Receive email confirmation for all appointment-related actions.
## License
  This project is licensed under the MIT License.

