# Password Strength Checker

## Description
Password Strength Checker is a tool designed to measure the security of a password. It calculates the strength based on password length, complexity, and uniqueness.

## Features
- Checks password length and complexity
- Provides real-time feedback on password strength
- Detects common patterns and weak passwords
- Allows customization of password validation rules

## Development Environment
This project was developed using NetBeans IDE.

## Implementation
The tool uses Java Swing for UI components and regular expressions to analyze password strength. The main functionality is implemented in the `checkPasswordActionPerformed` method, which:
1. Retrieves user input.
2. Validates the input length.
3. Calls `checkPasswordStrength` to evaluate password security.

The `checkPasswordStrength` function assigns a score based on the presence of:
- Lowercase letters
- Uppercase letters
- Numbers
- Special characters

Based on the score, the password is classified as Weak, Medium, or Strong, with corresponding color-coded feedback.

## Usage
### Java Version
Run the Java application in NetBeans:
1. Open the project in NetBeans.
2. Run `CheckePassword.java`.
3. Enter a password in the input field and click the check button to see the strength evaluation.

## Contributing
1. Fork the repository
2. Create a new branch (`feature-branch`)
3. Commit your changes (`git commit -m 'Add new feature'`)
4. Push to the branch (`git push origin feature-branch`)
5. Open a Pull Request

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact
For any inquiries, please contact [maleezha1975@gmail.com](maleezha1975@gmail.com)
