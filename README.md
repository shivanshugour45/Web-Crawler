# Web Scraping Job Data from Naukri.com

This is a Python script that demonstrates web scraping job data from Naukri.com using Selenium and BeautifulSoup libraries. The script navigates through multiple pages of job listings, extracts relevant information for each job, and saves the data to a CSV file.

## Prerequisites

Before running the script, ensure that you have the following dependencies installed:

- Selenium (`pip install selenium`)
- BeautifulSoup (`pip install beautifulsoup4`)
- pandas (`pip install pandas`)

In addition, you will need to download the appropriate web driver for your browser. This script uses the Chrome WebDriver, which can be downloaded from the following link: [ChromeDriver](https://sites.google.com/a/chromium.org/chromedriver/)

Make sure to place the downloaded WebDriver in the "Selenium" directory or update the path accordingly in the script.

## Usage

1. Clone the repository to your local machine or download the script directly.
2. Install the required dependencies mentioned in the "Prerequisites" section.
3. Make sure the Chrome WebDriver is placed in the "Selenium" directory or update the path to the WebDriver in the script.
4. Run the script and wait for it to scrape job data from Naukri.com.
5. Once the script completes, a CSV file will be generated in the "data" directory with the naming convention `naukri_<current_date>.csv`.
6. You can open the CSV file using any spreadsheet software like Microsoft Excel or Google Sheets to view the extracted job data.

**Note:** The script currently scrapes data from a maximum of 5 pages. You can adjust this limit by modifying the condition within the `if page == 5` block in the script.

## Disclaimer

Please note that web scraping may be against the terms of service of certain websites. Make sure to review and comply with the website's terms of service and scraping policy before using this script. The purpose of this script is solely educational and for personal use.

**Use at your own risk. The author assumes no responsibility or liability for any misuse or damage caused by this script.**
