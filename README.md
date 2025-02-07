# Student Registration - Java with JavaBeans

## Description
This is a simple student registration project developed in Java using JavaBeans. The system allows managing basic student information, such as name, age, and enrolled course.

## Technologies Used
- **Java SE** (Java Standard Edition)
- **JavaBeans** for data encapsulation
- **JDBC** for database connection (if applicable)
- **Swing** or **JavaFX** (if there is a graphical interface)
- **MySQL** or **PostgreSQL** (optional, if data persistence is required)

## Features
- Register new students
- List registered students
- Update student information
- Remove students from the system

## Setup and Execution
1. **Clone the repository**
   ```sh
   git clone https://github.com/your-username/student-registration.git
   cd student-registration
   ```
2. **Import the project into your IDE** (Eclipse, IntelliJ, NetBeans)
3. **Configure the database** (if applicable)
   - Create a database
   - Import the SQL script available in the `database/` folder
   - Update settings in the `database.properties` file
4. **Compile and run**
   ```sh
   javac -d bin src/**/*.java
   java -cp bin Main
   ```

