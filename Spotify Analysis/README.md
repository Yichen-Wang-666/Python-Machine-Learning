# Spotify Dataset Analysis and Music Recommendation
<p align="center">
  <img src="https://github.com/jingyuc9988/Spotify_Analysis/blob/master/Image/Spotify_Logo_RGB_Green.png" alt="drawing" width="260"/>
<p align="center">
<p align="center">
  <img src="https://github.com/jingyuc9988/Spotify_Analysis/blob/master/Image/images.png" alt="drawing" width="600"/>
<p align="center">   
</p>

**Conducted by: Jingyu Chen, Yulin Hong, Yingxin Jiang, Yi Kuang, Xintong Li, Alice Liu, Yichen Wang, Kexin Wang**

# Introduction:
This project is conducted using [Spotify dataset on Kaggle](https://www.kaggle.com/ektanegi/spotifydata-19212020). 

We also build a front-end web app of our project, to use it, please refer to this URL (https://8potify.netlify.app/)

**The data dictionary is as followed:**
- id (Id of track generated by Spotify)

**Numerical:**
- acousticness (Ranges from 0 to 1)
- danceability (Ranges from 0 to 1)
- energy (Ranges from 0 to 1)
- duration_ms (Integer typically ranging from 200k to 300k)
- instrumentalness (Ranges from 0 to 1)
- valence (Ranges from 0 to 1)
- popularity (Ranges from 0 to 100)
- tempo (Float typically ranging from 50 to 150)
- liveness (Ranges from 0 to 1)
- loudness (Float typically ranging from -60 to 0)
- speechiness (Ranges from 0 to 1)
- year (Ranges from 1921 to 2020)

**Dummy:**
- mode (0 = Minor, 1 = Major)
- explicit (0 = No explicit content, 1 = Explicit content)
- genre_fit (1 = not fit the desired genre, 5 = Excellent fit)
- mood_fit (1 = not fit the desired mood, 5 = Excellent fit)
- age (ranges from 20-29)

**Categorical:**
- key (All keys on octave encoded as values ranging from 0 to 11, starting on C as 0, C# as 1 and so on…)
- artists (List of artists mentioned)
- release_date (Date of release mostly in yyyy-mm-dd format, however precision of date may vary)
- name (Name of the song)

