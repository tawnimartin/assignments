# 02/16/15

___This homework is due by 8am, on 02/17/15___

## Homework

### Part 1

There is an included file called `refactor.js`, it contains 10 pieces of code that need to be refactored. There is a description above each snippet of code explaining how it should be refactored. There is also a place for you to put your answer. Copy the file to your own repo and complete each question. I want __at least one commit for each question__. You may make multiple commits for each question but you may not make a single commit for more than one question. __Do not edit any part of the document other than to add your code to the specified area__. Any answers that require explanation need to be done so via comments so that this remains a __valid javascript file__ when you turn yours in.

### Part 2

Create a project that loads the provided `data.json` file via Ajax. Create a function that converts the data into an HTML tree. Use the provided `categories.html` file for reference on what your function should be returning.

**Hint**

* First work on converting the root items:
  - __Electronics__
  - __Books__
* The tackle the next level down:
  - __Electronics__
    - __Computers__
    - __Home Entertainment__
  - __Books__
    - __Fiction__
    - __Non Fiction__
* Continue building each level at a time.

This is going to be a very difficult and tedious task. I want this to be painful. It may get too complex and you may get lost in the steps. Make sure you are committing to git at every iteration!!

If you can't get the function to work on all the levels, just do the best you can.

This tree of data is 5 levels deep. Imagine if it were 20?

Tomorrow we are going to learn a new programming technique to solve problems like this no matter how many levels deep.

## Deliverables

You may use 1 repo for both parts or split them into 2 repos. Either way, each one should also have a `gh-pages` branch with an `index.html` file that loads your `.js` so I can easily run it.

Comment on the issue assigned to you with links to the repo, and to the github pages.

## Resources

* [jQuery API](http://api.jquery.com/)
* [jQuery.ajax()](http://api.jquery.com/jQuery.ajax/)
* [bower](http://bower.io/#getting-started)

