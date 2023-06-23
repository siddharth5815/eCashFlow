# eCashFlow Simulator
eCashFlow Simulator is a Java-based desktop application that simulates an electronic cash flow system. It allows users to authenticate, manage accounts, perform transactions, and incorporates Object-Oriented Programming (OOP) principles for user interfaces. The application utilizes an SQL database to store user information and transaction records.

## Features
User Authentication: Users can create an account, log in, and manage their profile.
Account Management: Users can view their account details, including balance and transaction history.
Transaction Processing: Users can perform various types of transactions, such as deposit, withdrawal, and fund transfers.
OOPs Principles: The application follows OOPs principles for designing user interfaces, ensuring modularity and reusability of code.
SQL Database Integration: User data and transaction records are stored in an SQL database, ensuring data persistence and reliability.

### Technologies Used
Java: The core programming language used for developing the application.
JavaFX: A framework used for creating user interfaces in Java.
SQL Database: An SQL database (such as MySQL or PostgreSQL) is used to store user information and transaction records.
JDBC: Java Database Connectivity (JDBC) is used to establish a connection between the Java application and the SQL database.
Prerequisites
Java Development Kit (JDK) 8 or later installed on your system.
An SQL database management system (such as MySQL or PostgreSQL) installed and configured.

### Getting Started
Clone the repository:

bash
git clone https://github.com/siddharth5815/eCashFlow

### Set up the SQL database:

Create a new database for the application.
Import the SQL schema file provided in the repository to create the necessary tables.
Update the database configuration:

Open the src/main/resources/application.properties file.
Update the database connection details (URL, username, and password) to match your local configuration.
Build and run the application:

bash
cd eCashFlow-Simulator
./gradlew run
Usage
Launch the application.

Register a new account or log in with existing credentials.

Use the various features of the application, such as managing your account, performing transactions, and viewing transaction history.

Logout and close the application.

Contributing
Contributions to the eCashFlow Simulator project are welcome. To contribute:

### Fork the repository.

### Create a new branch:

bash
git checkout -b feature/your-feature-name
Make your changes and commit them:

bash
git commit -m "Add your commit message"
Push your changes to your forked repository:

bash
git push origin feature/your-feature-name
Open a pull request in the main repository and describe your changes.

### License
This project is licensed under the MIT License.

### Contact
For any inquiries or support, please contact siddharth.dubey5815@gmail.com

Acknowledgements
JavaFX Documentation
JDBC Documentation
MySQL Documentation
PostgreSQL Documentation
