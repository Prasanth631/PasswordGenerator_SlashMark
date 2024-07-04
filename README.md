"# PasswordGenerator_SlashMark" 

# SecurePass - Password Generator

SecurePass is a Java-based application designed to help users create strong, customized passwords securely. It features a command-line interface for generating passwords and evaluating their strength based on user-defined criteria.

## Key Features

- **Customizable Password Generation**: Choose from uppercase letters, lowercase letters, numbers, and symbols to create unique passwords.
- **Password Strength Evaluation**: Evaluate password strength based on length, complexity, and adherence to security best practices.
- **Useful Tips**: Offers guidance on creating secure passwords and avoiding common pitfalls.

## Installation and Usage

### Installation

1. **Clone the repository:**

   ```
   git clone https://github.com/Prasanth631/PasswordGenerator_SlashMark
   cd SecurePass
   ```

2. **Compile the project:**

   ```
   javac -d bin src/*.java
   ```

### Usage

1. **Run the application:**

   ```
   java -cp bin Main
   ```

2. **Follow the on-screen instructions** to customize your password preferences and generate a secure password.
3. SecurePass provides instant feedback on password strength and suggestions for improvements.

## Design Principles

- **Modular Architecture**: Separates functionality into modules for password generation, validation, and user interaction for clarity and maintainability.
- **Interactive Interface**: Provides a user-friendly command-line interface with clear prompts and informative messages.
- **Robust Error Handling**: Ensures smooth user experience through comprehensive error handling and validation mechanisms.
- **Randomization**: Implements strong randomization techniques to enhance password security and unpredictability.

## Challenges Addressed

- **User Input Validation**: Ensuring secure and reliable input handling to prevent vulnerabilities and errors.
- **Performance Optimization**: Balancing security requirements with performance considerations for efficient password generation.
- **Feedback Mechanism**: Developing effective feedback mechanisms to guide users towards creating stronger passwords.

