# ACIT3630 - A_6_2fa 
# 2-factor Authentication Project
Implementation

You have to implement bcrypt at two stages of the app.


At the password generation stage. When you create a user with their plaintext password, this password has to be hashed with bcrypt and then stored. Storing the plaintext password is not acceptable.
At the password verification stage. Whenever a user verifies their credentials they supply a plaintext password. You have to hash this password with bcrypt and compare the resulting value with your stored value. If they match authentication is successful.



One-Time Password

HOTP (Hash-based One Time Passwords) is a method of user authentication. It creates a unique password based on a shared secret that can only be used a single time. It is usually used in conjunction with a regular password and is used to implement Two-Factor Authentication.
TOTP (Time-Based One Time Passwords) are created with the shared secret and an additional time stamp. This makes them only valid for a certain amount of time.