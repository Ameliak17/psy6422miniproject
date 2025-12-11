# PSY6422 miniproject

# Spotify Top Artists Analysis (January vs November 2025)

This project analyses the most-streamed artists on Spotify, comparing their cumulative streams between January and November 2025. It demonstrates data cleaning, transformation, and visualisation using R and Quarto, highlighting trends in artist popularity over the year.

## Project Description

-   **Objective:** To explore how artist popularity changes throughout the year and identify emerging trends or spikes due to album releases.
-   **Data Source:** Spotify Global Weekly Charts (CSV files, downloaded from [charts.spotify.com](https://charts.spotify.com/))
-   **Analysis:**
    -   Data cleaning and preparation (e.g., splitting collaborative artists, grouping by artist)
    -   Calculation of cumulative streams per artist
    -   Comparison of top artists between January and November using visualisations
-   **Output:** Visualisations created in Quarto/ggplot2

## Data Description 
The data for this project was sourced from charts.spotify.com, which publishes weekly global rankings of the most-streamed songs on Spotify. Two weekly datasets were used:
January 3–9, 2025
November 21–27, 2025 (most recent chart available at time of download)
Each dataset was downloaded as a CSV file from the Spotify Global Weekly Charts, which aggregate streaming counts from all Spotify users worldwide. The charts are generated using Spotify’s internal streaming logs and are freely accessible with a standard Spotify account.
Variables:
-   rank – the position of the track in the weekly chart

-   uri – a unique Spotify identifier for each track

-   artist_names – the name(s) of the artist(s) associated with each song

-   track_name – the name of the song

-   streams – the total number of Spotify streams for that track during the chart week

-   weeks_on_chart – how many weeks the track has appeared in the chart

## How to Run

1.  **Clone the repository:** \`\`\`bash git clone <https://github.com/Ameliak17/psy6422miniproject/tree/main>
