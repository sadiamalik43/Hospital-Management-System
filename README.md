# Hospital-Management-System
Hospital Management System (Java OOP)
This is a comprehensive Hospital Management System developed using Java and Object-Oriented Programming (OOP) principles. The system provides functionalities for managing patient registrations, appointments, patient records, staff, and user authentication.
Features
The system includes the following key features:
User Authentication: Secure login system with distinct roles for Admin and Non-Admin users. Includes functionality for setting and changing passwords.
Patient Registration: 
Register new patients with unique Patient IDs.
Record essential patient details such as name, CNIC, parent/guardian information, contact, age, and gender.
Automatic creation of dedicated files for patient records and appointments upon registration.
Patient Management: 
Manage and update existing patient records.
Store detailed patient checkup data, including category, amount, age, gender, date, and time.
Appointment Management: 
Schedule and manage patient appointments.
Record appointment-specific data like category, amount, age, gender, date, and time.
Automatic date and time stamping for appointments.
Patient Search: Search and retrieve patient records based on Patient ID, covering both general and appointment-related information.
Staff Management: 
Add Staff: Register new staff members with unique Staff IDs. Store details including name, CNIC, contact, category, address, age, gender, date, time, and shift.
Delete Staff: Remove staff records from the system using their Staff ID.
Data Management: The system creates and manages a structured DataFiles directory to store patient IDs, staff IDs, passwords, appointments, patient records, registered patients, and staff data.
Initial Setup: A Setup utility is available to initialize the necessary data directories and files, and can also be used to clear previous records.
Technologies Used
Java: The core programming language.
JavaFX: Used for building the graphical user interface (GUI) of the application.
Setup and Installation
To run this project, ensure you have a Java Development Kit (JDK) with JavaFX support installed.
Clone the repository (if applicable):
Bash
git clone <repository_url>
Navigate to the project directory:
Bash
cd HospitalManagementSystem
Run the Setup.java file: This will create the necessary data directories and files.
Compile: javac Setup.java
Run: java Setup
Follow the on-screen prompts.
Compile and Run MainPanel.java:
Compile: javac MainPanel.java
Run: java MainPanel
Alternatively, you can run the LogPanel.java first, which provides an administrative login to access the MainPanel.
Compile: javac LogPanel.java
Run: java LogPanel
Usage
Login: Start the application from LogPanel.java. You can log in as an Admin or Non-Admin user. If it's the first run, you might need to set a password for the Admin.
Main Panel: After successful login, the MainPanel will be displayed, providing access to various modules like Patient Registration, Patient Management, Appointment Management, Staff Management, and Patient Search.
Patient Registration: Register new patients and their details.
Appointment Management: Schedule and manage appointments for registered patients.
Patient Search: Search for patient records using their unique IDs.
Staff Management: Add or delete staff records.

