# Movie Finder 

**About Movie** is a sample android application 📱to search movies 🍿using OMDb API which is built to demonstrate use of *Modern Android development* tools. It has been built using kotlin with clean architecture principles and MVVM pattern as well as Architecture Components. Dedicated to all Android Developers with ❤️.



## About
The app in itself is a simple movie searching app. Clicking the movie list item it shows the detail of the movie. While this is not an extremely complex app, it isn't a silly Hello World one either, so the hope is that it'll cover regular use cases for a basic application.


## Sailent Features:
- Search the movies.
- View the list of movies based on the search result.
- View the released date, genre, IMDB rating and short plot.

## 📸 Screenshots

**Please click the image below to enlarge.**

<img src="https://github.com/cheetahmail007/AboutMovie/blob/master/screenshots/1.png" height="600" width="300" hspace="40"><img src="https://github.com/cheetahmail007/AboutMovie/blob/master/screenshots/2.png" height="600" width="300" hspace="40">

<img src="https://github.com/cheetahmail007/AboutMovie/blob/master/screenshots/3.png" height="600" width="300" hspace="40"><img src="https://github.com/cheetahmail007/AboutMovie/blob/master/screenshots/4.png" height="600" width="300" hspace="40">


## Built With 🛠
- [Kotlin](https://kotlinlang.org/) - First class and official programming language for Android development.
- [Coroutines](https://kotlinlang.org/docs/reference/coroutines-overview.html) - For asynchronous and more..
- [Android Architecture Components](https://developer.android.com/topic/libraries/architecture) - Collection of libraries that help you design robust, testable, and maintainable apps.
  - [LiveData](https://developer.android.com/topic/libraries/architecture/livedata) - Data objects that notify views when the underlying database changes.
  - [ViewModel](https://developer.android.com/topic/libraries/architecture/viewmodel) - Stores UI-related data that isn't destroyed on UI changes. 
  - [ViewBinding](https://developer.android.com/topic/libraries/view-binding) - Generates a binding class for each XML layout file present in that module and allows you to more easily write code that interacts with views.
- [Koin](https://insert-koin.io) - Dependency Injection Framework
- [Retrofit](https://square.github.io/retrofit/) - A type-safe HTTP client for Android and Java.
- [GSON](https://github.com/google/gson) - A Java serialization/deserialization library to convert Java Objects into JSON and back.
- [GSON Converter](https://github.com/square/retrofit/tree/master/retrofit-converters/gson) - A Converter which uses Gson for serialization to and from JSON.
- [OkHttp3](https://github.com/square/okhttp) -  For implementing interceptor, logging and mocking web server.
- [Glide](https://github.com/bumptech/glide) - An image loading and caching library for Android focused on smooth scrolling.
- [Material Components for Android](https://github.com/material-components/material-components-android) - Modular and customizable Material Design UI components for Android.

# Package Structure
    
    com.abhishek.moviefindermvvm    # Root Package
    .
    ├── data                # For data handling.
    │   ├── model           # Model classes
    │   ├── network         # Remote Data Handlers     
    |   │   ├── api         # Retrofit API for remote end point.
    │   └── repository      # Single source of data.
    |
    |
    ├── ui                  # Activity/View layer
    │   ├── main            # Main Screen Activity & ViewModel
    |   │   ├── adapter     # Adapter for RecyclerView
    |   │   ├── viewmodel   # ViewHolder for RecyclerView   
    │   └── details         # Detail Screen Activity and ViewModel
    |
    └── utils               # Utility Classes / Kotlin extensions


## Architecture
This app uses [***MVVM (Model View View-Model)***](https://developer.android.com/jetpack/docs/guide#recommended-app-arch) architecture.

![](https://developer.android.com/topic/libraries/architecture/images/final-architecture.png)


## Contributing

Please fork this repository and contribute back using
[pull requests](https://github.com/Shashank02051997/MovieFinderUsingMVVM-Android/pulls).

Any contributions, large or small, major features, bug fixes, are welcomed and appreciated
but will be thoroughly reviewed .

### Contact - Let's become friend
- [Twitter](https://twitter.com/shashank020597)
- [Github](https://github.com/Shashank02051997)
- [Linkedin](https://www.linkedin.com/in/shashank-singhal-a87729b5/)
- [Facebook](https://www.facebook.com/shashanksinghal02)

<p>
Don't forget to star ⭐ the repo it motivates me to share more open source
</p>

