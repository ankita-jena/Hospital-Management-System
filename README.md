# 🏥 Hospital Management System

A console-based Java application to manage hospital operations efficiently using Java and MySQL.

### ✨ Features
- Add New Patient
- View All Patients
- View Doctors List
- Book Appointment (Patient-Doctor mapping)
- MySQL Database Integration

### 🛠️ Tech Stack
- **Language:** Java
- **Database:** MySQL
- **Connectivity:** JDBC
- **IDE:** IntelliJ IDEA

### 📂 Core Classes
- `HospitalManagementSystem.java` - Main menu & logic
- `Patient.java` - Patient operations
- `Doctor.java` - Doctor operations
- `Main.java` - Entry point

### 🚀 How to Run
1. Create DB: `CREATE DATABASE hospital;`
2. Create Tables: `patients`, `doctors`, `appointments`
3. Update DB username/password in `HospitalManagementSystem.java`
4. Add `mysql-connector-j-9.7.0.jar`
5. Run `HospitalManagementSystem.java`

### Future Scope
- GUI with Swing/JavaFX
- Billing Module
- Admin Panel
