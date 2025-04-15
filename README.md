# Telegram GigaChat Bot

This project is a simple Telegram chatbot built using Python and the [g4f library](https://pypi.org/project/g4f/). The bot is designed to maintain conversation history per user, handle commands such as /start and /clear, and generate intelligent responses via g4f's interface to various AI backends.

## 📚 Description

Originally developed as a student project under the supervision of my instructor ([GitHub: inkara06](https://github.com/inkara06)), this bot has evolved to utilize the g4f library for its core AI functionalities. This change replaces the previous direct integration with the GigaChat API, offering a more streamlined approach to interacting with language model APIs.

The project implements robust handling of Telegram interactions with the help of the pyTelegramBotAPI library while managing conversation histories and command responses.

## 🔧 Features

- g4f Library Integration: Leverages g4f to simplify communication with AI models.
- Conversation History: Maintains individual chat histories for users.
- Command Support: Includes /start for initialization and /clear to reset conversations.
- Deployment Ready: Easily deployable on remote servers (Render, Railway, etc.).

## 🧪 Technologies Used

- Python 3.8+
- [pyTelegramBotAPI](https://pypi.org/project/pyTelegramBotAPI/)
- [g4f Library](https://pypi.org/project/g4f/)
- Additional utilities such as requests (if needed)

## 🔐 Environment Variables

Before running the bot, ensure you have a .env file in your project root (or set these variables in your hosting dashboard):
