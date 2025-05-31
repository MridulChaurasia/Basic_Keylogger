# Keylogger Tool

## Description
This is a basic Python-based keylogger that captures and logs keystrokes on a system. It records every key pressed by the user and stores the data into a log file for later review.

This project is intended purely for **educational purposes** to understand how keylogging mechanisms work, with strict adherence to ethical guidelines and legal use in controlled environments.

## Features
- Captures all keystrokes
- Logs data into a local file (`keylog.txt`)
- Runs in the background using `pynput` library
- Works on Linux systems with Python 3

## Usage

1. Install required Python module:

```bash
pip install --user pynput
```

2. Run the script:

```bash
python3 Keylogger.py
```

The keypresses will be logged in `keylog.txt` in the same directory.

> **Press `Esc` to stop the keylogger (if implemented accordingly).**

## Concepts Demonstrated
- Event listeners using `pynput.keyboard`
- File I/O operations in Python
- Logging user interaction
- Ethical red teaming and controlled environment practices

## Requirements
- Python 3.x
- `pynput` module

## Disclaimer
This tool is strictly for **educational and ethical research purposes only**. Unauthorized use of keyloggers is illegal and unethical. Always ensure you have explicit permission before running this tool on any system.
