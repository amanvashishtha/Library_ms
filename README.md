# Library Management System Project Documentation

## Introduction

Welcome to the Library Management System project documentation. This guide will walk you through the steps required to set up, run, and use the project. Make sure you have all the necessary software and tools installed on your system before proceeding.

Prerequisites

Before you begin, ensure you have the following installed on your system:

1. JDK (Java Development Kit) 20
2. Apache XAMPP
3. Apache NetBeans

Installation and Setup

Step 1: Install JDK

1.Download and install JDK 20 from the official Oracle JDK download page.

2.Set up the JAVA_HOME environment variable:
          - On Windows:
            Open the Control Panel.   
            Navigate to System and Security > System.
            Click on Advanced system settings.
            Click on Environment Variables.
            Under System variables, click New and enter JAVA_HOME as the variable name and the path to your JDK installation as the variable value.
         
        -  On Mac/Linux:
         Add the following line to your ~/.bash_profile or ~/.bashrc file:
                  export JAVA_HOME=/path/to/your/jdk
                  export PATH=$JAVA_HOME/bin:$PATH
         - Apply the changes:

                  source ~/.bash_profile

Step 2: Install and Start Apache XAMPP

     1. Download and install XAMPP from the official XAMPP download page.

     2. Start the XAMPP control panel and start the Apache and MySQL servers.

Step 3: Import the Project into Apache NetBeans

     1. Open Apache NetBeans.
     2. Click on File > Open Project.
     3.Navigate to the cloned project directory and select it. 
     4.Wait for NetBeans to load the project and its dependencies.

Step 4 : Configure the Database

     1. Open PHPMyAdmin from the XAMPP control panel.
     2. Create a new database named library_management.
     3. Import the provided SQL file to set up the necessary tables and data:
               - Click on Import.
               - Choose the SQL file located in the project directory.
                - Click on Go.

Running the Application

Step 1: Run the Main File

         1. In NetBeans, navigate to the src directory of the project.
         2. Locate the SignUpPage file.
         3. Right-click on the SignUpPage file and select Run.

Step 2: Sign Up and LogIn
         1. Once the application is running , a signup page will appear
         2. Enter the required details (username, password, email, and contact) to create a new account.
         3. After signing up, log in using the credentials you just created.

Step 3: Use the Library Management System

          1. After logging in, you will be directed to the home page/dashboard.
          2. Explore the various functionalities:
              - Manage Books: Add, delete, update, and view books.
              - Manage Students: Add, delete, update, and view student records.
              - Issue Details: Track book borrowings and returns.
          3. Utilize the intuitive interface and the pie chart for a visual overview of the library's data.

## Additional Information
### Working Video: Project Demo
Note: Some content, icons, and pictures used in this project are sourced from the internet. This project is solely for learning and educational purposes and is not intended for any professional use. 

Conclusion
Thank you for using the Library Management System. I hope this documentation helps you set up and run the project smoothly. If you have any questions or need further assistance, feel free to reach out.

