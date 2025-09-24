# 🚀 Selenium Python Automation: Swag Labs Login & Link Count

Automated login testing for Swag Labs using Python + Selenium. The script logs in, validates the title, counts `<a>` links, and prints them. A beginner-friendly project to practice browser automation, element handling, and test validation in real-world scenarios.  

[![Python](https://img.shields.io/badge/Python-3.x-blue)](https://www.python.org/)
[![Selenium](https://img.shields.io/badge/Selenium-Automation-green)](https://www.selenium.dev/)
[![License](https://img.shields.io/badge/License-MIT-yellow)](LICENSE)

## 📌 Project Overview
This project demonstrates **automated login testing** for the [Swag Labs Demo Website](https://www.saucedemo.com/) using Python and Selenium. It also counts and prints all available links after login.

**Key Features:**
- Launches Chrome browser automatically  
- Logs in using sample credentials (`standard_user` / `secret_sauce`)  
- Verifies the page title for validation  
- Counts and prints all `<a>` links on the page  
- Gracefully closes the browser after execution  

## 🛠️ Quick Setup
git clone https://github.com/your-username/SwagLabs-Selenium-Automation.git
cd SwagLabs-Selenium-Automation
pip install selenium
# Download ChromeDriver (ensure version matches your Chrome browser)
# Place chromedriver.exe in a known directory and update the path in the script
python swaglabs_login.py
