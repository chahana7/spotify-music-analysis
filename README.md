# Spotify Audio Features Analysis (Beginner API Project)

This project explores the audio characteristics of top tracks using the **Spotify Web API**. Using the `spotipy` library, I pulled data from a real Spotify playlist and analyzed track popularity, energy, danceability, and more.

>  Note: This was my first project using an API, and while the code isn’t perfect, it reflects my early efforts to work with real-world data and build Python skills.

---

## Project Overview

- Pulled data from the Spotify “Top 50 Global” playlist using the Spotify Web API
- Extracted key track information: name, artist, popularity, and audio features
- Visualized relationships like:
  - Danceability vs. Energy
  - Top 10 Most Popular Tracks
  - Correlation Heatmap of audio features

---

## Tools Used

- Python
- pandas
- matplotlib
- spotipy (Spotify Web API wrapper)
- seaborn (for cleaner charts)

---

## API Access Setup

To replicate this project, you’ll need Spotify API credentials.

1. Create a Spotify Developer account → https://developer.spotify.com/dashboard/
2. Create an app and get:
   - **Client ID**
   - **Client Secret**
3. Save them in a `.env` file (or set them as environment variables):

```env
SPOTIPY_CLIENT_ID=your_client_id
SPOTIPY_CLIENT_SECRET=your_client_secret
SPOTIPY_REDIRECT_URI=http://localhost:8888/callback

