# Bulk-Email-Sender
Bulk Email Sender using Python

Overview
This script allows you to send bulk emails to a list of recipients using Python. It uses the smtplib library for sending emails and reads recipient information from a CSV file.

Prerequisites
Python installed on your machine (Download Python)
Access to an SMTP server (e.g., Gmail, Outlook) for sending emails

Setup
Clone the repository:


bash
pip install -r requirements.txt
Update email configuration:

SMTP_SERVER: Your SMTP server address.
SMTP_PORT: Your SMTP server port.
USERNAME: Your email address.
PASSWORD: Your email password or an App Password (for Gmail).
Prepare the CSV file:

Create a CSV file (recipients.csv) with columns Name and Email for each recipient.

csv
Name,Email
example@example.com

The script will read the recipients.csv file and send emails to each recipient.

Customization
Modify the email template in email_template.html.
Adjust the subject in send_emails.py.
Customize the CSV file structure as needed.
Notes
Use this script responsibly and ensure compliance with email sending regulations.
For security, consider using environment variables for sensitive information.

