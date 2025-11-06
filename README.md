
# Automated Folder Email Sender

## Description
An automated Python script designed to send all files within a specified folder via email at a scheduled time. This tool simplifies file sharing by automatically dispatching files from a folder at predefined intervals or specific times, saving time and effort.

## Features
- Sends all files in a designated folder
- Scheduled to run at a specific time
- Supports multiple file types
- Easy configuration for email credentials and schedule

## Technologies Used
- Python 3.8+
- smtplib for sending emails
- email for composing email messages
- glob for file pattern matching
- os for file handling
- datetime for scheduling
- schedule (optional) for task scheduling

## Setup Instructions
1. Clone this repository to your local machine.
2. Install necessary dependencies (if any).
    You need Python installed on your system. No external libraries are required beyond the           standard library, but ensure your environment is set up.

3. Configure email credentials and folder path:  
  3.1 Set the environment variables EMAIL_SENDER, EMAIL_PASS, and EMAIL_RECEIVER with your              email address, app password, and recipient email, respectively.
  3.2 Update the folder_path variable in the script to the folder containing your files                 ("E:\GOVT_EXAM\ADMIT_CARD" by default).
4. Set the desired schedule time:  
    Use a task scheduler (like Windows Task Scheduler or cron) to run the script at your              preferred time.
5. Run the script:  
    Execute the Python script to automatically attach the latest files from the specified folder      and send them via email.
