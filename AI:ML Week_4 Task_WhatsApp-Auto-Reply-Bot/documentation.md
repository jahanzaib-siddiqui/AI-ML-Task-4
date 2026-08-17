# Project Documentation

## WhatsApp Auto-Reply Bot – Automated Reply Engine

### 1. Project Overview

The WhatsApp Auto-Reply Bot is a Python-based automated reply system developed as a prototype for Nitroxshift Studios.

The system takes a user's message as input, checks the message against a predefined set of FAQ keywords, identifies the most relevant FAQ, and automatically returns the corresponding response.

The prototype works through the terminal and does not require a connection to the actual WhatsApp Business API.

---

## 2. What I Built

I built an automated FAQ reply engine that can:

- Accept questions from users through the terminal.
- Load predefined FAQs from a CSV dataset.
- Check user messages for relevant keywords.
- Identify the most relevant FAQ.
- Return an automated response.
- Handle unknown questions with a default response.
- Allow the user to continue asking questions until they type `exit`.

The FAQ dataset contains information about:

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

---

## 3. Technologies Used

The project was developed using:

- Python
- CSV
- Regular Expressions (`re`)
- GitHub

The chatbot uses Python's built-in libraries, so no external Python packages are required.

---

## 4. FAQ Dataset

The FAQ information is stored in:

```text
faq_dataset.csv