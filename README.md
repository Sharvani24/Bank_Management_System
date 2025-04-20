# Project Title
The name of the project is Bank Management System Using Java. The Bank Management System is a console-based Java application that allows users to perform basic banking operations like creating accounts, depositing, fast cash, pin change, withdrawing, mini statement and checking balances.
# Project Description:
The Bank Management System is a simple Java-based application designed to simulate basic banking operations. This project allows users to perform essential banking activities such as depositing and withdrawing money, checking account balance, and viewing account details. The application is built using Core Java.

# Features:
1. Create a new bank account
2. Deposit money into an account
3. Withdraw money from an account
4. Check balance of an account
5. Display all account information
6. Exit the system
# Technologies Used:
Programming Language: Java (Core Java)

IDE: VS Code(Any Java-supported IDE e.g., IntelliJ IDEA, Eclipse). At back-end, I am storing data using MySQL Workbench.
File Handling: To store and retrieve account information

# 🧑‍💻 How to Run the Project:
1. Clone the repository or download the source code.
2. Open the project in your preferred Java IDE.
3. Compile all .java files.
4. Run Main.java.
5. Use the command-line interface to interact with the system.
# Explanation of each module:
1. Login Screen - It consist of Card number and pin. It has three buttons as sign in, sign up and clear(to clear the entries done in card number and pin). Here the pin which we enter is invisible.
2. Signup Screen - It consist of various pages such as:
   Page1 : It consist of application form number and personal details such as name, father's name, gender, DOB, email address, marital status, address, city, pin code, state.
   Page2 : It consist of image of bank logo and additional details such as religion, category, income, education, occupation, PAN number, aadhar number, senior citizen and existing account. Some of them also have options as yes or no or a drop-down menu.
   Page3 : It also consist of image of bank logo and account details such as account type, card number, pin, services required and a checkbox.
3. Then we will connect our Java Project with MySQL  using the  JDBC connection  and imoprt java.sql.connection package. Store the data of signup page 2 and signup page3 in the database.
4. We will create Deposit class using which we can deposit some amount in our account.
5. We will create our main transactions Class which will have all the buttons of the functionalities user can use. In this we can sing in using the pin and card number. Then we will be redirected to the main screen of the ATM machine where transactions will take place. In that there are certain options like deposit, cash withdraw , fast cash etc.
6. We can check the balance in our account by creating a new class with name Balance_Enquiry and withdraw class using which we can  withdraw some amount from our account.
7. We have the Pin Change class using which user can change the  Pin of your account.
8. Then we have the Mini Statement class with all the transactions in your account.
