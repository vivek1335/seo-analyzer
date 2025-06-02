# SEO Analyzer

SEO Analyzer is a Python tool that helps you analyze and improve the SEO performance of a given website. This script fetches the website's HTML content, extracts key SEO elements such as meta tags, headings, images, and checks for the existence of `robots.txt` and `sitemap.xml` files.

## Features

- **Meta Tags Analysis**: Extracts the title, description, and keywords from the meta tags.
- **Headings Structure**: Retrieves all headings (`h1`, `h2`, etc.) in the page to analyze the page's content structure.
- **Images Analysis**: Identifies images missing the `alt` attribute, which is important for SEO and accessibility.
- **Robots & Sitemap Check**: Checks for the presence of `robots.txt` and `sitemap.xml` files, which are crucial for search engine crawling.

## Requirements

Before running the script, you need to install the following dependencies:

- `requests`: For making HTTP requests.
- `beautifulsoup4`: For parsing HTML and extracting useful information.
- `lxml`: For faster HTML parsing.

You can install these dependencies using `pip`:

```bash
pip install requests beautifulsoup4 lxml
