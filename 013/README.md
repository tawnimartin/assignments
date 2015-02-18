# 02/18/15

___This homework is due by 8am, on 02/19/15___

## Homework

### Normal Mode

Copy the included `constructors.js` to a new project. Add an index.html that includes it. Answer all the questions and upload to __gh-pages__.

Keep in mind in the examples in `constructors.js`
I need to be able to test them in __gh-pages__ on the
console. Also make sure there are no javascript errors
and check your code in [js hint](http://jshint.com/). Finally make sure it
is formatted/indented correctly. Code is in place
that validates each answer. It will currently say:
`Assertion failed` for each question. Once you answer
the question correctly that will go away. Use this to
check your work.

### Hard Mode

In the `constructors.js` there is a bonus question at the bottom. This is your hard mode. If you are finished with your normal mode before 7pm I would urge you to try the hard mode.

### Nightmare Mode

The file `since.jquery.js` contains a jQuery plugin. Currently it sets html elements to have a red color and background. Refactor it to do the following:

  * Check each selected element for a data attribute of `since` that will be used as the date for that html element. If not present, use the current date.

  * if the date is less than __1 minute ago__, make the elment's text: __just now__
  * if the date is less than __5 minutes ago__, make the elment's text: __a few minutes ago__
  * if the date is less than __1 hour ago__, make the elment's text: __within the past hour__
  * if the date is less than __1 day ago__, make the elment's text: __today__
  * if the date is less than __6 days ago__, make the elment's text: __whatever the day is for the given data (e.g. Friday)__
  * if the date is more than __6 days ago__, make the elment's text: __/mm/dd/yyyy__

  You can go even further by using an interval to keep the message up to date without having to recall the jQuery plugin. Meaning you call it on an element and the text gets set to _just now_, then 2 minutes later, it auto resets to __a few minutes ago__ and so on.

## Deliverables

* Push to gh pages.
* Comment on the issue assigned to you with a link to your repo and a link
to your gh-pages.

## Resources

* [Working with objects](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Guide/Working_with_Objects)
