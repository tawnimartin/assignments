# 03/18/15

___This homework is due by 8am, on 03/19/15___


## Homework

__Pair Programming__: This assignment is meant to help practice communication and thinking through problems. You are to pick a partner, and rotate between the roles of _driver_ and _navigator_.

Your task is to build a list of bugs, ahem, _features_ and display their progress. Each issue has a progress level from 0 to 1 representing how complete it is; 0 indicating no work is done yet and 1 indicating complete. Load the data into a Backbone collection, and display it on the screen.

_The catch_. This data needs to be rendered twice. One using Backbone.View and the other using React. Come up with a creative way for displaying the progress. Render each part into it's own container on the body like:

```html
<body>
  <div class="backbone-view"></div>
  <div class="react-view"></div>
</body>
```

#### Part 0

Delegate among yourselves who will drive for creating the collection and loading in the data etc.

#### Part 1

Student A writes the code for the Backbone.View, but Student B tells Student A what code to write.

#### Part 2

Student B writes the code for the React view, but student A tells student B what code to write.


## Deliverables

Just create a single repo, I do not care whose name it is under, but I want to see commits by both students. Deploy to github pages and comment on issue assigned with links to both.
