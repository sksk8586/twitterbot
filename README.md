
# Internet Speed Complaint Twitter Bot

# Overview
This Python script automates the process of checking your internet speed using Speedtest.net and tweeting a complaint to your internet service provider (ISP) on Twitter if the actual speed falls below the promised speed. It uses the Selenium  to interact with web elements on Speedtest.net and Twitter, automating the entire process.

# Features
Speed Test:
- The script uses the Speedtest.net website to measure your current download and upload speeds.

Twitter Login:
- The script navigates to Twitter's login page and logs in using the provided Twitter username and password.
  
Complaint Tweet:
- If the actual internet speed is below the promised speed, a complaint tweet is composed automatically.
- The tweet mentions the specified internet service provider (ISP) and includes details about the actual and promised speeds.

# Prerequisites
Before using the script, ensure the following:
- Python: Make sure Python is installed on your system.
- Selenium: Install the Selenium library using pip install selenium.
- ChromeDriver: Download the ChromeDriver executable from the official website.
  
# Configuration
Customize the code by replacing the placeholders with your specific information, such as promised upload/download speeds, Twitter username, password, and internet service provider.

# Usage
Run the script using the command python script_name.py.
The script will open a Chrome browser, perform a speed test, log in to Twitter, and tweet a complaint if the internet speed is below the promised speed.
