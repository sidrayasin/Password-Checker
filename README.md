# Password-Checker
This password checker allows users to create a strong password by determining the amount of times a given password has been hacked using the 'haveibeenpwned.com' api.

# Functionality
Input a password as an argument when opening the python file through the terminal. 
This python code only accesses the api to compare the first 5 characters of the sha1 hashed password to allow a more secure search within the database. Through the narrowed database, we are able to match the given password to determine the amount of times the password has been hacked.

# Installations
- requests module 

