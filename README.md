🖥️ Fake BSOD Prank Script (Windows)

⚠️ WARNING: This script shuts down the computer automatically. Use at your own risk.
This project is intended for educational or prank purposes only on systems you own or have permission to use.

📌 Description

This Python script simulates a fake system crash / BSOD sequence on Windows using:

Full-screen Tkinter window

Desktop screenshot overlay

Image and sound effects

Keyboard input blocking

Automatic system shutdown at the end

Once the user clicks the screen, a sequence of images and sounds plays, creating the illusion of a system failure or virus attack.

🎯 Features

Takes a screenshot of the desktop and displays it fullscreen

Blocks specific keyboard keys (A, B, CTRL, ALT)

Plays multiple sound effects asynchronously

Displays a sequence of fullscreen images (bsod1.png, bsod2.png, etc.)

Hides the mouse cursor

Forces a Windows shutdown at the end

🧰 Requirements
Operating System

Windows only (uses winsound and Windows shutdown command)

Python Version

Python 3.8+ recommended

Required Libraries

Install dependencies with:

pip install pyautogui pillow keyboard


Built-in modules used:

winsound

tkinter

time

os

sys

📁 Project Structure
project-folder/
│
├── main.py
├── desktop.png                # auto-generated
├── bsod1.png
├── bsod2.png
├── ...
├── bsod15.png
│
├── df.wav
├── noise1.wav
├── noise2.wav
├── noise3.wav
├── final.wav
├── virus-noise.wav
├── another-virus-pyrus.wav
├── bio-alarm.wav
└── usb-connect-disconnect-windows-11.mp3


⚠️ All image and audio filenames must match exactly.

▶️ How It Works

Script waits 5 seconds

Minimizes all windows (Win + D)

Takes a screenshot of the desktop

Displays the screenshot in fullscreen mode

Waits for a mouse click

Plays a timed sequence of:

Images

Sound effects

Blocks user input

Shuts down the computer

🖱️ How to Run
python main.py


After launch:

Do not click unless you want the sequence to start

Clicking anywhere on the screen triggers the event

⚠️ Important Warnings

This script will shut down the computer

Keyboard input is partially blocked

Can cause panic or confusion

Do NOT run on production or shared systems

Use only with permission

🛑 How to Stop (Emergency)

Before clicking:

Close the terminal

Kill the Python process via Task Manager

After clicking:

Shutdown is forced — interruption may not be possible

📜 Disclaimer

This project is provided as-is, without warranty.
The author is not responsible for data loss, misuse, or damages caused by running this script.

⭐ Credits

Created using:

Python

Tkinter

PyAutoGUI

PIL (Pillow)
