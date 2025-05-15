# 🏥 Hospital Management System

A simple console-based **Hospital Management System** built using **Java** and **MySQL**. This application allows you to manage patient and doctor data and book appointments. It demonstrates the use of JDBC for database operations and follows a modular code structure for better maintainability.

---

## 🚀 Features

- **Add Patient**  
  Add new patients by providing their name, age, and gender.

- **View Patients**  
  View the list of all patients with their ID, name, age, and gender.

- **View Doctors**  
  View the list of available doctors with their ID, name, and specialization.

- **Book Appointment**  
  Schedule appointments by selecting valid patient and doctor IDs along with the desired appointment date.

- **Doctor Availability Check**  
  Automatically checks if the doctor is already booked on a selected date before scheduling a new appointment.

---

## 🧱 Technologies Used

- Java
- MySQL
- JDBC
- IntelliJ / Eclipse (IDE)
- MySQL Workbench (for DB operations)

---


### 📦 Prerequisites

- Java JDK (17 or compatible)
- MySQL Server
- MySQL Connector/J (JDBC driver)
- IDE (like IntelliJ IDEA or Eclipse)

---

### 🧪 Running the Application

  Clone or download the repository.
  Make sure your MySQL credentials are correctly set in:
  
  private static final String url = "jdbc:mysql://localhost:3306/DB_name";
  
  private static final String username = "username";
  
  private static final String password = "password";

3. Compile and run the main class:
     javac HospitalManagementSystem/HospitalManagementSystem.java
     java HospitalManagementSystem.HospitalManagementSystem

### 🖥️ Usage

      When the application runs, you’ll see a menu-driven interface offering options such as:

        - Reserve a room
        
        - View reservations
        
        - Edit reservation
        
        - Delete reservation
        
        - Exit

---
### 🤝 Contributing
  If you find bugs or have ideas for improvements or new features:

  Fork the repository
  
  Create a new branch
  
  Submit a pull request
  
  Issues and discussions are also encouraged!



### 🙏 Acknowledgments
  Special thanks to all contributors and users who support the development of the Hotel Reservation System.
  Your feedback makes this project better!
    



