# Project: Spotify Songs Analysis 2023

## Table of Contents  
1. [Introduction](#introduction)
   * [Business Overview/Problem](#businessoverview/problem)
   * [Rationale for the Project](#rationalefortheproject)
2. [Aim of the Project](#aimoftheproject)
3. [Data Description](#datdescription)
4. [Tech Stack](#techstack)
5. [Project Scope](#projectscope)
6. [Data Interpretation](#datainterpretation)
7. [Recommendations](#recommendations)

## Introduction 
This project is the second one completed during my internship at CognoRise Infotech. The project provides an analysis of Spotify songs for the year 2023. The dataset includes famous songs listed on Spotify and describes each song's popularity and attributes on different music platforms.
This project was completed in Power BI where I designed an interactive dashboard to communicate insights from the analysis. 

### Business Overview/Problem
This project leverages Power BI to analyze Spotify song data, providing insights into trends, listener preferences, and genre popularity. By visualizing metrics such as streaming counts and song characteristics, this analysis helps music curators, marketing teams, and artists make data-driven decisions. The goal is to optimize playlist recommendations, target specific audience segments, and enhance user engagement on the platform. Additionally, it supports predictive analysis for emerging artists or trends, allowing Spotify to remain competitive in the digital music landscape.
The key obstacles that could arise include:
1. **Data Availability and Access**: Ensuring access to accurate, real-time Spotify song data might be challenging due to API limitations or licensing restrictions.
2. **Data Quality and Completeness**: Incomplete or inconsistent data, such as missing song features or listener demographic details, could affect the accuracy of insights.
3. **Dynamic User Preferences**: Music trends and user behavior change frequently, making it difficult to keep the analysis relevant and up-to-date without continuous data refreshes.

### Rationale for the Project
The rationale behind the Spotify songs analysis project centers around the need to understand user behavior, enhance product offerings, and make data-driven decisions for business growth.
1. **Enhance User Engagement**: Gain insights into listener preferences to tailor personalized music recommendations and improve user satisfaction on the platform.
2. **Identify Popular Trends**: Analyze streaming patterns to detect emerging music genres, popular artists, and hit songs, allowing for timely content curation.
3. **Support Data-Driven Decisions**: Provide Spotify's marketing and product teams with actionable insights to drive targeted campaigns and improve customer retention.
4. **Optimize Playlist Creation**: Use song characteristics data such as energy, danceability, and liveness to curate more engaging and relevant playlists for different user segments.
5. Monetize Listener Preferences**: Help Spotify maximize revenue by analyzing which types of content or artists are most popular with different demographic groups, allowing for better advertising or subscription targeting.

## Aim of the Project
The key tasks in this project are to understand what are the top songs and artists on Spotify content and provide recommendations regarding user preferences. Some specific objectives are: 
1. Exploring patterns in audio features to understand trends and preferences in popular songs.
2. Comparing the song's popularity across different music platforms such as Apple, Deezer, and Shazam.
3. Analyzing how artist involvement and attributes relate to a song's success.
4. Identifying any shifts in music attributes and preferences over time.
5. Investigating how songs perform across different streaming services.
 
## Data Description
This dataset consists of information such as track name, artist name, release date, Spotify playlists and charts, streaming statistics, Apple Music presence, Deezer presence, Shazam charts, and various audio features. The dataset contains 24 columns and 953 rows described as follows:
*	*Track Name*: Name of the song
*	*Artist Name*: Name of the artist who sang the song
*	*Artist Count*: Number of artists contributing to the song
*	*Released Year*: The year when the song was released
*	*Released Month*: The month when the song was released
*	*Released Day*: The day when the song was released
*	*Spotify Playlists*: Number of Spotify playlists the song is included in
*	*Spotify Pharts*: Presence and rank of the song on Spotify charts
*	*Streams*: Total number of streams on Spotify
*	*Apple Playlists*: Number of Apple Music playlists the song is included in
*	*Apple Charts*: Presence and rank of the song on Apple Music charts
*	*Deezer Playlists*: Number of Deezer playlists the song is included in
*	*deezer_charts*: Presence and rank of the song on Deezer charts
*	*Shazam Charts*: Presence and rank of the song on Shazam charts
*	*BPM*: Beats per minute, a measure of song tempo
*	*Key*: Key of the song
*	*Mode*: Mode of the song (major or minor)
*	*Danceability*: Percentage indicating how suitable the song is for dancing
*	*Valence*: Positivity of the song's musical content
*	*Energy*: Perceived energy level of the song
*	*Acoustic*: Amount of acoustic sound in the song
*	*Instrumental*: Amount of instrumental content in the song
*	*Live*: Presence of live performance elements
*	*Speech*: Amount of spoken words in the song

## Tech Stack
The analysis tool for this project focused on data analysis using Microsoft Power BI. Therefore, Power BI's built-in features were used to analyze data and design an interactive dashboard.

## Project Scope
* **Data Gathering and Integration**
  1. Download Spotify Songs content from Kaggle.
  2. Store the data in a secure folder for further steps.

* **Data Cleaning**: Power Query was used to clean and transform the data. To complete this process, I
  1. Renamed fields for consistency.
  2. Checked for nulls across all columns and replaced them with 0.
  3. Replaced empty values with "Not Given" where necessary.
  4. Removed the Error value in the Stream column by replacing it with the mean of the column.

* **Data Analysis and Dashboard Development**
  1. I created several charts such as
    * Bar charts to show artists and tracks by the number of streams and artists by tracks
    * A Line chart to show charts from various music platforms by track name
    * A donut chart to show the number of tracks by mode
    * A column chart to show the number of streams by released month
    * A Stacked Bar chart to show the top 10 track names by categories.
  2. Designed a dashboard in Power BI to provide an overview of content.
  3. Included key metrics and charts to monitor top songs, top tracks, number of streams, and Number of tracks. 
  4. After creating all the charts, I combined them in a dashboard as shown in Figure 1.

<figure>
  <img src="https://github.com/Songonge/CognoRise-Infotech/blob/main/Spotify Project/Spotify Dashboard.png" width=100% height=100% alt="alt text">
  <figcaption>Figure: Spotify Songs Analysis 2023 Dashboard</figcaption>
</figure>
<br/><br/>

## Data Interpretation
1. **Content Type Distribution**: Movies dominate Netflix's library, comprising nearly 70% of the content, while TV shows make up the remaining 30%. This indicates a significant emphasis on movie content.
2. **Content Addition Over the Years**: The amount of content added has increased significantly from 2015 to 2020, peaking in 2019. There was a slight decline after 2020, potentially due to market saturation or strategic shifts.
3. **Top Countries by Content Type**: The United States is the leading country producing Netflix content, followed by India and the United Kingdom. The U.S. primarily produces movies, while India has a more balanced distribution between TV shows and movies.
4. **Top Directors by Content Type**: Rajiv Chilaka, known for producing movies, leads the list of directors, followed closely by Raúl Campos & Jan Suter, who also predominantly direct movies. TV shows, however, are less represented among top directors.
5. **Top Most Watched Content Categories**: Dramas and international movies are the most-watched categories, closely followed by documentaries and stand-up comedy. The diversity in popular genres suggests a wide range of viewer interests.
6. **Content Release Years**: Most content was released between 2017 and 2020, with 2018 seeing the highest number of releases. The decline in 2021 suggests a reduction in new releases, possibly due to the COVID-19 pandemic.
7. **Content Ratings**: TV-MA (mature audience) content dominates, with TV-14 following. This suggests a significant portion of Netflix's audience prefers mature content.

## Recommendations
1. **Diversify Content Types**: Since movies are predominant, Netflix could consider expanding its TV show offerings to attract a more diverse audience, particularly in countries like India, where TV shows have a significant market share.
2. **Leverage Top Categories**: Since dramas and documentaries are popular, Netflix should invest in producing high-quality content in these categories. Additionally, exploring niche categories like stand-up comedy could further attract and retain subscribers.
3.	Strategic Content Release: The decline in new content after 2020 suggests the need to evaluate current content strategies. Netflix should focus on maintaining a steady flow of releases, even if production is impacted by external factors like pandemics.
4.	Expand Global Presence: With most content originating from the U.S., expanding production in other regions, especially in Asia and Europe, could help cater to local preferences and increase global viewership.
5.	Targeted Marketing: Given the dominance of TV-MA ratings, Netflix could tailor its marketing efforts to highlight mature content while ensuring parental controls and family-friendly content are also emphasized to cater to diverse audiences.
6.	Capitalize on Most Watched Categories: Netflix should consider creating more original content in its top-viewed categories. For example, focusing on cross-genre content that blends drama, international films, and documentaries could drive engagement.
   
**Thank you for taking the time to read this report!**

**Please reach out for any updates.**

### Author
[Edwige Songong](https://github.com/Songonge)


