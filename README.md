# 🛍️ Amazon Product Web Scraper (RSelenium + R)

This project is a browser automation tool built using **RSelenium** in **R** that scrapes product data from Amazon. It collects key details such as:

- ✅ Product Title
- 💵 Price

The goal is to create a structured dataset for analysis or downstream ML/NLP applications.

---

## 🚀 Features

- Uses **RSelenium** to control a browser and navigate Amazon search pages.
- Handles dynamic web elements and extracts key product info.
- Saves the results to a **CSV file** for further use or analysis.
- Built with modular, reusable R code for easy updates or customization.

---

## 📂 Output Sample

| Product Title              | Price    | Rating |
|---------------------------|----------|--------|
| Example Product Name      | $29.99   | 4.5    |

_(Optional: Add a screenshot or real CSV sample in the `/output/` folder)_

---

## 🛠️ Tech Stack

- **Language:** R  
- **Libraries:** RSelenium, dplyr, rvest (if used)  
- **Export:** CSV  
- **Scraping Target:** Amazon.ca/.com product listings

---

## 📌 How to Run

1. Install RSelenium and dependencies:
   ```r
   install.packages("RSelenium")
