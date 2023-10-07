# Web Scraping Wikipedia for a List of Largest Companies in the United States

This Python script scrapes data from a Wikipedia page to create a dataset of the largest companies in the United States by revenue. It uses the BeautifulSoup library to parse the HTML content of the Wikipedia page and extract the relevant table data. The extracted data is then converted into a pandas DataFrame and saved as a CSV file.

## Prerequisites

Before running the script, make sure you have the following prerequisites installed:

- Python (version 3.x)
- BeautifulSoup (`beautifulsoup4`) library
- Requests (`requests`) library
- Pandas (`pandas`) library

You can install these libraries using `pip`:

```bash
pip install beautifulsoup4 requests pandas
```

## Usage

1. Clone this repository to your local machine using `git clone` or download the code as a ZIP archive and extract it to a directory of your choice.

```bash
git clone https://github.com/your-username/web-scraping-wikipedia.git
```

2. Navigate to the project directory:

```bash
cd web-scraping-wikipedia
```

3. Open the Jupyter Notebook file (`Untitled0.ipynb`) in an environment that supports Jupyter Notebooks (e.g., Jupyter Notebook, Google Colab).

4. Run the code cells in the notebook one by one. The code will scrape data from the specified Wikipedia page and create a CSV file containing the list of largest companies in the United States by revenue.

5. You can find the output CSV file named `Companies.csv` in the specified output folder.

## Customization

You can customize the script by:

- Changing the URL (`url`) to scrape data from a different Wikipedia page with a similar table structure.
- Modifying the output file path to save the CSV file in a location of your choice.




