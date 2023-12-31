
# Loan Management System (Web Application)

The Loan Management System is a web application that aims to solve the problems of traditional loan application systems by 
providing a user-friendly platform for users to apply for loans, view their loan details, and make EMI payments. Additionally, 
the system includes an admin module for loan officers to approve user loan applications efficiently.

## Features
- User Registration and Authentication: Users can create an account and log in to access the loan application and other features.
- Loan Application: Users can apply for loans by providing necessary details and documents.
- Loan List: Users can view a list of their active loans and their respective details.
- EMI Payment: Users can make EMI payments using various payment methods.
- Admin Module: Loan officers with admin credentials can approve or reject user loan applications.

## Project Setup Steps
To set up the Loan Management System project, follow these steps:

### Prerequisites
- Java JDK 11 or higher installed on your system
- Apache Maven installed
- MySQL or any other compatible database system

### Step 1: Clone the Repository
Clone the project repository from GitHub to your local machine using the following command:
git clone https://github.com/your-username/loan-management-system.git

### Step 2: Configure Database
1. Create a MySQL database with the name "loan_management_system".
2. Open the "application.properties" file located in `src/main/resources`.
3. Update the database connection properties, such as `spring.datasource.username` and `spring.datasource.password`, with your MySQL credentials.
4. 
### Step 3: Import the Project
Open your java editor, import the project file using option import maven project.

### Step 4: Run the Application
Run the Spring Boot application using run command run as springboot project.
The application will start, and you can access it at `http://localhost:8080`.

### Step 5: Access Admin Module
To access the admin module, create an admin account in the database. You can do this manually using MySQL queries or create an API endpoint to register an admin user.

### Step 6: Start Using the Application
1. Register as a user through the application's registration page.
2. Log in with your credentials.
3. Apply for a loan by providing the required details and documents.
4. Use the loan list to track your active loans and their details.
5. Make EMI payments through the payment gateway integration.
As an admin, you can log in using the admin credentials and approve/reject user loan applications.

## Technologies Used
- Spring Boot: Java-based framework for building web applications.
- MySQL: Database to store application data.
- Maven: Dependency management and build tool.
