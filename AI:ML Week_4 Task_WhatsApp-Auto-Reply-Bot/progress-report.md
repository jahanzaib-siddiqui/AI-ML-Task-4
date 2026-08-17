
---

# `progress-report.md`

```markdown
# Progress Report

## Project Title

**WhatsApp Auto-Reply Bot – Automated Reply Engine**

---

## 1. Project Objective

The objective of this project was to build a simple automated reply system that can read a user's message, identify the most relevant FAQ using keyword matching, and return an appropriate automated response.

---

## 2. Work Completed

The following tasks have been completed:

- Created a predefined FAQ dataset.
- Stored the FAQ information in a CSV file.
- Added multiple FAQ categories.
- Added keywords for each FAQ category.
- Implemented CSV dataset loading in Python.
- Implemented user input through the terminal.
- Implemented keyword-based message matching.
- Implemented matching-score logic to identify the most relevant FAQ.
- Implemented automated FAQ responses.
- Implemented a default response for unknown questions.
- Implemented an `exit` option to close the chatbot.
- Tested the chatbot with multiple FAQ questions.
- Tested the chatbot with an unknown question.
- Prepared screenshots demonstrating the chatbot functionality.

---

## 3. FAQ Categories Implemented

The current FAQ dataset contains the following categories:

1. Working Hours
2. Contact Information
3. Services
4. Pricing
5. Registration
6. Internship Information
7. Support
8. Location
9. Payment Methods
10. Cancellation Policy

---

## 4. Technologies Used

The project uses:

- **Python** – Main programming language.
- **CSV** – Storage format for the FAQ dataset.
- **Regular Expressions (`re`)** – Used for basic message cleaning.
- **GitHub** – Project version control and submission.

---

## 5. Challenges Faced

### Challenge 1: Different Question Formats

Users can ask the same question in different ways.

For example:

```text
What are your working hours?
