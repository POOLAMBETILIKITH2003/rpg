# rpg
# Overview
This repository hosts a Python script for generating random passwords. 
The script allows users to specify the number of passwords to generate and the length of each password. 
It employs a combination of lowercase letters, uppercase letters, and numbers to create diverse and secure passwords.
# Features
Random Password Generation: The script generates random passwords based on user-defined lengths.
Password Complexity: Passwords are designed to be more secure by incorporating a mix of lowercase letters, uppercase letters, and numbers.
User Interaction: Users can specify the number of passwords to generate and the length of each password through an interactive command-line interface.
Input Validation: The script validates user inputs to ensure they are valid integers and enforces a minimum password length of 3 characters.
# Code Structure
generatePassword(pwlengths): This function generates random passwords based on the provided lengths.
replaceWithNumber(pword): This function replaces random characters in the password with numbers to increase complexity.
replaceWithUppercaseLetter(pword): This function replaces random characters in the second half of the password with uppercase letters.
main(): The main function handles user interaction, input validation, and orchestrates the password generation process.
# Usage
Users can clone the repository and run the script locally. 
Upon execution, the script prompts the user to input the number of passwords to generate and the length of each password. 
After validation, it generates and displays the passwords.
