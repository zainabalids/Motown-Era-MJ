MJ Motown Era (Spotify Data Analysis): Analysis of Michael Jackson's Motown era discography using Spotify audio data and Genius lyrics.

What this project does:
- Exports Spotify playlist data using Exportify (danceability, energy, valence, etc.)
- Fetches lyrics using Genius API
- Runs emotion classification on lyrics using a HuggingFace model
- Visualizes mood, popularity, and emotional breakdown of the playlist

Key findings:
- Sadness is the dominant lyrical emotion (14/42 songs)
- Despite sad lyrics, valence is high (avg 0.66) — the music sounds happy
- Most popular song: Ben (score: 70)
- Least popular: Johnny Raven (score: 38)

Files:
- `Motown_Era_MJ_token_hidden.ipynb` — main analysis notebook
- `Motown_Era.csv` — raw Spotify data
- `Motown_Era_with_lyrics.csv` — data with lyrics added

Tools used:
- Python, Pandas, Matplotlib
- Spotify API, Genius API
- HuggingFace transformers (emotion classifier)
