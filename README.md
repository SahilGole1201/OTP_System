OTP System using Python and SMTP

Overview
This OTP (One-Time Password) System is a simple and efficient implementation using Python and SMTP. It generates and sends OTPs via email for user verification, providing a basic yet secure authentication system without relying on any external libraries or frameworks beyond Python’s built-in functionalities.

Features
Generates a random 6-digit OTP for secure user verification.
Sends OTP via email using the SMTP protocol.
Validates email addresses to ensure they are correctly formatted before sending OTPs.
Allows OTP re-sending in case of an invalid entry.
Prompts the user to change the email address or resend the OTP if verification fails.

Technologies Used
Language: Python
Email Delivery: SMTP (Simple Mail Transfer Protocol)
