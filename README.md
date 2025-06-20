# Hospital-Management-System
🏥 Hospital Management System (Java OOP)
A comprehensive Hospital Management System built using Java and Object-Oriented Programming (OOP) principles. The application provides modules to handle patient registration, appointments, records, staff management, and user authentication through a clean GUI interface using JavaFX.

📌 Features
🔐 User Authentication
Secure login system with role-based access (Admin and Non-Admin).

Supports password setting and modification.

🧾 Patient Registration
Register patients with unique Patient IDs.

Capture essential details: Name, CNIC, parent/guardian info, contact, age, and gender.

Automatically creates files for patient records and appointments.

🗃️ Patient Management
Update and manage patient records.

Store detailed checkup data: category, amount, age, gender, date, and time.

📅 Appointment Management
Schedule and manage appointments for patients.

Includes automatic date and time stamping.

🔍 Patient Search
Search patient information using Patient ID.

View both general records and appointment history.

👩‍⚕️ Staff Management
Add Staff: Register new staff with unique Staff IDs and complete profile.

Delete Staff: Remove staff using Staff ID.

📁 Data Management
Organized DataFiles/ directory for:

Patient & Staff data

Appointments & Records

User authentication (passwords)

Setup utility to initialize or reset system data.

💻 Technologies Used
Java – Core application logic

JavaFX – Graphical User Interface (GUI)

File I/O – For persistent local storage

⚙️ Setup and Installation
Ensure you have JDK (Java Development Kit) installed with JavaFX support.

Step-by-step Guide
Clone the Repository

bash
Copy
Edit
git clone <repository_url>
cd HospitalManagementSystem
Initialize the System (Run Setup)

bash
Copy
Edit
javac Setup.java
java Setup
Run the Application

Option 1: Direct Access via Main Panel

bash
Copy
Edit
javac MainPanel.java
java MainPanel
Option 2: Admin Login First (Recommended)

bash
Copy
Edit
javac LogPanel.java
java LogPanel
🚀 Usage
Login: Use the LogPanel to log in as Admin or Non-Admin.

Main Dashboard: Navigate to patient registration, appointment management, staff management, and more.

Register Patients: Input and store personal and medical info.

Schedule Appointments: Assign date, time, and medical category.

Search Records: Retrieve data by entering Patient ID.

Manage Staff: Add or remove staff with complete details.

📁 Directory Structure
bash
Copy
Edit
HospitalManagementSystem/
│
├── Setup.java               # Initializes file structure
├── LogPanel.java            # Login interface
├── MainPanel.java           # Main dashboard post-login
├── DataFiles/               # Directory for all saved data
│   ├── PatientIDs.txt
│   ├── StaffIDs.txt
│   ├── Appointments/
│   └── Records/
└── ...
📝 License
This project is intended for educational purposes. License terms can be added here if applicable.
