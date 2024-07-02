# Historical BVC Quotes Scraper

This project is a web scraper designed to extract historical quotes from the Bolsa de Valores de Cabo Verde (BVC). The scraper is implemented in a Jupyter Notebook using BeautifulSoup4 and requests to gather data, and pandas for data manipulation and analysis.

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Data Storage](#data-storage)
- [Contributing](#contributing)
- [License](#license)

## Installation

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/historical-bvc-quotes-scraper.git
    cd historical-bvc-quotes-scraper
    ```

2. Create a virtual environment and activate it:

    ```bash
    python3 -m venv venv
    source venv/bin/activate  # On Windows use `venv\Scripts\activate`
    ```

3. Install the required packages:

    ```bash
    pip install -r requirements.txt
    ```

## Usage

To run the scraper, open the Jupyter Notebook `bvc_scraper.ipynb` and execute the cells. The notebook will scrape the historical quotes data, clean it, and perform some basic exploratory data analysis.


## Data Storage
The cleaned data is saved to a CSV file in the data folder for future analysis.

## License
This project is licensed under the MIT License. See the LICENSE file for details.