ATM Management System Using Python
Overview
This ATM Management System allows users to perform basic banking operations such as logging in, checking their balance, depositing money, withdrawing cash, and viewing transaction history. The application is built using Python and SimpleGUICS2Pygame, providing a simple graphical user interface (GUI) for interaction.

Features
Secure login using account number and PIN.
Check account balance.
Deposit money into the account.
Withdraw money from the account.
View transaction history.
User-friendly interface.
Prerequisites
To run this project, you need to have Python and the SimpleGUICS2Pygame library installed. You can install SimpleGUICS2Pygame using pip:

bash
Copy code
pip install SimpleGUICS2Pygame
Getting Started
Clone the Repository Download the project to your local machine using the following command:

bash
Copy code
git clone https://github.com/pratham1212/ATM-Management-System-Using-Python.git
cd ATM-Management-System-Using-Python
Run the Application Open your terminal or command prompt and run the main Python file:

bash
Copy code
python ATM Management System Using Python.py
Replace ATM Management System Using Python.py  with the name of your Python script.

How to Use the ATM System
Login

Enter your account number (e.g., 101) and PIN (e.g., 1234).
If the login is successful, you will see a welcome message and the main menu.
Example Output:

rust
Copy code
Login successful for account 101.
Menu Options Once logged in, you will see the menu options:

Check Balance: Displays the current balance in your account.
Deposit: Enter the amount you want to deposit.
Withdraw: Enter the amount you want to withdraw.
View History: Shows the history of your transactions.
Exit: Logs you out and returns to the login screen.
Check Balance Click the "Check Balance" button to view your current balance.

Example Output:


Copy code
Balance: 5000
Deposit Enter the amount you wish to deposit and click the "Deposit" button. The system will update your balance and log the transaction.

Example Output:


Copy code
Deposited 1000. New Balance: 6000
Withdraw Enter the amount you wish to withdraw and click the "Withdraw" button. If you have sufficient funds, the system will deduct the amount and update your balance.

Example Output:


Copy code
Withdrew 500. New Balance: 5500
View Transaction History Click the "View History" button to see a list of your recent transactions.

Example Output:


Copy code
Deposited: 1000
Withdrew: 500
Exit Click the "Exit" button to log out. The application will display the login screen again.

Example Output:

typescript
Copy code
Please login with your account number and PIN.
Conclusion
This project serves as a practical example of using Python to build a simple banking application. The ATM Management System demonstrates object-oriented programming concepts and user interaction through a GUI.
