# GitHub Topic Scraper

A Node.js script that scrapes GitHub topic pages, fetches repositories under those topics, and retrieves their associated issues, saving the issues' links in a PDF.

## Features

- **Scrapes GitHub topics:** Utilizes the power of web scraping to fetch details of GitHub topics.
- **Fetches repositories:** Gathers repositories associated with a given topic.
- **Retrieves issue links:** Extracts issue links for the fetched repositories.
- **Saves in PDF:** The extracted issue links are saved in PDF files, organized by topics.

## Prerequisites

Before you begin, ensure you have the following installed:

- [Node.js](https://nodejs.org/)
  
Install the necessary Node modules with:

```bash

npm install request cheerio pdfkit

## Usage

1. **Clone the repository:**
   git clone [your-repo-link]

2. **Navigate to the project directory:**
   cd [your-repo-directory]
3. Run the script:
   node main.js

```bash

Output
The script works as follows:

Creates a directory for each topic.
Within each directory, a PDF file for each repository is created containing its issues' links.
Important Notes
This script performs web scraping. It's essential to respect GitHub's robots.txt file and terms of service.
If GitHub updates its DOM structure, web scraping selectors may require updates.
License
This project is licensed under the MIT License.

Contributing
We welcome contributions! For major changes, kindly open an issue first to discuss what you'd like to change.

