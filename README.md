# Password Complexity Checker

## Objective

Create a Password Complexity Checker using Python that evaluates the strength of a password based on multiple security criteria such as:

- Password length
- Presence of uppercase letters
- Presence of lowercase letters
- Presence of numbers
- Presence of special characters

The tool also provides feedback and suggestions to help users improve their password strength.

This project was developed as part of Task-03 of my Cybersecurity Internship at Prodigy InfoTech.



# Features Implemented

Minimum 8-character password validation  
Uppercase letter detection  
Lowercase letter detection  
Numeric digit detection  
Special character detection  
Interactive password checking system  
User feedback and improvement suggestions  
Exit option to exit continuous loop  
Strong/Weak password indication  


# Technologies Used

- Python
- Regular Expressions (`re` module)
- Functions
- Loops
- Conditional Statements
- String Methods

---

# Methods and Functions Used

| Method / Function | Purpose |

| `isdigit()` | Checks numeric digits |
| `isupper()` | Checks uppercase letters |
| `islower()` | Checks lowercase letters |
| `lower()` | Converts input to lowercase |
| `re.search()` | Detects special characters |
| `any()` | Checks condition existence |
| `while True` | Creates interactive loop |

---

# Working Principle

The program continuously accepts user passwords and checks whether they satisfy important password security conditions.

If a condition is missing, the tool immediately provides feedback such as:

- Password must contain at least 8 characters
- Add at least one digit
- Add at least one uppercase letter
- Add at least one lowercase letter
- Add at least one special character

Once all requirements are satisfied, the tool displays a strong password confirmation message.

---

# Output Examples ~

Enter your password (or type 'exit' to quit): hello
Use minimum 8 characters in the password : Weak Password !

Enter your password (or type 'exit' to quit): hellpool
Must have atleast one digit in the password : Weak Password !

Enter your password (or type 'exit' to quit): hellpool123
Must have atleast one uppercase letter in the password : Weak Password !

Enter your password (or type 'exit' to quit): Hellpool123
Must have atleast one special character : Medium Password !

Enter your password (or type 'exit' to quit): Hellpool@123
Password is all set! : Strong Password

Enter your password (or type 'exit' to quit): exit

Thank you for using the Password Checker Tool!