README
Project Title : Echo Bot with Azure AI Language Sentiment Analysis

Overview
This project is a Python-based chatbot built using the Microsoft Bot Framework SDK. The bot receives user messages, analyzes their sentiment using Azure AI Language, and responds with the sentiment result along with confidence scores.

Features:
Echoes user messages

Performs sentiment analysis using Azure AI Language

Handles malformed or empty input

Provides a capabilities/help command

Responds to greetings


Requirements:
Python 3.8+

Bot Framework Emulator

Azure AI Language resource (endpoint + key)

Required Python packages (see requirements.txt)

Testing Bot



Files
app.py — main application

bots/echo_bot.py — bot logic

config.py — configuration and environment variables

requirements.txt — dependencies
