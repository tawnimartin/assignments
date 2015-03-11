# 03/11/15

___This homework is due by 8am, on 03/12/15___


## Homework

Fork this [music app](https://github.com/tiy-tpa-js-q1-2015/music-app) and refactor it to a richer application.


## Requirements

* Make the app have 2 primary screens, __genres__ and __search__.
* Use Backbone.Router to navigate between the screens (back/forward button navigation and bookmarking must work).
* Make both screens have a constant navigation area to jump between the screens.
* on the genres screen, have a sidebar with a set of genres (e.g. buttons like "rock", "rnb", "metal", "country") that the user can click and load songs for that genre.
* on the search screen, allow the user to enter a search term and display songs matching the search results.
* use the following routes:
  - `genre/:genre`
  - `search/:keyword`

Below are example wireframes of how each screen could look:

```
  +--------------------+
  |      main nav      |
  +--------------------+
  |  G  |              |
  |  E  |              |
  |  N  |    SONGS     |
  |  R  |              |
  |  E  |              |
  |  S  |              |
  +--------------------+
```


```
  +--------------------+
  |      main nav      |
  +--------------------+
  |       search       |
  +--------------------+
  |                    |
  |       SONGS        |
  |                    |
  |                    |
  +--------------------+
```


### Normal Mode

  * Make both screens

### Easy Mode

  * Just make the genres screen
   - (I am only adding this because there is a required field trip tomorrow so lab is cut short)

### Hard Mode

  * Make both screens and make an additional screen (example, a screen where you can search within a particular genre)

### Go Even Further

  * Add aditional functionality. Examples:
    - Volume controls
    - Stop playing the current song when playing a new song.


## Deliverables

* Push to github
* Deploy to gh-pages
* Comment on the issue assigned to you with a link to both.


## Resources

* [Sound Cloud SDK](https://developers.soundcloud.com/docs/api/sdks)
* [Sound Cloud API](https://developers.soundcloud.com/docs/api/guide)
