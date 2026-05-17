- MJ Motown Era (Sentiment and Audio Feature Analysis):
This project analyses Michael Jackson's Motown era discography (1972-1975) across two dimensions: audio features and lyrical emotion. The goal is to explore a compelling tension in his early work — the music sounds happy, but the lyrics tell a different story.

- Background:
Michael Jackson's Motown years produced some of his most iconic early work. This project takes a data-driven look at 42 songs from this era, combining structured audio data with NLP-based lyrical analysis to uncover patterns in how the music was constructed emotionally.

- What this project does:
Exports Spotify playlist data via Exportify (danceability, energy, valence, acousticness, tempo, and more), fetches lyrics for each song using the Genius API, runs emotion classification on lyrics using a pre-trained HuggingFace transformer model (RoBERTa), and visualises mood, popularity, and emotional breakdown across the full discography.

- Key findings:
Sadness is the dominant lyrical emotion with 14 out of 42 songs classified as sad. Despite this, average valence sits at 0.66, meaning the music itself sounds upbeat and positive. This mismatch is consistent with Motown's signature style: emotional depth wrapped in bright, danceable production. The most popular song is Ben with a score of 70, and the least popular is Johnny Raven at 38.

- Files:
1. Motown_Era_MJ_token_hidden.ipynb is the main analysis notebook. Motown_Era.csv contains the raw Spotify playlist data exported via Exportify.
2. Motown_Era_with_lyrics.csv is the dataset with lyrics added.

- Tools and Libraries:
1. Python,
2. Pandas,
3. Matplotlib,
4. Exportify,
5. Genius API,
6. lyricsgenius,
7. HuggingFace Transformers.

- Setup:
To run this notebook locally, clone the repository, create a genius_token.txt file with your Genius API token in the format GENIUS_ACCESS_TOKEN=your_token_here, install dependencies with pip install pandas matplotlib lyricsgenius transformers python-dotenv, then run the notebook.
