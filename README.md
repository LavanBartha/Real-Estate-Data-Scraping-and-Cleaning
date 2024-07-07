# Real Estate Data Scraping and Parsing

This Python script scrapes real estate property data from Makaan.com for Bangalore city, using BeautifulSoup and requests libraries. It fetches details such as company name, project name, property type, RERA details, location coordinates, pricing, area details, construction status, and bathrooms count from multiple pages.

## Requirements

- Python 3.x
- BeautifulSoup (`bs4`)
- requests
- pandas

## Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/LavanBartha/Data-Scraping-and-Cleaning.git

2. Install dependencies:

   ```bash
   pip install beautifulsoup4 requests pandas

## Usage

1. Modify the url variable in the script (main.py) to change the Makaan.com URL if needed.

2. Adjust the page variable to specify the number of pages to scrape.

3. Run the script:

     python main.py
4. The script will output details of each property to the console and save the data to a CSV file (Dataset1.csv) (change the location as required).

## Output

The script generates a CSV file containing the following columns:

- Company_name
- Project_name
- Rooms
- Type
- Rera_Details
- latitude
- longitude
- Price
- Price_per_sft
- Area_in_sft
- Construction_Status
- Bathrooms


`https://github.com/LavanBartha/Data-Scraping-and-Cleaning`
