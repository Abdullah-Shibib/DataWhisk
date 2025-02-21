# DataWhisk

DataWhisk is a powerful tool designed to scrape Google Reviews using Playwright, perform sentiment analysis using a transformer-based model, and extract insights from customer feedback. The project leverages Playwright for web scraping and Python for data processing and visualization.

## Features

- **Automated Web Scraping:** Uses Playwright to extract reviews from Google.
- **Sentiment Analysis:** Applies a transformer-based model to evaluate the sentiment of reviews.
- **Aspect-Based Insights:** Categorizes reviews into aspects such as food, service, atmosphere, and pricing.
- **Keyword Extraction:** Identifies common terms in negative reviews for actionable improvements.
- **Data Visualization:** Generates word clouds and aggregates aspect ratings.

## Technologies Used

- **Playwright (Node.js):** Web scraping automation.
- **Python Libraries:**
  - **transformers:** BERT-based sentiment analysis.
  - **scikit-learn:** Keyword extraction.
  - **pandas:** Data manipulation.
  - **matplotlib & wordcloud:** Data visualization.

## Installation

Clone the repository:

```bash
git clone https://github.com/Abdullah-Shibib/datawhisk.git
cd datawhisk

npm install playwright

pip install transformers torch pandas scikit-learn matplotlib wordcloud

Usage
Scrape Reviews
Run the Playwright script to extract Google Reviews:

node scrape.js
This will save reviews in the googreviews folder as JSON files.

Analyze Reviews
Run the Python script to process and analyze the reviews:

python bert.py

This will generate:

Sentiment-based aspect ratings.
Word cloud visualization.
Improvement suggestions based on negative reviews.
Output Files
reviews_with_aspects.json: Reviews with sentiment-based aspect ratings.
aspect_rating_summary.json: Average ratings for each aspect.
improvement_suggestions.json: Keywords and improvement insights.

Ensure you replace any placeholders or specific paths as necessary to match your project's structure and requirements.
