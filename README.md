# Cookie Clicker Web Scraping Using Selenium

This repository contains a Python script that automates gameplay for the Cookie Clicker web game using Selenium WebDriver.

## Features
- Automatically clicks the cookie to generate points.
- Purchases upgrades and items to increase cookie production.
- Runs on a loop to continuously optimize gameplay.

## Requirements
Ensure you have the following installed:
- Python 3.x
- Google Chrome or any Chromium-based browser
- ChromeDriver (Ensure it matches your Chrome version)


## Installation

1. Clone this repository:
   ```sh
   git clone https://github.com/SalonRaut7/Cookie-Clickers-WebScraping-Using-Selenium.git
   cd Cookie-Clickers-WebScraping-Using-Selenium
   ```

2. Install selenium:
   ```sh
   pip install selenium
   ```

3. Ensure ChromeDriver is set up correctly and added to your system's PATH.

## Usage

Run the script with:
```sh
python main.py
```

The script will start playing Cookie Clicker automatically by clicking the main cookie and purchasing available upgrades.

## Configuration
- Modify the script to adjust clicking speed or upgrade purchase logic as needed.
- Update ChromeDriver if needed to match your Chrome version.

## Troubleshooting
- If the script fails to locate elements, ensure your browser and ChromeDriver versions are compatible.
- Adjust `time.sleep()` intervals if elements are loading too slowly.
- Check for website updates that may affect element IDs or class names.

