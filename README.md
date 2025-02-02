# Password Strength Checker

## Description
Password Strength Checker is a Java-based application that evaluates the security of a given password. It checks password length, complexity, and character variety to classify passwords as Weak, Medium, or Strong.

![Password Strength Checker Screenshot](screenshot.png)

## Features
- Validates password length (minimum 8 characters)
- Checks for lowercase, uppercase, numbers, and special characters
- Provides real-time feedback on password strength
- User-friendly GUI using Java Swing
- Color-coded strength indicators

## Development Environment
- **Language:** Java
- **IDE:** NetBeans
- **GUI Framework:** Java Swing

## Implementation
The application is implemented using Java Swing and utilizes regular expressions to assess password strength. The main functions include:

### `checkPasswordActionPerformed`
1. Retrieves user input.
2. Validates input length.
3. Calls `checkPasswordStrength` for evaluation.

### `checkPasswordStrength`
This function assigns a score based on the presence of:
- Lowercase letters
- Uppercase letters
- Numbers
- Special characters

### Strength Classification:
- **Weak**: Fewer than two conditions met
- **Medium**: Two to three conditions met
- **Strong**: All four conditions met

Color codes:
- **Red:** Weak
- **Orange:** Medium
- **Green:** Strong

## Usage
### Running the Application in NetBeans
1. Open the project in NetBeans.
2. Compile and run `CheckePassword.java`.
3. Enter a password in the input field.
4. Click "Check Strength" to see the evaluation.

## Contributing
1. Fork the repository.
2. Create a new branch (`feature-branch`).
3. Commit your changes (`git commit -m 'Add new feature'`).
4. Push to the branch (`git push origin feature-branch`).
5. Open a Pull Request.

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any inquiries, please contact [maleezha1975@gmail.com](mailto:maleezha1975@gmail.com).
