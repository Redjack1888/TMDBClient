# TMDBClient
In this project I built a TMDB client app following MVVM Clean architecture with Dagger, Retrofit, Room, Coroutines and data binding.
The Project Requires an API Key from The Movie Database (https://www.themoviedb.org/) to work properly.
I had implemented a local data source, remote data source and a cache data source.

# Use cases of the project.

User should be able to view popular movies
And user should be able to update them when needed.
That means, In our app we are going to download movie details from the api once, store them in the database and display the data taken from the data base.
But TMDB list of most popular movies usually changes every day. So if the user wants, user should be able to update the stored movies list by clicking on the update icon.
Similarly user should be able to view and update most popular tv shows and most popular actors and actresses.


