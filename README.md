# Spotify-Analysis
**48.pdf** is summary report of findings. 

## Spotify Music Trends Analysis – Applied Machine Learning deep dive into Spotify's musical landscape

Conducted a comprehensive analysis of Spotify’s Top 200 global dataset (2017–2023, 7,457 unique songs) to uncover trends in audio features, genre evolution, and the impact of COVID-19 on music preferences. Applied exploratory data analysis and machine learning techniques to derive actionable insights on user listening patterns and song popularity.

### Key Contributions & Methods:

#### Exploratory Data Analysis: Examined temporal trends in audio features (danceability, energy, acousticness, valence, speechiness, loudness, instrumentalness) across years, seasons, holidays, and days of the week; identified shifts in music trends during COVID-19, including lower energy and danceability and increased acousticness.

#### Genre & Collaboration Insights: Mapped songs to genres (EDM, Pop, Hip-Hop/Rap, R&B, Latin) and analyzed collaborative effects, confirming that songs with multiple artists generally have higher popularity. Investigated genre distribution changes over time, e.g., surges in Pop and Latin songs post-2020.

#### Machine Learning & Clustering: Applied spectral clustering to classify songs by audio features, revealing connected clusters corresponding to genres (Pop, EDM, R&B, Hip-Hop/Rap) and confirming that numerical features alone only partially define genre boundaries.

#### Predictive Modeling: Used random forest regression to predict song popularity from audio features and collaboration metrics, identifying the relative importance of features, even though the model’s predictive performance was limited due to inherent variability in music popularity.

#### Visualization & Reporting: Created radar charts, heatmaps, bar plots, and correlation matrices to communicate nuanced trends and insights, highlighting seasonal effects, top songs, and genre-specific audio profiles.

### Impact & Insights:

* Revealed how seasonal, holiday, and daily listening patterns influence audio feature preferences, enabling data-informed playlist curation.

* Quantified the effect of collaboration on song popularity and explored the limitations of algorithmic genre classification.

* Provided insights for Spotify’s recommendation system by identifying patterns in user preferences and potential strategies for promoting seasonal and collaborative tracks.

### Technologies & Tools: Python (pandas, NumPy, matplotlib, seaborn), scikit-learn, spectral clustering, random forest regression, data visualization techniques.
