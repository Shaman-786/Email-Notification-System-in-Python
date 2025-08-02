# 📬 Email Notification System in Python

This project is a simple email notification system built with **Python** and **SQLite**. It allows sending email alerts to all registered users whenever a new update or activity is triggered.

## 🚀 Features

- Store and manage registered users with email addresses
- Add new update/notification messages
- Send emails to all users when a new update is added
- Prevent duplicate notifications using a tracking system
- Easy to set up and extend

## 🧱 Project Structure

email-notification-system/
├── main.py # Main script to send notifications
├── add_update.py # Script to add a new update
├── database.py # Database operations
├── email_sender.py # Email sending logic
├── config.py # Email credentials and settings
├── requirements.txt # Python package requirements
├── database.db # SQLite database (auto-created)
└── README.md # Project documentation


## 📦 Requirements

- Python 3.x
- A Gmail account with **App Password** enabled
- `smtplib`, `sqlite3`, and `schedule` (optional)

## 📥 Installation

1. Clone the repo:
   ```bash
   git clone https://github.com/shaman-785/email-notification-system-python.git
   cd email-notification-system-python
