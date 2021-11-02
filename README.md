# Flixster App
Flixster is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#). 
View on full screen all recents movies using YouTube player view and ratingbar in portrait and landscape mode.

Submitted by: ** Antonine Pelicier**

Time spent: ** 20 ** hours spent in total

---

## Flixster Part 2

#### Flixster2_App


### User Stories

#### REQUIRED (10pts)

- [X] (8pts) Expose details of movie (ratings using RatingBar, popularity, and synopsis) in a separate activity.
- [X] (2pts) Allow video posts to be played in full-screen using the YouTubePlayerView.

#### BONUS

- [X] Implement a shared element transition when user clicks into the details of a movie (1 point).
- [X] Trailers for popular movies are played automatically when the movie is selected (1 point).
  - [X] When clicking on a popular movie (i.e. a movie voted for more than 5 stars) the video should be played immediately.
  - [X] Less popular videos rely on the detailed page should show an image preview that can initiate playing a YouTube video.
- [X] Add a play icon overlay to popular movies to indicate that the movie can be played (1 point).
- [X] Apply data binding for views to help remove boilerplate code. (1 point)
- [X] Add a rounded corners for the images using the Glide transformations. (1 point)

### App Walkthough GIF

`TODO://` Add the URL to your animated app walkthough `gif` in the image tag below, `YOUR_GIF_URL_HERE`. Make sure the gif actually renders and animates when viewing this README. (🚫 Remove this paragraph after after adding gif)

<img src="https//github.com/apelicier/Flixster2-app/Flixster2_App.gif" width=250><br>

### Notes

Describe any challenges encountered while building the app.
I spent almost 6 hours of time to correct an error after adding the .jar file, after all this time of working and executing my project, I decided to check all my files line by line and finally find  the error I was looking for for 3 days (synchronization not done to the graddle file) 
the other one was the electricity problem in my country which makes this project extremely difficult to achieve. Finally I do it. It's very very challenging.

## Open-source libraries used
- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Android
