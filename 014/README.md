# 02/19/15

___This homework is due by 8am, on 02/23/15___

## Homework

Create a photo gallery application which will allow the user to view their albums as well as the individual photos contained within, as a single page application (SPA).

You can create your own JSON file with all the data you need. Come up with whatever structure works best. Load this file via Ajax.

You can make the images self hosted (in the repo in an images folder) or you can load them from an image sharing site like imgur.


## Wireframes

![Wireframes](assets/photo-album.png)


## Objectives

After completing this assignment, you should be able to effectively use

* jQuery and DOM events
* constructors to organize and create cohesive code
* templates


### Deliverables

Push your app to github and github pages. Comment with a link to both on the issue assigned to you.


### Requirements

* `index.html` is the only page that exists for this assignment
* Must have a minimum of 6 photo albums
* Each photo album must contain at least 3 photos
* Based on the wireframes, you have 3 main views.
  - Main Gallery of Albums view
  - Contents of Album view
  - Photo detail view
* JS dependencies must be loaded via bower and be included as a dependency via  `bower.json`
* Styles should be defined via LESS and compiled to CSS via Gulp
* Templates should be handlebars and compiled to templates.js via Gulp
* Gallery is data driven via loading JSON with Ajax


## Normal Mode

To complete this assignment:

- The gallery application must be a single web page
- The views must match the wireframe layouts
  * (within reason - have fun with the design)


## Hard Mode

Do everything in normal mode, but also:

- On the photo detail, allow to navigate to other photos in the same album via a prev/next buttons.
