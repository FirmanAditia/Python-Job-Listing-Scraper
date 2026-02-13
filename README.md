# Python-Job-Listing-Scraper

This project is a Python web scraper designed to extract job listings from the [Real Python Fake Jobs](https://realpython.github.io/fake-jobs/) website. It gathers key information from job cards and saves the data into a structured CSV file.

## Features

* **Data Extraction:** Scrapes Job Title, Company Name, Location, and Application URL.
* **Edge Case Handling:** Automatically handles missing data (e.g., missing location or company name) without crashing.
* **CSV Export:** Saves the scraped data into a `job_results.csv` file.
* **Clean Logic:** Uses explicit targeting of HTML elements using `BeautifulSoup`.

## Tools I Used

* **Python 3**
* **Requests** (Library for making HTTP requests)
* **BeautifulSoup4** (Library for parsing HTML)
* **CSV** (Built-in library for file handling)

## Output

The script generates a file named `job_results.csv` containing the following columns:
1.  `Job Title`
2.  `Company`
3.  `Location`
4.  `Apply Link`

## How to Run

1.  Open the `.ipynb` file in **Google Colab** or **Jupyter Notebook**.
2.  Ensure the required libraries are installed:
    ```python
    !pip install requests beautifulsoup4
    ```
3.  Run the code cells.
4.  Download the generated `job_results.csv` file.
