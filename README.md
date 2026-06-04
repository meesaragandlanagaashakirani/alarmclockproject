# Objective

The objective of this project is to create a simple alarm clock application in Python that alerts users at a specified time. This project helps beginners understand how to work with date and time functions, loops, and user input in Python.

# Concepts Used

* Variables and Data Types
* User Input (`input()`)
* Infinite Loops (`while True`)
* Conditional Statements (`if`)
* Date and Time Handling (`datetime` module)
* Time Delay (`time.sleep()`)
* Sound Notifications (`winsound` module for Windows)

# Technologies Used

* **Programming Language:** Python 3
* **Libraries/Modules:**

  * `datetime` – for obtaining and formatting current time
  * `time` – for delaying program execution
  * `winsound` – for generating alarm sounds on Windows systems

# How It Works

1. The user enters the desired alarm time in `HH:MM:SS` format.
2. The program continuously checks the current system time.
3. Every second, the current time is compared with the alarm time.
4. When both times match, the program:

   * Displays an alarm message.
   * Plays a beep sound.
5. The program then stops execution.

# Author

**Name:** asha kirani

**Project:** Alarm Clock Using Python

**Description:** A beginner-friendly Python project demonstrating the use of date and time operations, loops, and sound notifications to build a functional alarm clock application.
