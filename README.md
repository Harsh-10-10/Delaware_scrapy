# 🕸️ Bid Data Scraping

## 📌 Objective

The primary goal of this project is to extract structured bid-related data from a target website. The data is collected from both the **main bid listing table** and the **individual bid detail pages**.

---

## 📄 Data Extraction Details
### 🔹 From Main Table (for each bid in **Open**, **Recently Closed**, and **Awarded** sections):

- `Contract Number`
- `Contract Title`
- `Open Date`
- `Deadline Date`
- `Agency Code`
- `UNSPSC`
- `Current Bid Status` (Open, Recently Closed, Awarded)

### 🔹 From Bid Detail Page (for each bid):

- `Full Bid Title/Header`
- `Solicitation Ad Date`
- `Deadline for Bid Responses`
- `Contact Name` (if available)
- `Contact Email` (if available)
- `List of all Supporting Bid Document URLs`
- `Any other text information present on the detail page`

---

## 🛠️ Tools & Libraries Used

- `Selenium` – for browser automation and dynamic content scraping  
- `Openpyxl` – for writing extracted data to Excel files  
- `os` – for file and directory operations  
- `logging` – for tracking script execution and errors  
- `WebDriver` – for controlling browser sessions  
- `time` – for managing delays and wait times  
- `pandas` – for data manipulation and structuring

---

## 📂 Main Script

You just need to run the Main.py file

