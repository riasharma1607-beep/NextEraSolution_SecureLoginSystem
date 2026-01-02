# Secure Login System

This project is developed as part of the **Cyber Security Internship** at  
**NextEra Solution With Technology**.

## Project Overview
The Secure Login System demonstrates how user authentication can be implemented securely using password hashing and validation.  
Passwords are **never stored in plain text**; instead, they are converted into a hashed format to ensure user data protection.

## Features
- Secure user registration
- Password hashing using Bcrypt
- Login authentication with password validation
- Protection against plain-text password storage

## Technologies Used
- Python  
- Flask  
- Flask SQLAlchemy  
- Flask Bcrypt  
- SQLite Database  
- Google Colab  

## How It Works
1. User registers with email and password  
2. Password is hashed before storing in the database  
3. During login, entered password is verified against the stored hash  
4. Login is successful only if the hash matches  

## Testing
The project includes test cases to demonstrate:
- Hashed password storage
- Successful login with correct password
- Failed login with incorrect password  

## Internship Task
This project fulfills **Task 1: Secure Login System** under the **Cyber Security domain**.

## Author
Intern at **NextEra Solution With Technology**
