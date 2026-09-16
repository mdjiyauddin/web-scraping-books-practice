# Web Scraping Practice — Books to Scrape

Practicing web scraping fundamentals using Python's `requests` and `BeautifulSoup` libraries on the practice site [books.toscrape.com](https://books.toscrape.com).

## What's done so far
- Used `requests` to download 50 pages of book listings (HTML) from the site's paginated catalogue
- Added error handling (checking status codes) and rate-limiting (`time.sleep`) between requests

## Next steps (in progress)
- Parse the downloaded HTML using `BeautifulSoup` to extract structured data: book title, price, rating, availability
- Store the extracted data in a pandas DataFrame / CSV
- Basic EDA on the scraped dataset (price distribution, rating patterns, etc.)

## Tools used
`requests`, `BeautifulSoup`, `pandas`
