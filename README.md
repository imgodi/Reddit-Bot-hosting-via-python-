🧠 Reddit Bot for Stock Sentiment Analysis & Market Insights
An automated Reddit bot designed to track real-time stock discussions on popular subreddits (like WallStreetBets) and extract trending tickers. Utilizes PRAW for Reddit data scraping and Yahoo-fin for live stock prices. Parses noisy Reddit comment streams and identifies tickers dynamically, maintaining a ranking system of the most-discussed stocks.

Tech Stack: Python, PRAW, Yahoo-fin, Heapq
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
