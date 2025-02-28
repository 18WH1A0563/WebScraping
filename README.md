# Job Scraper using Python

This project is a simple web scraper that extracts job postings from a webpage and saves the data in a CSV file. It uses Python and the following libraries:
- requests – to send HTTP requests and retrieve webpage content
- BeautifulSoup – to parse and extract job details from the HTML
- csv – to store the extracted job postings
- datetime – to manage timestamps
- time – to introduce delays for better request handling

Features
- Generates a search URL dynamically based on job position and location
- Extracts job title, company name, and location from job postings
- Saves the extracted data in a structured CSV format
- Uses exception handling to manage missing data
