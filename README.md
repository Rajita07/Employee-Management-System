# Employee Management System

## Description
The Employee Management System is a Java-based desktop application designed to help organizations manage employee data efficiently. It provides functionalities such as adding, updating, viewing, and removing employee information, along with a secure login system. The application integrates with a MySQL database for persistent data storage.

## Features
- **Add Employees**: Capture and store details of new employees.
- **Update Employee Information**: Edit existing employee records.
- **View Employee Details**: Display employee data in an organized format.
- **Remove Employees**: Delete employee records from the system.
- **User Authentication**: Secure login system for accessing the application.
- **Database Integration**: Stores and retrieves data using MySQL.

## Tech Stack
- **Programming Language**: Java
- **Database**: MySQL
- **IDE**: IntelliJ IDEA / Eclipse
- **Libraries**:
  - MySQL Connector
  - JCalendar
  - RS2XML (for displaying database tables)

## Prerequisites
1. **Java Development Kit (JDK)**: Ensure JDK 8 or later is installed.
2. **MySQL Server**: Install and configure MySQL Server.
3. **IDE**: Use IntelliJ IDEA or Eclipse for running the project.

## Installation and Setup

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/employee-management-system.git
cd employee-management-system
```

### 2. Import the Project
- Open the project in your preferred IDE (IntelliJ IDEA or Eclipse).
- Ensure the necessary libraries (e.g., MySQL Connector, JCalendar) are configured in the project.

### 3. Set Up the Database
- Create a MySQL database named `employee_management`.
- Use the provided SQL scripts (if any) to set up the necessary tables.

### 4. Configure the Database Connection
- Update the `conn.java` file with your MySQL credentials:
  ```java
  String url = "jdbc:mysql://localhost:3306/employee_management";
  String username = "root";
  String password = "RPRaundal$@03";
  ```

### 5. Run the Application
- Locate the `Main_class.java` file and run it to start the application.

## Usage
1. Launch the application.
2. Log in using your credentials.
3. Navigate through the options:
   - Add a new employee.
   - View existing employees.
   - Update employee details.
   - Remove an employee.
4. Log out when finished.

## Project Structure
```
project-root
|
|-- src
|   |-- employee.management.system
|       |-- AddEmployee.java
|       |-- conn.java
|       |-- Login.java
|       |-- Main_class.java
|       |-- RemoveEmployee.java
|       |-- Splash.java
|       |-- UpdateEmployee.java
|       |-- View_Employee.java
|
|-- out
|-- .idea
|-- .classpath
|-- .project
```

## Screenshots
- 1 Screenshot

## Future Enhancements
- Add role-based access control for admins and employees.
- Include search functionality to filter employee records.
- Integrate data export to CSV or Excel files.
- Improve the UI with modern JavaFX components.

## License
This project is licensed under the MIT License. See the LICENSE file for details.

## Contact
For any queries, feel free to reach out:
- **Name**: [Rajita]
- **Email**: [rajita.raundal.07@gmail.com]
- **GitHub**: [Rajita07]

