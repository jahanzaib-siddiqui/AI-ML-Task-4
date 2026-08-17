# AI/ML Task 4 WhatsApp Auto-Reply Bot

## Project Overview

The WhatsApp Auto-Reply Bot is a Python-based automated reply engine developed as an AI/ML internship project.

The prototype takes a user's message as input, checks the message against predefined FAQ keywords, identifies the most relevant FAQ, and returns an automated response.

The project does not connect to the actual WhatsApp Business API. Instead, it demonstrates the core automated reply logic through a terminal-based chatbot.

## Features

- FAQ dataset stored in CSV format
- Keyword-based message matching
- Automated FAQ responses
- Terminal-based user input
- Default response for unknown questions
- Multiple FAQ categories
- Simple and lightweight implementation

## Technologies Used

- Python
- CSV
- Regular Expressions
- GitHub

## FAQ Categories

The chatbot currently supports:

- Working Hours
- Contact Information
- Services
- Pricing
- Registration
- Internship Information
- Support
- Location
- Payment Methods
- Cancellation Policy

## How It Works

1. The chatbot loads the FAQ dataset from `faq_dataset.csv`.
2. The user enters a question through the terminal.
3. The message is converted to lowercase.
4. Unnecessary punctuation is removed.
5. The chatbot checks the message against predefined FAQ keywords.
6. The FAQ with the highest keyword match is selected.
7. The corresponding automated response is displayed.
8. If no keyword matches, the chatbot displays a default support message.

## How to Run

### 1. Clone the repository

```bash
git clone YOUR_GITHUB_REPOSITORY_URL
