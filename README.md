# Spaceflight News API & WordCloud Generator

A simple Data Science workflow in Python that fetches spaceflight news articles using an external API, formats the structured data using **pandas**, and generates a **WordCloud** visualization based on the news summaries.

## Project Overview
- **Data Source:** [Spaceflight News API v4](https://api.spaceflightnewsapi.net/v4/articles/)
- **Libraries Used:** `requests`, `pandas`, `matplotlib`, `wordcloud`, `nltk`
- **Output:** Structured pandas DataFrame & WordCloud image representation of space news keywords.

## Features
1. Automatically downloads required NLTK resource packages (`stopwords`, `wordnet`, `punkt`).
2. Fetches real-time spaceflight articles via REST API.
3. Structures JSON payloads into a pandas DataFrame (12 columns: `id`, `title`, `authors`, `url`, `image_url`, `news_site`, `text`, `published_at`, `updated_at`, `featured`, `launches`, `events`).
4. Aggregates summary text and builds a visual WordCloud map.

## How to Run
1. Clone this repository:
   ```bash
   git clone [https://github.com/ichameisyak-sudo/Text-Processing-.git](https://github.com/ichameisyak-sudo/Text-Processing-.git)
