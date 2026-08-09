 YouTube Search Scraper

A Python-based web scraping project that extracts search result metadata from YouTube using BeautifulSoup and requests.

 📌 Project Overview

This project automates the extraction of YouTube search result details without using the official YouTube Data API. It parses the HTML structure of YouTube search pages to collect key video metrics and output structured data.

✨ Features

- **Query-based Search:** Scrapes results for custom search keywords.
- **Metadata Extraction:** Collects key video details including:
  - Video Title
  - Video URL
  - View Count
  - Duration
  - Channel / Creator Info
  - Video Description / Snippet

 🛠️ Tech Stack

- **Language:** Python 3.x
- **Libraries:**
  - `requests` (for HTTP page retrieval)
  - `beautifulsoup4` (for HTML parsing)
  - `pandas` (for data manipulation and export)
  - `jupyter` (for interactive notebook execution)

 🚀 Getting Started

 Prerequisites

Ensure you have Python installed, then install the required dependencies:

```bash
pip install requests beautifulsoup4 pandas jupyter
