# The Evolution of Music from 2000 to 2023: A Spotify Data Analysis

This dataset has been retrieved from [Kaggle](https://www.kaggle.com/datasets/amitanshjoshi/spotify-1million-tracks). I chose this dataset because I love listening to music and wanted hands-on practice in a data analysis project. My goal is to explore what makes a song more popular and how the music industry has evolved over time.

## Visualization
You can view the interactive notebook [here](https://github.com/manulucena12/spotify-trends/blob/main/main.ipynb) on GitHub.  
If that doesn’t load properly, you can access the HTML version on my [portfolio](https://manulucenaportfolio.is-a.dev/spotify.html)  

## Features
This dataset contains the following columns:
- `artist_name`
- `track_name`
- `popularity`
- `genre`
- `year`
- **Audio features**: danceability, energy, key, loudness, mode, speechiness, acousticness, instrumentalness, liveness, valence, tempo, duration_ms, time_signature  

![Dataset Features](https://raw.githubusercontent.com/manulucena12/spotify-trends/main/public/features.jpg)

## Project Structure
1. **Data Loading & Cleaning**  
   - Imported dependencies, cleaned the data, and grouped features by year to study their evolution  
   ![Averages by Year](https://raw.githubusercontent.com/manulucena12/spotify-trends/main/public/averages.jpg)
2. **Feature Trends Over Time**  
   - Plotted the evolution of key audio features  
   ![Feature Trends](https://raw.githubusercontent.com/manulucena12/spotify-trends/main/public/plot1.jpg)
3. **Popularity Comparison**  
   - Compared the most popular features  
   ![Popularity Comparison](https://raw.githubusercontent.com/manulucena12/spotify-trends/main/public/plot2.jpg)
4. **Correlation Analysis**  
   - Studied which features most influence song popularity  
   ![Correlation Matrix](https://raw.githubusercontent.com/manulucena12/spotify-trends/main/public/plot3.jpg)
5. **Interactive Visualizations**  
   - Used Plotly for interactive charts  
   ![Interactive Plot](https://raw.githubusercontent.com/manulucena12/spotify-trends/main/public/plot4.jpg)
6. **Genre Comparison**  
   - Compared audio features between Hip-Hop and Pop genres  
   ![Genre Comparison](https://raw.githubusercontent.com/manulucena12/spotify-trends/main/public/plot5.jpg)

---

*PS: Each plot includes a reflection that attempts to explain the observed behaviors.*