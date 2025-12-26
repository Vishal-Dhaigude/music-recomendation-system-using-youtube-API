![Screenshot (262)](https://github.com/user-attachments/assets/75d36b08-7406-4241-8baf-cad35ddf3e7a)
![Screenshot (263)](https://github.com/user-attachments/assets/13919c15-df4a-4969-be6a-686127d4d768)
![Screenshot (264)](https://github.com/user-attachments/assets/7067fae5-e91d-4d82-8ed6-c7abf70e7e5d)
![Screenshot (265)](https://github.com/user-attachments/assets/63b03fb0-52cb-4581-8644-d6c9b9260382)
🎵 Music Recommendation System using YouTube API

A mood-based music recommendation system that suggests songs and playlists using the YouTube Data API. The system recommends music based on the user’s selected mood, helping users discover relevant and personalized tracks effortlessly.

🚀 Project Overview

This project uses the YouTube API to fetch music content and recommend songs according to different moods such as Happy, Sad, Relaxed, Energetic, etc.
It focuses on improving user experience by providing emotion-aware music suggestions.

🎯 Features

🎧 Mood-based music recommendations

🔍 Fetches real-time songs using YouTube Data API

⚡ Fast and dynamic song suggestions

🧠 Simple logic for mood classification

💻 User-friendly interface (CLI / Web-based if applicable)

🛠️ Tech Stack

Programming Language: Python

API: YouTube Data API v3

Libraries:

google-api-python-client

requests

json

Tools: VS Code, GitHub

📌 How It Works

User selects a mood

The system maps mood to predefined music keywords

YouTube API fetches relevant videos/songs

Recommended music is displayed to the user

📂 Project Structure
music-recommendation-system/
│
├── main.py
├── youtube_api.py
├── config.py
├── requirements.txt
├── README.md

🔑 Setup & Installation

Clone the repository:

git clone https://github.com/Vishal-Dhaigude/music-recomendation-system-using-youtube-API.git


Install required libraries:

pip install -r requirements.txt


Get a YouTube API Key from Google Developer Console

Add your API key in config.py

Run the project:

python main.py

📊 Example Moods Supported

😊 Happy

😔 Sad

😌 Relaxed

⚡ Energetic

💖 Romantic

🌟 Use Cases

Personalized music discovery

Mood-based entertainment apps

Beginner-friendly API integration project

Recommendation system learning project

📈 Future Enhancements

Add ML model for mood detection

Integrate sentiment analysis

User login & history-based recommendations

Spotify API integration
