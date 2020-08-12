# Spotify-DataMining
DATA MINING OF MUSIC INDUSTRY
I.	Introduction
The purpose of this project is to explore the available data of music industry and to provide insightful information by analyzing and interpreting trends.
II.	Steps of data mining
1.	Data Collection
2.	Methodologies
3.	Data Wrangling
4.	Data Exploration & Communication of findings
III.	Details
1.	Data Collection
The information the management is looking for is:
-	Number of streaming
-	Top songs
-	Top artists
-	Relationship between variables includes genre, Beat per minute, valence, acousticness, liveness, speechiness or popularity
Data was collected in this project includes 
-	Top 200 global and US songs on Spotify by daily counting on 08/04/2020. The purpose of this dataset is to explore current trends regarding streaming, artist and songs. Source: https://spotifycharts.com/regional/global/daily/2020-08-04
-	Top 50 global songs on Spotify in 2019. The purpose of this dataset is to find the relationship between features of songs. Source: https://www.kaggle.com/leonardopena/top50spotify2019
2.	Methodologies
Tableau, Python, Excel, SQL are applied during the process of data mining of these datasets
3.	Data Wrangling
General, the data is pretty clean and well-organized. There is not much to do during the process of data wrangling.
4.	Data Exploration
4.1	Global chart
Top 200 songs by Global
 
 
To be in Top 100 of the global chart, any songs should have more than 1 million streaming times.

 
Top artists having highest number of stream
 
Considering Top 200 songs globally, Taylor Swift is the artist that has the highest times of streaming with more than 22 million views by 17 different songs. Juice WRLD ranks secondly with 13.6 million times by 11 songs. Pop Smoke is getting more than 7 million views from 5 different songs.
Average number of streams by artists
 
However, regarding average times of streaming by an artist per each song, Taylor Swift, Juice WRLD or Pop Smoke are not in Top 5 or even Top 5. Jawsh 685 has highest view with the song Savage Love. DaBaby comes after that with the song Rockstar. This information amplified that Taylor Swift and Jucies WRLD has a lot of popular songs but those are not the most streamed hits.
4.2 US Chart
Top songs in the US
 
 
To be in Top 100 of the US chart, any songs should have more than 300,000 streaming times.
 
Top artists having highest times of streaming
 
Considering only in the US, Jucie WRLD with 24 songs has the total views higher than Taylor Swift with 17 songs. Pop Smoke ranks thirdly with more than 3 million views from 6 songs.  This information show us that Taylor Swift is more popular than Jucie WRLD all over the world. However, considering only US market, people love Jucie WRLD’s music more than Taylor Swift’s.
Average stream by artists
 
Lil Mosey, The Weekend and Jack Harlow are top 3 artists that earn highest views per song. Taylor Swift is also in Top 5 with 626,497 views. Although DaBaby has the hit ROCKSTAR with highest times of streaming (more than 1.1 million views), on average, this artist only gets around 450,000 views average with 5 songs in Top 200. This means that other songs of DaBaby is not as popular as ROCKSTAR although both of them are in Top 200.
4.3 Comparison between Global chart and US chart
The analyst would like to see how many times that songs in global chart are listened by people in the United of States.
 
Regarding Top 10 songs that are listened globally, on average, there is 25% of streams that are from people in the US. There are some songs that have higher percent of streams than average number. They are Come & Go, exile, my future, ROCKSTAR and cardigan. This means that these are songs seems to be on the trending in the US.
What are the positions of those Top 10 global songs in US chart?
 
 
Although Savage Love has the 1st ranking of streaming, there seem to be a decrease in its popularity in the US with the ranking of 18th. On the other hand, ROCKSTAR is doing well in both global and US billboards. Taylor Swift’s recent songs are in both Top 10 global and US chart.

 
 
US chart and global chart has total 119 songs in common. This means that nearly 60% of global music in Top 200 are influenced by US music.
There are 81 songs in Top 200 US chart that is not in Top 200 Global chart. This means that these songs below are popular only in the US not globally.
 
 
5.	Relationship between variables
The information is analyzed by the data Top 50 Spotify songs 2019
Data source: https://www.kaggle.com/leonardopena/top50spotify2019
The dataset is about the top 50 most listened songs in the world by Spotify. This dataset has several variables about the songs. The data includes 50 songs and 13 variables
 
 
Varaibale definition:
•	Danceability: Describes how suitable a track is for dancing based on a combination of musical elements including tempo, rhythm stability, beat strength, and overall regularity.
•	Valence: Describes the musical positiveness conveyed by a track. Tracks with high valence sound more positive (e.g. happy, cheerful, euphoric), while tracks with low valence sound more negative (e.g. sad, depressed, angry).
•	Energy: Represents a perceptual measure of intensity and activity. Typically, energetic tracks feel fast, loud, and noisy. For example, death metal has high energy, while a Bach prelude scores low on the scale.
•	Beats per minute (BPM): the speed or pace of a given piece, and derives directly from the average beat duration.
•	Loudness: The overall loudness of a track in decibels (dB). Loudness values are averaged across the entire track and are useful for comparing relative loudness of tracks.
•	Speechiness: This detects the presence of spoken words in a track. The more exclusively speech-like the recording (e.g. talk show, audio book, poetry), the closer to 1.0 the attribute value.
•	Liveness: Detects the presence of an audience in the recording. Higher liveness values represent an increased probability that the track was performed live.
•	Acousticness: A confidence measure from 0.0 to 1.0 of whether the track is acoustic.

An overview of the quantitative variables
 
 
In 2019, Ed Sheeren has the most number of song in top 50 songs of Spotify with 4 songs. The Chainsmokers, Ariana Grande, Shawn Mendes, Sech, Billie Ellish and Post Malone share the 2nd position with 2 songs for each.
 
 
Dance pop (8 songs), pop (7 songs) and latin (5 songs) are the most popular genre in top 50 Spotify 2019.

 
In general, most of the songs in top 50 has the popularity from 87 to 90.
 
The distribution of energy focus on three branches: around 40, from 60 to 70 and around 80.
 
In general, most of the songs in top 50 has the Beats per Minutes from range 85 to 115.

 
In general, most of the songs in top 50 has the Danceability at around 85. This means most of the songs have the ability make people dance.
 
In general, most of the songs in top 50 has the Liveness at around 5.
 
In general, most of the songs in top 50 has the Liveness from 60 to 70. However, there are a number of songs in top 50 has the Valence at around 40. This means that those song with medium level of cheerfulness has the highest distribution.
 
In general, the distribution of Loudness is mainly around -6 and -4.
 
Most of the songs has the length at around 200 seconds. The distribution of the length is mainly from 175 to 225 seconds.
 
Most of the songs have the acousticness from 0 10 15.
 
Most of the songs have the speechiness figure less than 8.
 
 
Bivariate Exploration
•	Beats Per Minute had a positive relationship with speechiness with the correlation of 0.56.
•	Energy had a strong relationship with Loudness and Valence but it has a negative relationship with acousticness.
•	Danceability didn’t really have any strong relationships with other attributes. Together with the distribution of danceability, it can be inferred that any songs in top 50 had an ability to make people dance regardless of other attributes.
•	Loudness had a negative relationship with speechiness but strong positive relationship with Energy.
•	Liveness didn’t really have any extremely strong relationships with other attributes. However, it did have a negative relationship with Beats Per Minutes but positive relationship with Loudness and Ranking of the Songs.
•	Valence had a positive relationship with Energy but negative relationship with Popularity.
•	Length didn’t have any strong relationship with other attributes except slightly positive relationship with Loudness and Energy. This means that longer song tends to have higher level of Loudness and Energy.
•	Position (Unamed column) has a slightly positive relationship with Valence and Liveness but a negative one with Speechiness, Beats Per Minute and Popularity.
 
Electric Pop had the highest popularity while Canadian pop’s popularity is the lowest.
 
Lower ranking songs tends to have higher level of popularity.
 
Energy and Loudness had a positive relationship together. The higher the level of loudness of a song is, its energy tend to be higher.
 
Speechiness and Beats per Minute had a positive relationship with each other.
 
Popularity and Valence had a negative relationship with each other.
 
Energy, Valence and Loudness had a positive relationship together. This means that the more cheerful a song is, the higher level of loudness and energy it has.
 
Higher ranking songs tend to have slightly higher level of speechiness.
As analyzed earlier above, dance pop (8 songs), pop (7 songs) and latin are the most favorite genre in top 50 Spotify 2019. When considering both Artist and Genre together, we can see that Ed Sheeran is the king of pop music with 4 out of 8 pop songs in Top 50. Both of songs of Ariana Grande in Top 50 have the genre of dance pop.


 
IV.	Summary and conclusions
Regarding Top 200 Spotify in global chart and US chart:
-	Taylor Swift and Juice WRLD are top artist that have highest number of songs in Top 200 both globally and in US. Taylor Swift is the most popular artist with highest number of songs and highest number of total view.
-	US chart and global chart has total 119 songs in common. This means that nearly 60% of global music are influenced by US music considering Top 200 songs by Spotify globally and in the US.
Regarding the relationship between variables in Top 50 Spotify songs 2019:
-	Energy, Valence and Loudness had a positive relationship together. This means that the more cheerful a song is, the higher level of loudness and energy it has.
-	Speechiness and Beats per Minute had a positive relationship with each other.
-	Popularity and Valence had a negative relationship with each other.
-	Electric Pop had the highest popularity while Canadian pop’s popularity is the lowest
-	Higher ranking songs tend to have slightly higher level of speechiness and Beats Per Minutes.
-	Most of the song in Top 50 Spotify songs 2019 has an ability to make people dance.
