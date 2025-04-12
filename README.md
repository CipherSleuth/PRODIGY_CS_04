# Python Keylogger (Educational Purposes Only)

This is a basic Python-based keylogger created purely for **educational and ethical hacking learning**. It listens for keystrokes on a user's system and logs them to a text file named `keylog.txt`.

**Created by Tejas Sardar.**

---

## Table of Contents

- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [How It Works](#how-it-works)
- [Output Example](#output-example)
- [Security and Ethics](#security-and-ethics)
- [Limitations](#limitations)
- [Disclaimer](#disclaimer)
- [License](#license)

---

## Features

- Logs every key typed on the keyboard.
- Captures both regular characters and special keys like space, enter, backspace, etc.
- Outputs all keystrokes to a plain text file.
- Very lightweight and simple to understand.
- Runs in the background without GUI.

---

## Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/keylogger.git
   cd keylogger

2. Install Required Package This script uses the pynput package to listen to keyboard events. You can install it using pip:

pip install pynput




---

Usage

To run the keylogger:

python keylogger.py

The keystrokes will be saved in a file called keylog.txt in the same directory.

To stop the keylogger, press CTRL + C in the terminal or kill the Python process if running in the background.


---

How It Works

The script uses pynput.keyboard.Listener to listen for keyboard events. Every key that is pressed is captured and written into the keylog.txt file. It differentiates between normal characters and special keys using a try-except block.

Normal keys like letters, numbers, symbols are written directly.

Special keys (space, enter, shift, etc.) are written in [brackets].



---

Output Example

Sample content of keylog.txt:

Hello[Key.space]World[Key.enter]
My[Key.space]password[Key.space]is[Key.space]notsecure123


---

Security and Ethics

This project is intended for:

Educational purposes

Learning how keyloggers work

Practicing ethical hacking in safe environments


Do NOT use this tool on someone else's computer without explicit permission. Unauthorized keylogging is illegal and unethical.


---

Limitations

Does not support remote monitoring or auto emailing (can be added optionally).

Logs are saved locally only.

May not work with all OS input methods.

This is a basic version without stealth or advanced features.



---

Disclaimer

This software is provided as-is without any warranties or guarantees.
The developer is not responsible for any misuse of this program.

> Use it responsibly and only for ethical hacking learning or penetration testing where you have permission.




---

License

This project is licensed under the MIT License - see the LICENSE file for details.
