# News-website
# Flask News Application

This is a Flask-based web application that fetches and displays news articles from various sources using the News API. Users can search for news articles by keywords and view the latest top headlines.

## Features

- Display the latest top headlines from various news sources.
- Search for news articles by keywords.
- View news articles with relevant details such as title, description, and link.

## Prerequisites

- Python 3.x
- Virtual environment (optional but recommended)

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Shubhaaamm/News-website.git
   cd flask-news-app

2. Create and activate a virtual environment:
    python -m venv venv    source venv/bin/activate  # On Windows, use `venv\Scripts\activate`

3. Install the required packages:
```pip install -r requirements.txt

4. Replace 'YOUR_API_KEY_HERE' with your actual News API key in the app.py file:
    newsapi = NewsApiClient(api_key='YOUR_API_KEY_HERE')

5. Project Structure
- app.py: The main application file.flask-news-app/
├── templates/
│   └── home.html
├── app.py
└── requirements.txt


