# What Makes a Song Danceable?

## Description

In this project we looked at over 1.2 million songs from Spotify to determine what factors make songs danceable. In the dataset we obtained from Kaggle, each song had a ranking for danceability from 0 to 1. Along with the danceability it had rankings for other factors of how the song was constructed. Our goal was to use these factors to determine which ones had the greatest impact on the songs danceability, specifically looking at the song’s energy, tempo, duration and release year. 

## Technologies Used

In order to obtain the data, we needed we used Python and Pandas. We also had to pull in the dependencies matplotlib, scipy and numpy. We used matplotlib for our visuals.

## Contributors

Erin Clark, Molly Gac, Zech Hornby, and Cam Pulling

## Further Analysis

We were able to find some interesting trends for the danceability. We discovered that the higher the energy the more likely a song is to be danceable, but energy alone did not necessarily make it danceable. We were able to conclude that the ideal tempo was between 100-125 bpm. Once the tempo exceeds 125 it can begin to have a negative effect on the danceability as it becomes harder to stay on beat with the song. Songs that have high energy but maintain the 100-125 bpm are the best songs for dancing. The duration of the songs had more of an impact than expected. Songs that are too short or too long both negatively impact the danceability. Songs between 3 minutes and 20 seconds and 5 minutes in length were ideal for dancing. Practically thinking this makes sense as after 5 minutes of dancing to a song most people would begin to get tired or find the song repetitive. The data also implies that songs released between 2000 and 2020 are the most danceable when looking at a specific year. The last thing we did was to find the top 10 artist for each category based on the mean of all their songs. This data however was skewed by artitsts with only one song due to features on the particular song. We filtered out those songs and only looked at artists with 10 or more songs. This gave us a better understanding on who the top artists truly were for each category. Now use this data to construct the perfect dance playlist for your next party!
