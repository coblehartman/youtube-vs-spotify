# Song Success Factors Analysis Project

## Project Overview

This project involves analyzing various factors that influence the success of songs. Utilizing data from Spotify and YouTube, the analysis focuses on metrics such as views, streams, danceability, and other attributes to understand what contributes to a song's popularity.

### Data Analysis and Visualization

- **Dependencies**: 
  - Python libraries: `requests`, `json`, `pandas`, `matplotlib.pyplot`, `scipy`, `seaborn`
  - `config.py` containing Spotify API key.

- **Data Source**: 
  - CSV file `Spotify_Youtube.csv` containing Spotify and YouTube metrics for various songs.

- **Key Analysis Points**:
  - Correlation between YouTube views and Spotify streams.
  - Danceability and its influence on song popularity.
  - Most streamed albums on Spotify and most viewed albums on YouTube.
  - Success comparison between singles and albums.
  - Influence of official videos on streaming success.
  - The effect of song licensing on streaming numbers.
  - Genre popularity analysis using the Spotify API.

- **Visualization Techniques**:
  - Scatter plots and linear regression to visualize relationships between different metrics.
  - Bar charts to compare the success of singles vs. albums, and official vs. unofficial videos.
  - Use of seaborn for enhanced data visualization.

### Key Insights

- Analysis of top 100 songs and albums to determine factors contributing to their success.
- Examination of the relationship between danceability, tempo, and overall popularity.
- Investigation into how the official status of a video affects its YouTube views and Spotify streams.
- Use of Spotify's API to analyze genre popularity and artist followers.

### File Structure

- `Spotify_Youtube.csv`: Raw data file containing song metrics from Spotify and YouTube.
- `analysis_notebook.ipynb`: Jupyter Notebook file containing all data analysis and visualizations.

### Instructions for Running the Analysis

1. Ensure all Python dependencies are installed.
2. Place the `Spotify_Youtube.csv` file in the same directory as the Jupyter Notebook.
3. Run `Final Notebook.ipynb` in Jupyter Notebook or Jupyter Lab.
4. View the analysis and visualizations within the notebook.

### Additional Notes

- The project uses Spotify's API to enhance the analysis. Ensure you have a valid API key in `config.py`.
- The data analysis is conducted in a Jupyter Notebook for an interactive and detailed exploration of the dataset.

