# Flix
Flix is an app that allows users to browse movies from the [The Movie Database API](http://docs.themoviedb.apiary.io/#).

---

## Flix

### User Stories

#### REQUIRED (10pts)
- [x] (70pts) User can view a list of movies (title, poster image, and overview) currently playing in theaters from the Movie Database API.
- [x] (10pts) Views should be responsive for both landscape/portrait mode.
   - [x] (5pt) In portrait mode, the poster image, title, and movie overview is shown.
   - [x] (5pt) In landscape mode, the rotated alternate layout should use the backdrop image instead and show the title and movie overview to the right of it.
- [x] (20pts) Improved the user interface by experimenting with styling and coloring.

### App Walkthough GIF
![Sample Gif](https://i.imgur.com/Iexhelo.gif)
<img src="/art/sample.gif?raw=true" width="200px"><br>
<img src="https://i.imgur.com/K610CZl.gif" width=250><br>


### Notes
Describe any challenges encountered while building the app.

Setting up the RecyclerView and Adapater was a challenging concept to implement as well as keeping
the app consistent during orientation change. Another challenge was displaying the ratings/popularity/date for
the NOW PLAYING movies and adjusting the adapter to achieve this UI improvement.

### Open-source libraries used

- [Android Async HTTP](https://github.com/codepath/CPAsyncHttpClient) - Simple asynchronous HTTP requests with JSON parsing
- [Glide](https://github.com/bumptech/glide) - Image loading and caching library for Androids
