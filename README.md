# Popular Movies Phase 1
A Udacity project part of the Android Nanodegree that displays popular movies.

# API Key
To run this app you will need to create a free account at The Movie DB. Then you can 
request an API key at The Movie DB. Once you have an API key go to file DownloadTask.java, 
which can be found in /app/src/main/java. Then insert on line 15:


public class DownloadTask extends AsyncTask<String, Void, String> {
   
   //Insert API Key here
    
    private final String API_KEY = "API-KEY";

# Project Overview
Most of us can relate to kicking back on the couch and enjoying a 
movie with friends and family. In this project, you’ll build an app to 
allow users to discover the most popular movies playing. We will split the 
development of this app in two stages. First, let's talk about stage 1.

In this stage you’ll build the core experience of your movies app.

# Your app will:

- Present the user with a grid arrangement of movie posters upon launch.
- Allow your user to change sort order via a setting:
- The sort order can be by most popular or by highest-rated

Allow the user to tap on a movie poster and transition to a details screen with additional information such as:
- original title
- movie poster image thumbnail
- A plot synopsis (called overview in the api)
- user rating (called vote_average in the api)
- release date

# Why this Project?
To become an Android developer, you must know how to bring particular mobile experiences to life. 
Specifically, you need to know how to build clean and compelling user interfaces (UIs), fetch data 
from network services, and optimize the experience for various mobile devices. You will hone these 
fundamental skills in this project.

By building this app, you will demonstrate your understanding of the foundational elements of 
programming for Android. Your app will communicate with the Internet and provide a responsive and 
delightful user experience.

# What Will I Learn After Stage 1?
You will fetch data from the Internet with theMovieDB API.
You will use adapters and custom list layouts to populate list views.
You will incorporate libraries to simplify the amount of code you need to write
