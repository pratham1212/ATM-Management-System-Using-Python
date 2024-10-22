ATM Management System
Overview
This ATM Management System is a simple Python application that simulates basic ATM functionalities such as account login, checking balance, depositing money, withdrawing cash, and viewing transaction history. The system uses Object-Oriented Programming (OOP) concepts, including encapsulation and abstraction, to enhance security and maintainability.

Features
Login: Users can log in using their account number and PIN.
Check Balance: Users can view their current account balance.
Deposit: Users can deposit money into their account.
Withdraw: Users can withdraw money from their account.
Transaction History: Users can view a history of their transactions.
Technologies Used
Python
SimpleGUICS2Pygame (for the GUI)
OOP Concepts Implemented
Encapsulation: Sensitive data (like account numbers and PINs) is kept private within the class, preventing unauthorized access. This ensures that only the ATM class methods can interact with the data.
Abstraction: The user interacts with simple methods (like deposit and withdraw) without needing to understand the underlying complexity of how the data is managed.


Installation
Clone the repository:
bash
Copy code
git clone https://github.com/pratham1212/ATM-Management-System-Using-Python
Navigate to the project directory:
bash
Copy code
cd ATM-Management-System-Using-Python
Install the necessary library (if not already installed):
bash
Copy code
pip install SimpleGUICS2Pygame


How to Use
Run the Program: Execute the script to open the ATM GUI.
Login: Enter your account number and PIN.
If the login is successful, you will see the main menu.
If the login fails, you will receive an error message.
ATM Menu:
Check Balance: Click the button to view your current balance.
Deposit: Enter the amount you wish to deposit and click the deposit button. You will see a confirmation message with your new balance.
Withdraw: Enter the amount you wish to withdraw and click the withdraw button. If the amount is available, the system will deduct it from your balance; otherwise, you will see an error message.
View History: Click the button to see a history of your transactions.
Exit: Click to exit the program, and your account summary will be displayed.
Outputs
Login Success: "Login successful for account {acc_number}."
Login Failure: "Incorrect PIN. Please try again."
Balance Check: "Balance: {balance}"
Deposit Confirmation: "Deposited {amount}. New Balance: {new_balance}"
Withdrawal Confirmation: "Withdrew {amount}. New Balance: {new_balance}"
Insufficient Funds: "Insufficient balance."
Invalid Amount: "Invalid amount."
Transaction History: A list of all transactions for the account or "No transactions found."
Conclusion
This ATM Management System is a practical example of how to implement OOP principles to create a secure and user-friendly application. By using encapsulation and abstraction, the system ensures that sensitive information is protected and that users can interact with the system easily.
