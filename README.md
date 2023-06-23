## BBC Topic Scraper

This is a Python script that scrapes topic-related articles from the British Broadcasting Corporation (BBC) website and saves the details in a CSV file. The script allows users to specify a topic and the number of pages to scrape.

## Prerequisites

Before running the script, ensure that you have the following installed:

- Python
- requests library
- pandas library
- BeautifulSoup library

## Usage

1. Clone the repository to your local machine.
2. Open a terminal or command prompt and navigate to the project directory.
3. Run the script using the following command:

   ```shell
   python scraper.py
   ```

4. Enter the topic you want to search for when prompted.
5. Enter the number of pages you want to scrape.
6. The script will start scraping the BBC website and display the completion status of each page.
7. Once completed, the script will save the scraped data as a CSV file named `topic_details_bbc_<page_number>.csv`, where `<topic>` is the topic entered and `<page_number>` is the number of pages scraped.

Note: The script assumes that you have a stable internet connection and that the BBC website structure remains unchanged. Any changes to the website structure may require modifications to the script.

## Dataset

The script generates a DataFrame containing the following details for each article:

Title: The title of the article
Description: The description of the article
Programs: The related programs associated with the article
Reference URL: The URL of the article for reference

The DataFrame is saved as a CSV file for further analysis or processing.

Feel free to modify the script or integrate it into your own projects as needed.

## Repository

The project is available on GitHub under the project name "BBC Topic Scraper". You can access the repository [BBC_WS](https://github.com/Pranay62/BBC_WS/). The repository contains the Python script, sample output, and any additional resources or documentation related to the project.
