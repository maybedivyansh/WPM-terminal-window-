Speed Typing Test (WPM)
======================

A terminal-based speed typing test built with Python and the curses library. This project measures your typing speed in words per minute (WPM) as you type randomly selected text prompts.

---

## Key Features

- **Terminal UI:** Uses the curses library for a real-time, interactive terminal interface.
- **Random Text Prompts:** Loads random lines from `wpm.txt` for each test.
- **Live WPM Calculation:** Continuously updates and displays your current WPM as you type.
- **Real-Time Feedback:** Correctly typed characters are shown in green, mistakes in red.
- **Backspace Support:** Allows you to correct mistakes as you type.
- **Replayable:** Play as many rounds as you like, with a new prompt each time.
- **Exit Anytime:** Press ESC to exit the test or after completing a round.

---

## Requirements

- Python 3.x
- curses (standard on Unix/Linux/macOS; for Windows, install with `pip install windows-curses`)

---

## How to Run

1. Make sure you have Python 3 installed.
2. Ensure you have a `wpm.txt` file in the same directory, containing lines of text for typing prompts.
3. Run the script:
   ```
   python WPM.py
   ```
4. Follow the on-screen instructions to start the test and type the displayed text as quickly and accurately as possible.

---

## Example Session

```
Speed typing test
Press any key to begin!

The quick brown fox jumps over the lazy dog
WPM: 42
You completed the text! press any key to continue...
```

---

## Key Learnings

- **Curses Library:** Building interactive terminal applications with real-time feedback.
- **File I/O:** Loading random text prompts from a file.
- **Timing and WPM Calculation:** Measuring elapsed time and calculating words per minute.
- **Input Handling:** Managing special keys (backspace, ESC) and real-time character input.
- **Color Feedback:** Using color pairs to visually distinguish correct and incorrect input.
- **Game Loop Design:** Structuring the application for replayability and user engagement.

---
