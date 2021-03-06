# Flixster

Flixster is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

### User Stories

- User can view a list of movies (title, poster image, and overview) currently playing in theaters from the Movie Database API.
- Views are responsive for both landscape/portrait mode.   
- Display a nice default placeholder graphic for each image during loading
- Improved the user interface by experimenting with styling and coloring.
- Expose details of movie (ratings using released date, RatingBar, popularity, and synopsis) in a separate activity when user selects "DETAILS".
- Allow video posts to be played in full-screen using the YouTubePlayerView.
- Implement a shared element transition when user clicks into the details of a movie.
- Trailers for are played automatically when the user selects "PLAY TRAILER".
- Add a rounded corners for the images using the Glide transformations.


### App Walkthough GIF
<img src="Flixster Walkthrough.gif" width=250><br>

### Open-source libraries used

- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Androids
