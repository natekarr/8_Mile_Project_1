# Analysis of Yearly Spotify Top Hits

# Outline of Project:
We used the Spotify API to analyze Spotify's Top Hits Playlists. We looked at how popular songs were, the genres listened to most, the most popular artists, and looked for potential outliers ("one hit wonders"). We performed t-tests to look at the year of a songs release and its popularity, as well as to look for a significant difference between popularities of two artists. Lastly, we analyzed a survey that had data about mental health and music listening habits. 


# Conclusions:
Song popularity tended to be above 80, with some interesting outliers appearing in the top 50 hits with popularity scores as low as 60, showing ‘one hit wonders’ or showing songs whose popularity has fallen over the years. Drake and Post Malone have been the top Spotify artists for the past 7 years. Pop dominates spotify’s top hits, with hip hop and rap often being the next popular. Not enough data to make a conclusive thought on music's effect on mental health, but from the little we have there is a small correlation that a small amount of music listening per day will better ones mental health


# Limitations of Data: 
There were many limitations that we ran into with this data. Spotify did not have an official top 50 hits for 2021, we could not find a reason for this and it left a decent gap in our data. Spotify API does not allow you to grab a songs genre, it only allows you to grab the genres that the artist creates, making our genre names very ugly. Spotify does not allow you to access the amount of plays a song has, it only gives you a ‘popularity score’ from 0 to 100. This was very disappointing as it is not clear what the popularity score of a song really means, the number of plays would have been much more concrete. Mental health survey was only for 2022, meaning it only applied to 14% of our data.
