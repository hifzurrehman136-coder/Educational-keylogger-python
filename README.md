Python Keylogger (Educational Project)

This project is a simple **Python Keylogger** built using the `pynput` library. It captures keyboard input events and logs the pressed keys into a text file. The purpose of this project is to demonstrate how keyboard listeners work in Python and to help students understand basic cybersecurity concepts.

⚠️ Disclaimer
This project is created strictly for educational purposes. It should only be tested on your own system in a controlled environment. Unauthorized use of keylogging software without permission is illegal and unethical.

How It Works

The program uses the `pynput.keyboard` module to listen for key press events.

 When a key is pressed, the `keyPressed()` function is triggered.
 The pressed key is printed on the screen.
The key is then saved into a file named keyfile.txt.
 Special keys that do not contain characters are handled using a try-except block.
 The listener runs in the background until the user stops the program.
 
Features

Captures keyboard keystrokes in real-time
Saves logged keys to a text file
Uses Python’s `pynput` library
Simple and beginner-friendly implementation
Demonstrates event-driven programming

Technologies Used

* Python 3
* pynput library

Install dependency:

pip install pynput

Learning Objectives

Through this project, you can learn:

 How keyboard event listeners work
 File handling in Python
 Exception handling (try-except)
 Basics of cybersecurity awareness


Usage


python keylogger.py

The program will start recording keystrokes and store them in `keyfile.txt`. Press **Enter** in the console to stop the program.



Future Improvements

 Logging special keys clearly (e.g., Space, Enter)
 Adding timestamp for each key press
 Encrypting the log file
 Sending logs to email (for advanced learning purposes)




