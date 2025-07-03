# Instagram Caption Scraper & Sentiment Analyzer

This project scrapes Instagram user data (including post captions, video URLs, likes, comments, etc.) and performs **sentiment analysis** on the post captions using `TextBlob`.

## Features

- Scrapes public Instagram profile data using Selenium.
- Extracts captions, likes, comments, locations, and video URLs.
- Analyzes the sentiment (Positive, Negative, Neutral) of post captions.
- Outputs structured data in a dictionary format.

## Requirements

Install the required Python libraries:

```bash
pip install requests textblob selenium

Also, make sure you have:

✅ Google Chrome installed

✅ ChromeDriver installed and added to your system PATH
🔗 Download ChromeDriver

▶️ How to Use
Clone this repository or open the notebook directly in Jupyter Notebook or Google Colab

Run all cells step by step

The notebook will:

Open a Chrome browser via Selenium

Access the public Instagram profiles (e.g. taylorswift, bellahadid, etc.)

Extract captions, likes, comments, and more

Analyze caption sentiment

Print the structured output using pprint
