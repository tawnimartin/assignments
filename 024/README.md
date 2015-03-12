# 03/12/15

___This homework is due by 8am, on 03/16/15___


## Homework

Build an app from scratch using, Backbone, Firebase, and the Soundcloud API.


## Ideas

_the below ideas are just ideas. Make whatever you want as long as it meets the requirements._

* __Playlist__:

  - You would need a playlist collection to play all the songs in the list
  - You would need to keep track of which song is currently playing, then play the next song in the list when it finishes
  - You would need the song model to be able to know when it is done playing. You could do this by comparing the `stream.position` to the `stream.duration`, or via `stream.onPosition(stream.duration, callback)`, or using an `onfinish` callback with `stream.play` (see the __SMSound API__ in the resources below)
  - You would need a way for the user to search for songs and add them to the play list
  - You could possibly have features like skip, shuffle, or specify order.

* __Media Player__:

  - Create a custom media player interface with pause, play, stop, volume, mute, rewind, etc. controls
  - This view could be large and show the fullsize artwork for the track it is playing
  - Could even have a scrubber using `<input type="range">` and set __max__ to the stream's `duration` and __value__ to the stream's `position`
  - Beneath you could search for songs and when you click to play one, the media player above plays it

* __Song Rater__:

  - Allow user to search for songs and add them to a saved list
  - Allow user to rate them, and list favorited songs by order of rating
  - Then user can open their list of fav songs and play them


## Requirements

* Must save at list 1 collection of data to Firebase
* Must use ___at least___ 1 model, 1 collection, 1 router, 3 views
* Must use ___at least___ 3 routes and 1 must take a parameter (e.g. `search/:query`)
* Your views, router, models & collections must be in seperate files
* Make it beautiful (or at least try to)


## Approach

* Come up with an idea
* Wireframe your design
* Figure out what views, data modeling, and interactions you will need
* Once you have the details figured out, then start to code
* HAVE FUN!


## Deliverables

* push to github
* deploy to github pages
* comment on issue assigned to you with links to both


## Resources

* [Sound Cloud SDK](https://developers.soundcloud.com/docs/api/sdks)
* [Sound Cloud API](https://developers.soundcloud.com/docs/api/guide)
* [SoundManager 2 SMSound API](http://www.schillmania.com/projects/soundmanager2/doc/#smsoundmethods)
* [BackboneFire](https://www.firebase.com/blog/2013-01-29-backfire-firebase-bindings-for-backbonejs.html)
* [Firebase 5 Minute Tutorial](https://www.firebase.com/tutorial/#gettingstarted)


