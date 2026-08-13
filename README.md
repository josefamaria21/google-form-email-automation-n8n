# Google Form Email Automation using n8n

An automated registration confirmation system built using **Google Forms, Google Sheets, n8n, and Gmail**.

When a user submits the registration form with their name and email address, the workflow automatically detects the new response and sends a personalized confirmation email to the registered email address.

## 🚀 Project Overview

This project demonstrates how a simple registration process can be automated without writing traditional application code.

### Workflow

Google Form
↓
Google Sheets
↓
n8n Google Sheets Trigger
↓
Gmail
↓
Personalized Confirmation Email

## ✨ Features

- Collects user registration details through Google Forms
- Automatically stores responses in Google Sheets
- Detects newly added registrations using an n8n trigger
- Sends an automated confirmation email through Gmail
- Uses the registered user's name to personalize the email
- Uses the submitted email address as the recipient
- Runs automatically once the n8n workflow is published and active

## 🛠️ Technologies Used

- **Google Forms** – Registration form
- **Google Sheets** – Stores form responses
- **n8n** – Workflow automation
- **Gmail API** – Sends confirmation emails
- **Google OAuth 2.0** – Authentication

## 📋 Registration Data

The form collects:

- Name
- Email Address

Example:

| Name | Email |
|------|-------|
| Jo | user@example.com |

## ⚙️ How It Works

1. A user opens the Google Form.
2. The user enters their name and email address.
3. The form response is automatically added to Google Sheets.
4. The n8n Google Sheets Trigger detects the newly added row.
5. n8n extracts the user's name and email address.
6. The Gmail node creates a personalized confirmation message.
7. The confirmation email is sent automatically to the user.

## 📧 Example Email

**Subject:**

`Jo - Welcome!!!`

**Message:**

> Hi Jo,  
> You have successfully registered.  
> Thank you for registering!

## 🔐 Security & Privacy

This repository intentionally does **not** contain:

- Google Form links
- Google Sheet links
- Client IDs
- Client secrets
- OAuth access tokens
- Gmail credentials
- Personal email addresses
- Private registration data

All credentials and private resources are stored securely inside n8n and Google Cloud.

> **Important:** Never upload OAuth client secrets, access tokens, private Google Sheet links, or other credentials to GitHub.

## 📌 Project Purpose

The purpose of this project is to demonstrate a practical **no-code/low-code automation workflow** that can be used for:

- Event registrations
- Workshop registrations
- Course registrations
- Newsletter sign-ups
- Appointment confirmations
- Customer registration systems

## 🔮 Future Improvements

Possible improvements include:

- Custom HTML email templates
- Registration numbers
- Duplicate email detection
- Automated welcome messages
- Admin notifications
- Registration confirmation IDs
- Integration with other communication platforms
- AI-generated personalized emails

## 👩‍💻 Author

**Jo**

Built as a practical automation project using n8n and Google services.
