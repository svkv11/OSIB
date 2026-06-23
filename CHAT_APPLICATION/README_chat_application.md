# Simple Chat Application

**Author:** VENKAT KALYAN VARMA SANGARAJU

---

## Overview

A lightweight rule-based console chat application written in Python. The program simulates a basic conversation between a user and a bot through the terminal, responding to a set of predefined inputs with matching replies.

---

## Features

- Greets the user when common greetings are entered (`hello`, `hi`, `hey`)
- Responds to casual questions like "how are you" and "what is your name"
- Gracefully exits the conversation when the user types `bye`
- Handles unrecognized input with a polite fallback message
- Input is case-insensitive (converted to lowercase before matching)

---

## How to Run

```bash
python chat_application.py
```

---

## Sample Interaction

```
=== Simple Chat Application ===
Type 'bye' to exit

You: hello
Bot: Hi! How are you?

You: what is your name
Bot: My name is ChatBot.

You: how are you
Bot: I am fine. Thanks for asking!

You: bye
Bot: Goodbye!
```

---

## Supported Commands

| User Input                        | Bot Response                      |
|-----------------------------------|-----------------------------------|
| `hello` / `hi` / `hey`           | Hi! How are you?                  |
| `how are you`                     | I am fine. Thanks for asking!     |
| `your name` / `what is your name`| My name is ChatBot.               |
| `bye`                             | Goodbye! (exits the program)      |
| Anything else                     | Sorry, I don't understand.        |

---

## Requirements

- Python 3.x
- No external libraries required

---

## Future Improvements

- Add more conversation topics and responses
- Integrate NLP (e.g., NLTK or spaCy) for smarter intent matching
- Store conversation history to a log file
- Build a GUI using Tkinter or a web frontend

---

*Created by VENKAT KALYAN VARMA SANGARAJU*
