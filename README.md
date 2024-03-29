# Does Song Duration Affect Popularity?

![image](https://github.com/juanpi19/spotify-analysis/assets/68093380/00e8fae6-43d1-4721-98ff-dc7c5486a8a8)


## Project Overview

This project analyzed whether the duration of a song impacts its popularity on music streaming platforms. The hypothesis was that song duration does have an effect on engagement metrics like number of likes.

The project focused on analyzing songs on Spotify to see if there was a correlation between song length and number of likes. The goals were to:

- Collect song data from Spotify
- Clean and process data 
- Analyze if song duration impacts number of likes
- Determine the ideal song duration for maximum engagement

## Data Collection and Cleaning

Song data was collected from an available dataset in Kaggle. The data included attributes like song name, artist, album, release date, genre, and duration.

The raw data went through a cleaning process:

- Removed duplicates
- Handled missing values
- Fixed formatting errors
- Added columns like length category (short vs long) 

The cleaned dataset was then ready for analysis.

## Analysis and Modeling

The data analysis focused on comparing the average number of likes for short songs (<3 min) vs long songs (>3 min). Statistical tests were run to see if the difference in means was significant.

Regression modeling was used to determine the ideal song duration that would maximize likes. Different models were tested out, including adding interaction terms. 

Key findings:

- Long songs had significantly more likes than short songs
- The ideal song duration was between 3.55-4.12 minutes



![image](./barchart.png)

## Conclusion

The analysis showed clear evidence that longer song duration leads to increased engagement on Spotify in the form of likes. This could guide musicians and labels looking to boost streams and visibility on streaming platforms. The ideal "hit song" duration seems to be around 4 minutes. 

## About the Project

This project was completed by Team E5 at USC Marshall School of Business. The team members were:

- Anqi Luo
- Antonia Roates
- Campbell Duncan 
- Farhan Sikder
- Juan Herrea
- Marliese Sanabria
- Nuo Chen
- XuÿenĀ Tu

The final presentation slide deck and datasets can be found in this GitHub repo. Please contact the team with any questions!
