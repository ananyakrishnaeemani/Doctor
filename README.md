e-Doctor Appointment System
Project Overview
The e-Doctor Appointment System is a user-friendly web application designed to simplify the process of booking and managing appointments with healthcare professionals. The system allows patients to search for doctors based on their name, location, and specialization, check their availability, and book appointments efficiently. It also includes features for doctors to manage their schedules and for administrators to oversee the platform.

Features
Patient Features:

Search for doctors by name, location, or specialization.
View detailed doctor profiles, including descriptions and availability.
Book, update, and cancel appointments.
Receive email notifications for appointment updates.
Doctor Features:

Manage appointment schedules.
View patient details and appointment information.
Admin Features:

Manage users (patients and doctors).
Monitor appointment activities.
Role-Based Authentication and Authorization:

Secure access to features based on user roles (Admin, Doctor, Patient).
Technology Stack
Frontend:
Framework: Angular
Styling: CSS
Features: Dynamic filtering, responsive UI, query parameter data passing.
Backend:
Framework: Spring Boot
Database: MySQL
Features: Secure API integration, email notifications for appointment updates.
Installation and Setup
Prerequisites:
Node.js
Angular CLI
Java Development Kit (JDK)
MySQL Server
Steps to Set Up:
Clone the repository:
git clone https://github.com/your-repo/e-doctor-appointment-system.git
cd e-doctor-appointment-system
Set up the Frontend:
cd frontend
npm install
in case of issue with angular version:
set NODE_OPTIONS=--openssl-legacy-provider 
$env:NODE_OPTIONS="--openssl-legacy-provider"
ng serve
Access the application at http://localhost:4200.

Set up the Backend:

Import the Spring Boot project into your IDE (e.g., IntelliJ, Eclipse).
Configure the application.properties file with your MySQL database credentials.
Run the backend server.
Initialize the Database:

Use the provided SQL scripts to set up the required tables and initial data.
Usage
Sign Up:

Choose a role (Patient, Doctor, Admin) during registration.
Log in to access your personalized dashboard.
Search and Filter:

Use the search bar with filters to find doctors based on criteria.
Book Appointments:

View doctor availability and book an appointment.
Receive email confirmation for all appointment-related actions.
Manage Appointments:

Patients can update or cancel their appointments.
Doctors can manage their schedules.
Future Enhancements
Integration of video consultation features.
AI-powered suggestions for doctors based on patient history.
Advanced analytics for administrators.
Contributions
Contributions are welcome! Please fork the repository and create a pull request with your proposed changes. Ensure all changes are well-documented and tested.

License
This project is licensed under the MIT License.
