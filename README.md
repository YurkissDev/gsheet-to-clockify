## gsheet-to-clockify

📄 Project Description — gsheet-to-clockify

gsheet-to-clockify is a Python utility that automates the process of transferring time entries from a Google Sheet to Clockify via their public APIs.

This tool is useful for individuals or teams who prefer logging time in a spreadsheet and want to sync that data with Clockify for proper time tracking and reporting.

🔧 Features
- Reads time entries from a Google Sheet
- Creates corresponding time entries in Clockify
- Supports fields like start time, end time, project, description
- Simple configuration using a .env file
- Command-line output with success/error logging

🚀 Tech Stack
- Python 3.x
- gspread (Google Sheets API wrapper)
- python-dotenv (for environment variable management)
- requests (for interacting with Clockify API)

📁 Example Sheet Format

| Date       | Start | End   | Project   | Description                |
| ---------- | ----- | ----- | --------- | -------------------------- |
| 2025-07-10 | 09:00 | 10:30 | MyProject | Fixing login functionality |

📦 Getting Started
1. Clone this repository
2. Set up your .env file with Google and Clockify credentials
3. Run main.py