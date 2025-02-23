# AI- OTH Webscraping (Python Data Acquisition Framework Using Web Scraping)

## Description
This project introduces an automated web scraping tool developed in Python to extract and organize information from websites. It is designed to collect hyperlinks, image URLs, and textual content, storing them efficiently in an SQLite database. The tool also provides an option to save images to a specified location.

---

## Features
- Automated Web Scraping: Extracts hyperlinks, image URLs, and text content from a primary URL.
- Data Organization: Saves extracted data in a structured SQLite database, named after the domain.
- Image Storage: Option to download images to a user-specified directory, organized by domain name.
- Error Handling: Comprehensive error handling for network issues, HTML parsing errors, and database interactions.
- Scalable Design: Efficiently handles multiple pages within the same domain.

---

## Technologies Used
- **Python 3**
- `BeautifulSoup` for HTML parsing
- `requests` for HTTP requests
- `SQLite` for data storage
- `os` and `hashlib` for file management
