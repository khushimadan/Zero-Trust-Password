# Zero Trust Password

Project PPT : https://www.canva.com/design/DAFh9MtCgbc/skYMI7J7ry36VOV4BMoaLA/view?utm_content=DAFh9MtCgbc&utm_campaign=designshare&utm_medium=link&utm_source=editor

# Overview
People often use their name, parents' name and important dates such as D.O.B,Anniversary etc. in their passwords which make them weak and easy to crack by hackers.
ZeroTrust is a web application built with Flask that focuses on checking the strength of password entered by a user. It shows a password as Weak if it contains personal information of the user and it shows a password as Strong if it doesn't contain their personal information in any form. 

Zero Trust ensures secure User Authentication and Password Management. It incorporates one-time Password (OTP) verification for registered users, password strength checking and personalized password recommendations for users. It also shows an estimated time to crack the entered password by a hacker using Brute Force method.

# Table of Contents

1. Installation

2. Usage

3. Features

4. Dependencies

5. Configuration


# Installation

To run this Flask application locally, follow these steps:

1. Clone the repository : git clone https://github.com/khushimadan/ZeroTrustPassword.git

2. Change into the project directory : cd ZeroTrustPassword

3. Install the required dependencies : pip install -r Requirements.txt

4. Set up the MySQL database : Ensure you have a MySQL server running and update the db_config dictionary in the App.py file with your database credentials

5. Run the Flask application : python App.py

# Usage

The application provides several routes for user registration, login and password management. Here are some key routes:

/: Welcome page

/login1: Login page

/signup1: Signup page

/password_checker_signup: Password strength checker for signup

/password_checker_login: Password strength checker for login

/sendOtp: Route for sending OTP

/signup_add: Additional information for signup

/submit_form: Form submission for user signup

/submit_signupform: Additional information submission for signup

/send_OTP: Sending OTP for login

/verify_otp: Verifying OTP

/password: Password strength checking for signup

/password_login: Password strength checking for login

/recommend: Password recommendation

/recommend_login: Password recommendation for login

# Features

User Authentication : Secure user registration and login

One-Time Password (OTP) : OTP generation and verification for additional security

Password Strength Checker : Evaluate the strength of a password based on various criteria

Password Recommendation : Generate recommended passwords based on user information

Estimated Time to Crack Password: Provides the worst case time complexity of a hacker to hack the entered password by the user

MySQL Database: Store users' data securely in MySQL database


# Dependencies

Flask

MySQL Connector

Smtp

Random

Math

# Configuration

Update the db_config dictionary in the App.py file with your MySQL database credentials





