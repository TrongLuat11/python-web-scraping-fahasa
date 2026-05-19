# python-web-scraping-fahasa

# Fahasa E-commerce Web Scraper

## 📌 Project Overview
A Python-based automated web scraping tool designed to extract book information from the Fahasa e-commerce platform. It targets specific dynamic categories (such as Graphic Novels, Anime, Manga) and automatically parses details including titles, prices, images, and product URLs, saving the structured output into a `.json` file.

## 🛠️ Tech Stack & Libraries
- **Language:** Python 3.x
- **Web Automation:** `Selenium WebDriver` (for handling dynamic JavaScript-rendered content)
- **HTML Parsing:** `BeautifulSoup4`
- **Data Serialization:** `JSON`
- **Error Handling:** Built-in Python Exception Handling (`try-except` blocks)

## 🎯 Key Features & Technical Implementation
- **Dynamic Content Handling:** Effectively bypasses asynchronously loaded components using Selenium waiting mechanisms.
- **Robust Exception Handling:** Implemented customized try-except blocks to gracefully log faulty links without interrupting the entire crawling process.
- **Structured Data Output:** Data is cleaned, structured, and saved into a local JSON format, ready for any database insertion or data analysis.

## 📁 Repository Structure
- `crawdataa.ipynb`: Main Jupyter Notebook containing the scraper logic.
- `books.json`: Sample output of the extracted data.
- `README.md`: Project documentation.
