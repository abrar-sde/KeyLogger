# Python Keylogger 🖥️🔑

Welcome to **Python Keylogger**, a simple and educational project demonstrating how to capture and log keystrokes in Python. 🚀

> **Note:** This project is intended for educational purposes only. Make sure you have permission before running keyloggers on any system that’s not yours.

---

## 📜 Table of Contents

- [Overview](#-overview)
- [Installation](#-installation)
- [Usage](#-usage)
- [How It Works](#-how-it-works)

- [Screenshots](#-screenshots)

---

## 🧐 Overview

This **Python Keylogger** logs keystrokes into a text file and runs quietly in the background. It's built with minimal code, using the [`pynput`](https://pypi.org/project/pynput/) library to monitor keyboard inputs. This project helps in understanding how keyloggers work and how you can build one for personal use—debugging your own keyboard input or monitoring personal device activity.

---

## ⚙️ Installation

To run this keylogger on your local machine, follow the steps below:

1. **Clone the repository**:

    ```bash
    git clone https://github.com/Satyampathania/python-keylogger.git
    cd python-keylogger
    ```

2. **Install the dependencies**:

    ```bash
    pip install pynput
    ```

3. **Run the script**:

    ```bash
    python keylogger.py
    ```

---

## 🎯 Usage

Once the script is executed, the keylogger will begin recording key presses and store them in `key_log.txt`.

1. Open the terminal and navigate to the folder containing `keylogger.py`.
2. Run the script and start typing in any text editor or browser.
3. The keystrokes will be logged in the file `key_log.txt`.

---

## 🔍 How It Works

The keylogger uses the `pynput` library to listen for keyboard events. It captures each keystroke and appends it to a log file. Here's a breakdown:

- **Key Presses**: Logs every key typed, whether alphanumeric or special keys (like Shift or Enter).
- **Log Storage**: The data is stored in a text file called `key_log.txt` located in the project directory.

---

## ⚖️ Legal Notice ⚠️

Keyloggers have ethical and legal implications. Make sure to only use this software for personal, non-malicious purposes. Logging keystrokes without permission on someone else’s computer is illegal in many jurisdictions.

---

## 🖼️ Screenshots

Here are some screenshots demonstrating the keylogger in action:

### Keylogger in Terminal
![WhatsApp Image 2024-10-06 at 14 49 33_33c77877](https://github.com/user-attachments/assets/ffee21c3-84cf-4723-a159-fdda1cb751ae)

### Running and testing
![WhatsApp Image 2024-10-06 at 14 51 47_0d268b53](https://github.com/user-attachments/assets/c2b51a03-cf09-443e-bb80-8e2b352e4dfc)


### Log File Output
![WhatsApp Image 2024-10-06 at 14 53 15_332c563a](https://github.com/user-attachments/assets/f68bb52c-dfee-4e7f-9331-7cdedaee1f28)

---

