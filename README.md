# 🌍 TourEase Pro

A premium Java-based desktop application for managing luxury tours, bookings, and customer information. Designed to streamline operations for high-end travel agencies with elegance and efficiency.

---

## ✨ Features

- 🛫 Custom Luxury Tour Package Creation  
- 📅 Booking and Reservation System  
- 🗺️ Destination and Itinerary Management  
- 💼 Client Profiles and CRM Module  
- 📊 Invoice & Report Generation  
- 🔐 Admin Login with Authentication  
- 📧 Email Notification System (optional)

---

## 🏗️ Built With

- **Programming Language:** Java (JDK 8)  
- **Database:** MySQL  
- **UI:** Swing
- **Build Tool:** Apache NetBeans  
- **JDBC Driver:** MySQL Connector/J

---

## 🖥️ Screenshots



## 🚀 How to Run the Project

### 🔧 Prerequisites

- Java JDK 8 or higher  
- MySQL Server installed  
- MySQL Workbench (optional)  
- Java IDE (NetBeans)  

### 📦 Setup Instructions

1. **Clone the repository**
```bash
git clone https://github.com/your-username/luxury-tour-app.git
cd luxury-tour-app
Import the project into your IDE (NetBeans).

Create the MySQL database:

Run the SQL script in the database/ folder:

sql
Copy
Edit
CREATE DATABASE luxury_tours;
USE luxury_tours;

-- Add your tables and data here (booking, customers, packages, admin, etc.)
Update DB credentials in the Java code:

java
Copy
Edit
String url = "jdbc:mysql://localhost:3306/luxury_tours";
String user = "root";
String password = "your_password";
Build and run the project:

Compile and run the Main.java or equivalent entry point.

Login with admin credentials.

Start managing luxury tours!

