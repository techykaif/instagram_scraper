## Instagram Scraper with Selenium

This Python script uses Selenium to automate logging into Instagram and scraping user profile data. The script extracts specific spans from a user's profile and saves them as a JSON file.

## Features
- Automated Instagram Login**: Logs into Instagram using provided credentials.
- Profile Scraping**: Extracts specific span texts from user profiles.
- JSON Output: Saves the extracted data in a JSON file.
- Popup Handling: Handles common Instagram popups during the scraping process.
- Developer Tools Integration**: Automatically opens Chrome Developer Tools (optional).
---
## Prerequisites

### 1. Python 
Ensure Python is installed on your system (Python 3.7+ recommended).

### 2. Chrome Browser
Google Chrome must be installed on your machine.

### 3. WebDriver
The script uses the `webdriver_manager` library to manage the Chrome WebDriver.

---

## Setup and Usage

### 1. Clone the Repository
```bash
git clone https://github.com/techykaif/instagram_scraper
```

### 2. Install Dependencies
Run:
```bash
pip install -r requirements.txt
```

### 3. Run the Script
Execute the script:
```bash
python instagram.py
```

### 4. Provide Instagram Credentials
Enter your Instagram username and password when prompted.
Use a Fake Instagram Account.

### 5. Start Scraping
- Enter the username of the Instagram profile you want to scrape.
- The script will extract span data and save it to a file named `profile_<username>.json`.

### 6. Exit the Script
Type `exit` to terminate the script.

---

## Example Output
Sample JSON output:
```json
[
    "Extracted span text 1",
    "Extracted span text 2",
    "Extracted span text 3"
]
```

---

## Logging
The script logs all events, including errors, to the console for easy debugging.

---

## Notes
- **Headless Mode**: The script runs in headless mode for performance. Remove the `--headless` option to visualize browser interactions.
- **JavaScript Execution**: JavaScript is used to extract spans. Adjust the indices in the script if needed.

---

## License
This project is licensed under the MIT License. Feel free to use and modify as needed.
```

Let me know if you want to make any modifications!
