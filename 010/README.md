# 02/12/15

___This homework is due by 8am, on 02/16/15___

### Learning Objectives

After completing this assignment, you should:

* Have a deep understanding of layout
* Understand JavaScript Templating (using Underscore or Lodash)
* Demonstrate strong ability to navigate through a large block of JSON data

## Homework

### Part 1

Re-Create An Etsy Page - https://www.etsy.com/search?q=whiskey

> Specifically you need to focus on the search bar and the main content of items.

1. Utilize the data for whatever search term you use - [DATA HERE](https://api.etsy.com/v2/listings/active?api_key=h9oq2yf3twf4ziejn10b717i&keywords=whiskey&includes=Images,Shop)
2. Use an [underscore template](http://underscorejs.org/#template) for creating each product
3. You should be able to type in a search term and display the product results.
4. I have supplied you with a function that will fetch the data for you.
5. Everything should be styled as closely as possible, including the Header/Footer
6. You should implement hover events and link the items to their proper Etsy product pages
7. You can just put random links in your sidebar.
8. The only functionality that needs to work is the search bar and filtering results
9. Lastly, worry about the structure first, the JS second and the fine details of the design last

I have added a main.js that has a function that you can use for fetching the data from etsy. You can optionally supply keywords.

examples:

```javascript
// without keyword
getData(function(data){
  console.log(data.results);
});

// with a single keyword
getData("whiskey", function(data){
  console.log(data.results);
});

// with multiple keywords as array
getData(["whiskey","beer"], function(data){
  console.log(data.results);
});

// with multiple keywords as string
getData("whiskey beer", function(data){
  console.log(data.results);
});
```
I have also added an index.html file that loads jQuery, underscore, and the main.js

## Deliverables

1. Push to Github and comment with a link to your repo
2. Deploy to Github Pages and comment with a link to that


## Optional
1. Create your own API token by signing up as an [Etsy developer](https://www.etsy.com/developers/)
2. Pull the categories from the data to create the sidebar, with links that filter the listings.
3. Implement the sorting dropdown.


## Resources

* [Etsy API Documentation](https://www.etsy.com/developers/documentation/reference/listing)
* [Etsy Payload Example](https://api.etsy.com/v2/listings/active?api_key=h9oq2yf3twf4ziejn10b717i&keywords=whiskey&includes=Images,Shop)
* [Etsy Page Example](https://www.etsy.com/search?q=whiskey)
* [Underscore Template](http://underscorejs.org/#template)

