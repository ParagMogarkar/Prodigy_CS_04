# 🛡️ Simple Keylogger (Educational Purpose Only)

A basic Python keylogger that captures and records keystrokes to a local file using the `pynput` library. This project is part of the **Prodigy Infotech Internship Program** under cybersecurity tasks.

> ⚠️ **Disclaimer**: This tool is for **educational use only**. Do not use it without explicit consent. Unauthorized use may be illegal.

---

## 💡 How It Works

- Uses the `pynput.keyboard` module to listen for keypress events.
- Every keystroke is logged and written to a file named `keylog.txt`.
- Special keys (like `Shift`, `Enter`, etc.) are recorded by name.

---

## 🚀 Features

- Captures all keyboard inputs in real-time.
- Writes to a persistent log file (`keylog.txt`).
- Lightweight and easy to understand.
- Cross-platform (Windows, macOS, Linux)

---

## 💻 Requirements

- Python 3.x
- `pynput` library

Install with:
```bash
pip install pynput
