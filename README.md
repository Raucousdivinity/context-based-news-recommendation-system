# Context-Based News Recommendation System

This project fetches and recommends news articles based on user preferences.

## Installation

1. Clone the repository:
   ```sh
   git clone <repo-url>
   cd news_recommendation_system
   ```

2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

## Usage

Run the script:
```sh
python news_recommendation.py
```

Enter a news category (e.g., technology, sports, business) when prompted, and the system will fetch relevant news articles.

## API Key Setup

This script uses the NewsAPI. Get an API key from [NewsAPI](https://newsapi.org/) and replace `"YOUR_API_KEY"` in `news_recommendation.py` with your actual key.

## Dependencies

- `requests` (for fetching news from the API)

## License

This project is open-source. Modify and use it as needed!
