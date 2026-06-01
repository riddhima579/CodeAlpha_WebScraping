# CodeAlpha Internship Task 1: Web Scraping Using Python

## Project Overview
This project was completed as part of the CodeAlpha Data Analytics Internship Program. The objective was to extract data from a website using Python web scraping techniques and store the collected information in a structured format for further analysis.

## Objective
To scrape book information from an online bookstore and save the extracted data into a CSV file using Python.

## Website Used
https://books.toscrape.com/

## Data Extracted
The following information was collected for each book:

- Book Title
- Price
- Rating

## Technologies & Libraries Used

- Python
- Requests
- BeautifulSoup (bs4)
- Pandas
- Google Colab

## Project Workflow

1. Sent an HTTP request to the target website using the Requests library.
2. Parsed the HTML content using BeautifulSoup.
3. Extracted relevant book information including title, price, and rating.
4. Stored the extracted data in a Pandas DataFrame.
5. Exported the cleaned data into a CSV file for future use.

## Output

Generated file:

- `books_data.csv`

The CSV file contains the scraped book data in a structured tabular format.

## Repository Contents

```text
CodeAlpha_WebScraping/
│
├── CodeAlpha_WebScraping.ipynb
├── books_data.csv
└── README.md
```

## Sample Output

| Title | Price | Rating |
|---------|---------|---------|
| Example Book | £51.77 | Three |
| Example Book 2 | £35.02 | Five |

*(Values shown above are for illustration purposes.)*

## Key Learning Outcomes

- Understanding web scraping fundamentals
- Working with HTML elements and tags
- Extracting and processing web data
- Data storage using Pandas
- Exporting data into CSV format
- Using Python libraries for data collection

## Note

GitHub may occasionally fail to render Jupyter Notebook previews and display an "An error occurred" message. If the notebook preview does not load, please download the notebook file and open it using:

- Google Colab
- Jupyter Notebook
- VS Code

The notebook file is complete and executable.

## Conclusion

This project successfully demonstrates the fundamentals of web scraping using Python. Data was extracted from a real website, processed efficiently, and stored in CSV format, showcasing practical skills in data collection and preprocessing.
