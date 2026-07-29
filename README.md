# Bank Management System

A desktop-based Bank Management System developed using Java Swing and MySQL. The application enables users to create bank accounts, authenticate securely, and perform various banking operations through an intuitive graphical user interface.

## Features

- User Registration
- User Authentication (Login)
- Deposit Money
- Withdraw Money
- Fast Cash Withdrawal
- Balance Enquiry
- Mini Statement
- ATM PIN Change
- MySQL Database Integration

## Technologies Used

- Java
- Java Swing
- AWT
- JDBC
- MySQL

## Requirements

- JDK 8 or above
- IntelliJ IDEA / Eclipse
- MySQL Server

## Project Structure

- `Login.java` – User login
- `Signup.java` – User registration
- `Signup2.java` – Additional user details
- `Signup3.java` – Account type selection and ATM card generation
- `main_Class.java` – Main dashboard
- `Deposit.java` – Deposit transactions
- `Withdrawl.java` – Withdrawal transactions
- `FastCash.java` – Quick cash withdrawal
- `BalanceEnquriy.java` – Balance enquiry
- `mini.java` – Mini statement
- `Pin.java` – ATM PIN update
- `Connn.java` – MySQL database connection

## Database

Create a MySQL database named:

```sql
banksystem
```

Import the required tables and update the database credentials in `Connn.java`.

## How to Run

1. Clone or download the repository.
2. Open the project in IntelliJ IDEA or Eclipse.
3. Create the `banksystem` database in MySQL.
4. Configure the database username and password in `Connn.java`.
5. Run `Login.java`.

## Future Improvements

- Money Transfer
- Transaction History
- Password Encryption
- Admin Dashboard
- Email Notifications
- Better Exception Handling

## Author

**Pratistha Kesarwani**