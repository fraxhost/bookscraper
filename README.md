# Bookscraper

A Scrapy project to scrape book data from a website.

## Installation

Ensure you have Python installed, then install Scrapy:

```sh
pip install scrapy
```

## Scrapy Commands

### Get List of Available Scrapy Commands

```sh
scrapy
```

### Create a Scrapy Project

```sh
scrapy startproject bookscraper
```

### Generate a Spider

```sh
scrapy genspider bookspider books.toscrape.com
```

### Run the Scraper

```sh
scrapy crawl bookspider
```

### Save Scraped Data to a File

```sh
scrapy crawl bookspider -o bookdata.csv
```

## Project Structure

```
bookscraper/
│── bookscraper/             # Project directory
│   ├── spiders/             # Contains your web crawlers
│   │   ├── bookspider.py    # Example spider
│   ├── settings.py          # Scrapy settings
│── scrapy.cfg               # Scrapy configuration file
```

## Usage

1. Navigate to the project directory:
   ```sh
   cd bookscraper
   ```
2. Run the scraper using one of the commands above.

## Requirements

- Python 3.x
- Scrapy

## License

This project is licensed under the MIT License.
