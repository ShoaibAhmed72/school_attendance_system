# 🏫 School Attendance System

A simple and user-friendly Java-based School Attendance System built using **Swing GUI** for the frontend and **MySQL** for the backend database. This project helps schools manage student records, attendance tracking, and reporting efficiently.

## 🚀 Features

- Login Authentication
- Add / Edit / Delete Student Records
- Manage Class Schedules
- Mark Daily Attendance
- Generate Attendance Reports

## 🛠️ Built With

- Java (JDK 8 or above)
- Swing (GUI)
- MySQL Database
- VS Code with Java Extensions
- External JARs (e.g., MySQL JDBC Driver)

## 📦 Requirements

- Java JDK (8 or above)
- MySQL Server
- VS Code or any Java IDE
- MySQL JDBC Connector (JAR file)

## ⚙️ Setup Instructions

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/school-attendance-system.git
   cd school-attendance-system
   ```

2. **Import MySQL Database**
   - Open MySQL or phpMyAdmin
   - Create a new database (e.g., `attendance_system`)
   - Import the provided `.sql` file from the project folder

3. **Configure Database Connection**
   - In the Java code (usually in `DBConnection.java`), update the following:
     ```java
     String url = "jdbc:mysql://localhost:3306/attendance_system";
     String user = "root";
     String password = "your_mysql_password";
     ```

4. **Add MySQL Connector JAR**
   - Download the MySQL JDBC driver if not already present.
   - Add the JAR file to your VS Code project:
     - Right-click the project > Configure Build Path > Add External JARs.

5. **Run the Project**
   - Open the main file (e.g., `Main.java` or `Login.java`)
   - Run the file using your IDE or terminal

## 🔐 Default Login Credentials (Optional)

```txt
Username: admin
Password: admin123
```

*(Change credentials in the database as needed.)*

## 📄 License

This project is open-source and free to use.

---

## 🙌 Contributing

Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
