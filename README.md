# Catalogue scraper (Python)
Scrapes a product catalogue (title, price, rating, stock, URL) into CSV and Excel.
Demo target is books.toscrape.com, a public practice site. Polite delay, deduplicated output.

    pip install -r requirements.txt
    python scrape_books.py --pages 50 --delay 0.2 --out books
