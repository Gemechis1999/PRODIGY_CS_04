🔑 Key Components:

Importing the Library:
Utilized the Listener class from the pynput.keyboard module to monitor keyboard events.

Defining the Log File:
Created a log file (keylog.txt) to store the captured keystrokes.

Key Press Handling:
Developed the on_press function to handle key press events. This function opens the log file in append mode and writes the pressed keys to it.

Setting Up the Listener:
Set up a listener to monitor keystrokes and invoke the on_press function whenever a key is pressed. The listener runs continuously, awaiting keypress events.

🛠 How to Use:
Clone or download the repository.
Install the pynput library using pip install pynput.
Run the script using python keylogger.py.
Check keylog.txt for the recorded keystrokes.

⚖️ Ethical Considerations:

Consent: Always obtain explicit consent before using this keylogger on any system.
Purpose: This tool is designed for educational purposes, testing, and development.
Legal Compliance: Ensure adherence to local laws and regulations regarding keylogging software.

This project highlights the importance of ethical considerations in software development, especially when dealing with sensitive data. It also reinforces the significance of data security and privacy in our digital age.
