
# 📚 BookScope — Web Scraping & Data Analysis

### Invoqe Data Analytics Internship | Task 1

BookScope is a Python-based web scraping and data analytics project developed as part of the **Invoqe Data Analytics Internship**. The project collects book information from [Books to Scrape](https://books.toscrape.com/), cleans and validates the extracted data, and performs exploratory analysis to discover useful insights.

The project demonstrates practical skills in **web scraping, data collection, data preprocessing, exploratory data analysis, and data visualization** using Python.

---

## 🎯 Project Objectives

- Collect book information from a publicly available website.
- Automate data extraction across multiple pages.
- Clean and validate the collected dataset.
- Store raw and cleaned data in CSV format.
- Analyze book prices, ratings, and availability.
- Generate visualizations to communicate findings.

---

## 🌐 Data Source

**Website:** [Books to Scrape](https://books.toscrape.com/)

Books to Scrape is a website designed for practicing web scraping. It contains book listings with information such as titles, prices, ratings, and availability.

### Data Collected

| Feature | Description |
|---|---|
| `title` | Name of the book |
| `price_gbp` | Book price in British pounds |
| `rating` | Customer rating represented by stars |
| `availability` | Stock availability status |
| `product_url` | Link to the book's product page |
| `category` | Category assigned during collection |

---

## 🛠️ Technologies Used

- **Python** — Main programming language
- **Requests** — Fetching web pages
- **BeautifulSoup** — Parsing HTML and extracting information
- **Pandas** — Data manipulation and cleaning
- **NumPy** — Numerical operations
- **Matplotlib** — Data visualization
- **Seaborn** — Statistical visualization
- **Jupyter Notebook** — Interactive development and documentation

---

## 📁 Project Structure

```text
Invoqe_BookScope/
│
├── BookScope_Web_Scraping.ipynb
├── requirements.txt
├── README.md
├── .gitignore
│
├── data/
│   ├── books_raw.csv
│   └── books_cleaned.csv
│
└── visualizations/
    ├── price_distribution.png
    ├── rating_distribution.png
    └── availability_distribution.png
```

---

## ⚙️ Installation and Setup

### 1. Clone the repository

```bash
git clone https://github.com/Avinash4926/Invoqe_BookScope.git
cd Invoqe_BookScope
```

### 2. Create a virtual environment

```bash
python -m venv .venv
```

### 3. Activate the virtual environment

**Windows PowerShell:**

```powershell
.venv\Scripts\Activate.ps1
```

### 4. Install dependencies

```bash
pip install -r requirements.txt
```

### 5. Launch Jupyter Notebook

```bash
python -m notebook
```

Open `BookScope_Web_Scraping.ipynb` and run the notebook cells in order.

---

## 🔄 Project Workflow

1. **Website Inspection**  
   Inspect the website structure and identify the HTML elements containing book information.

2. **Web Scraping**  
   Use Requests to retrieve pages and BeautifulSoup to extract book details.

3. **Pagination Handling**  
   Navigate through multiple pages to collect a larger dataset.

4. **Data Storage**  
   Save the collected data as `books_raw.csv`.

5. **Data Cleaning**  
   Remove duplicate records, handle missing values, standardize fields, and validate prices and ratings.

6. **Data Analysis**  
   Calculate descriptive statistics and examine price, rating, and availability patterns.

7. **Data Visualization**  
   Generate charts to present the analysis clearly.

---

## 📊 Analysis and Visualizations

The project explores the following questions:

- How are book prices distributed?
- Which ratings are most common?
- How many books are available or unavailable?
- What patterns can be observed in the collected book listings?

The notebook generates the following visualizations:

- **Price Distribution** — Histogram showing the distribution of book prices.
- **Rating Distribution** — Chart showing the frequency of each rating.
- **Availability Distribution** — Chart comparing availability statuses.

> The findings and numerical results are generated from the scraped dataset when the notebook is executed.

---

## 📂 Project Outputs

| Output | Description |
|---|---|
| `books_raw.csv` | Original data collected from the website |
| `books_cleaned.csv` | Cleaned and validated dataset |
| `visualizations/` | Generated charts |
| `BookScope_Web_Scraping.ipynb` | Complete scraping, cleaning, analysis, and visualization workflow |

---

## ▶️ How to Run

1. Install the required Python libraries.
2. Open `BookScope_Web_Scraping.ipynb` in Jupyter Notebook.
3. Run the cells from top to bottom.
4. The notebook collects the data, cleans it, performs analysis, and generates visualizations.
5. Review the saved CSV files and charts in the project folders.

---

## 📌 Key Skills Demonstrated

- Web scraping with Requests and BeautifulSoup
- HTML inspection and parsing
- Automated pagination
- Data collection and structuring
- Data cleaning and validation
- Exploratory data analysis (EDA)
- Statistical summaries
- Data visualization
- Jupyter Notebook documentation
- Git and GitHub project management

---

## ⚠️ Disclaimer

This project uses **Books to Scrape**, a website intended for practicing web scraping. The project is for educational and internship purposes. Please use responsible scraping practices, avoid excessive requests, and follow the website's terms and policies.

---

## 👨‍💻 Author

**Avinash**

B.Tech — Artificial Intelligence and Machine Learning

Developed as part of the **Invoqe Data Analytics Internship — Task 1**.

---

## ⭐ Acknowledgment

Thanks to **Invoqe** for providing the opportunity to apply practical data analytics skills through an internship project.
