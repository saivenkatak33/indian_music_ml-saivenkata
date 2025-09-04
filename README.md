# indian_music_ml
a recommendation system for indian music
Indian Music ML - README

Project Description:
This project analyzes Indian music tracks using Spotify's Web API. It fetches track metadata, audio features, and performs analysis and visualization to understand musical characteristics and trends.

Prerequisites:
- Python 3.x
- spotipy library (Spotify API wrapper)
- pandas, plotly, seaborn, matplotlib for data manipulation and visualization

Spotify App Setup:
1. Register an app at https://developer.spotify.com/dashboard/applications
2. Note your Client ID, Client Secret
3. Set Redirect URI to http://127.0.0.1:8888/callback (or your preferred URL)
4. Enable scopes like user-library-read, playlist-read-private in your OAuth flow

Usage:
- Run the OAuth authorization code flow to get an access token with proper scopes.
- Use provided Python scripts/notebooks to fetch playlist data and audio features.
- Perform exploratory data analysis and generate visualizations.
- Extend project by building ML models for popularity prediction or clustering.

Limitations:
- Spotify API has rate limits; respect them by adding delays between calls.
- Some Spotify tracks/playlists might be restricted by region or permissions.
- Proper OAuth authentication is necessary to avoid access errors.

Contact:
For questions or help, reach out to the project maintainer.

Thank you for exploring Indian Music ML!
