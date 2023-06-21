# Random Password Generator

This is a simple Python script that generates a random password based on the user's input.

## Requirements

- This program requires **Python 3.x** to be installed on your machine. You can download it from the official website: https://www.python.org/downloads/

## How to use

1. Run the program using the command `python3 password_generator.py` in your terminal.
2. Enter the minimum length of the password when prompted. 
3. Answer "y" or "n" for whether you want numbers and special characters included in the password.
4. The program will generate the password for you and display it on the screen.

## How it works

- The script takes input from the user for the minimum length of the password, whether to include numbers, and whether to include special characters.
- The characters that can be used in the password are stored in variables using the `string` module.
- If the user chooses to include numbers or special characters, those are added to the list of possible characters.
- The script then generates a random password using the `random` module by selecting characters from the list of possible characters.
- The script continues to add characters until the password meets the length criteria set by the user, and includes at least one number (if selected) and at least one special character (if selected).
- The final password string is returned and displayed on the screen.

Feel free to customize the script to fit your needs!