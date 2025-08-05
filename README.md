# Web Scraping and NLP Project

This project focuses on web scraping and natural language processing (NLP) using Python tools such as `requests`, `BeautifulSoup`, and `spaCy`.

The article analyzed is an archived version of:
https://web.archive.org/web/20210327165005/https://hackaday.com/2021/03/22/how-laser-headlights-work/

## Project Tasks

1. **Scrape article HTML** using `requests` and `BeautifulSoup`.
2. **Save HTML to file** for reuse and reproducibility.
3. **Extract and clean text** using `.get_text()` from the parsed HTML.
4. **Analyze most frequent tokens** after removing stopwords, punctuation, and whitespace.
5. **Analyze most frequent lemmas** using spaCy’s lemmatizer.
6. **Score sentences** by how often they include common tokens and lemmas.
7. **Plot histograms** showing the distribution of sentence scores.
8. **Filter by nouns only** using `token.pos_ == "NOUN"` for more targeted analysis.

## Files in this Repository

- `web-scraping.ipynb` – Main notebook with all code and answers
- `web-scraping.html` – Exported HTML version of the notebook
- `article.html` – The raw article content scraped and saved
- `README.md` – This file

## Tools Used

- Python
- Jupyter Notebook
- requests
- BeautifulSoup4
- html5lib
- spaCy
- matplotlib
