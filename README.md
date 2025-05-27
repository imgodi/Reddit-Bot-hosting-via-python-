# Reddit Bot for Stock Sentiment Analysis

Tracks trending stock tickers from Reddit's WallStreetBets and other subreddits, providing real-time rankings and price data.

## Features
- Extracts stock tickers from Reddit comments using `PRAW`
- Fetches live prices via `Yahoo-fin`
- Maintains top 5 trending stocks dynamically
- Parses noisy text streams for accurate ticker extraction

## Tech Stack
Python, PRAW, Yahoo-fin, Heapq

## How to Run
1. Clone the repository
2. Set up Reddit API credentials
3. Run `python main.py`
