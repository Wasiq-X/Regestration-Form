# Pygame Registration Form

A simple Registration Form GUI made using Python and Pygame.

This project allows users to enter their Name, Email, and Password and register through an interactive graphical interface.

## Features

* Name input field
* Email input field
* Password input field
* Password is displayed as `*` characters
* Mouse-based field selection
* Keyboard input support
* Press Enter to move between fields
* Register button
* Registration success message
* Window close support

## Technologies Used

* Python
* Pygame

## Installation

First, make sure Python is installed on your computer.

Install Pygame using:

```bash
pip install pygame
```

## How to Run

1. Download or clone this project.
2. Open the project folder.
3. Run the Python file:

```bash
python registration_form.py
```

4. The Registration Form window will open.
5. Enter your Name, Email, and Password.
6. Click the Register button.
7. If all fields are filled, you will see:

```text
Registration Successful!
```

## How to Use

### Mouse Controls

Click on any input box to select it.

### Keyboard Controls

* Type to enter text
* Backspace to delete text
* Enter to move to the next field
* Close Button to exit the application

## Project Structure

```text
Registration-Form/
│
├── registration_form.py
└── README.md
```

## How It Works

The program creates a Pygame window and displays three input fields for the user's information.

The `active_field` variable keeps track of which field is currently selected. Keyboard events are used to add or remove characters from the selected field.

When the user clicks the Register button, the program checks whether the Name, Email, and Password fields are filled.

If all three fields contain information, the program displays:

```text
Registration Successful!
```

## Password Protection

For privacy, the password is not displayed directly. Each password character is shown as:

```text
*****
```

This provides a basic password-masking feature for the GUI.

## Learning Goals

This project is useful for beginners learning:

* Python programming
* Pygame GUI development
* Event handling
* Mouse events
* Keyboard events
* Variables and conditions
* Input fields
* Basic user interaction

## Future Improvements

Some possible improvements are:

* Add email validation
* Add password strength checking
* Add a Show/Hide Password button
* Save registered information to a file
* Add username availability checking
* Add a login system
* Improve the GUI design
* Add error messages for empty fields

## Author

Wasiq

This project was created as a beginner-friendly Python and Pygame project to practice GUI development and event handling.

## Conclusion

The Pygame Registration Form is a simple project that demonstrates how Python and Pygame can be used to create an interactive registration interface.

It is a good beginner project for understanding GUI design, keyboard input, mouse interaction, and conditional logic.
