# ScrapeSummarize

# Webpage Summarizer Using OpenAI GPT-4

This project demonstrates how to summarize the content of any webpage using OpenAI's GPT-4 model. The summarizer extracts the text from a webpage, removes irrelevant elements (like scripts and styles), and generates a concise summary using GPT-4.

## Features
- **Web Scraping**: Uses `BeautifulSoup` to extract and clean webpage content.
- **OpenAI Integration**: Connects to OpenAI's GPT-4 model for summarization.
- **Markdown Output**: Displays summaries in a clean, markdown format.

## How It Works
1. **Webpage Extraction**: The `Website` class fetches and parses the webpage content, removing unnecessary elements like scripts, styles, and images.
2. **Summarization**: The `summarize` function sends the cleaned content to OpenAI's GPT-4 model, which generates a concise summary.
3. **Markdown Display**: The `display_summary` function renders the summary in markdown format for easy readability.

## For more details, check out the full notebook  [here](https://colab.research.google.com/github/MohHasan1/ScrapeSummarize/blob/main/ScrapeSummarize.ipynb).
