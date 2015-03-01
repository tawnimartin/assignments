# 03/02/15

___This homework is due by 8am, on 03/03/15___


## Homework

### Part 1

You guessed it! Write a blog post about last week.

### Part 2

Create a new project with Mocha and Chai. Include the [test.extending.js](test.extending.js) test suite and make it passing.

There are 3 parts to the test you will need to solve

  * You will need to create a hierarchy of several constructors for different types of vehicles all descending from a root vehicle.

  * You will have to create a base hash (object) called __extendee__ with various keys and values. You will then need to create another object called __extended__ and use `_.extend` to make it extend the __extendee__ object.

  * Finally you will need to create a function called `param` the function should accept some parameters and return them. The function should have a set of default parameters that can be overridden.

## Deliverables

Once you have all your tests in the green. Push to github pages and comment on the issue assigned to you with a link to:

  * the test on github pages
  * the repo
  * your blog post

## Go Further

__This is optional but would be a great learning exercise so if you have time, I strongly encourage you to try it.__

Make each vehicle constructor add methods to it's prototype and add tests to ensure they get added to descendants. For example Vehicle could have a method called `travel()` that returns __"goodbye"__ and SeaVessel could have a method called `setSail()` that returns __"ahoy"__ and you would test that Boat inherits both methods.

## Resources

  * [Classical inheritance with Object.create()](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Object/create#Example:_Classical_inheritance_with_Object.create)
  * [_.extend](http://underscorejs.org/#extend)
