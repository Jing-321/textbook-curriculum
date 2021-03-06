# Seven Wonders JavaScript

This project will be very similar to the [Seven Wonders exercise](https://github.com/AdaGold/api-exercise-seven-wonders) we completed when first learning about APIs. This time we'll be working in JavaScript.

This is an in-class exercise, and does not require a pull request.

## Learning Goals
By the end of this project, students should be able to...

- Use `axios` to read data from an API in JavaScript
- Parse through an API response in JavaScript and extract desired information
- Add data from an API to a web page

## Details

Given the following array of wonders:

```javascript
sevenWonders = ['Great Pyramid of Giza', 'Gardens of Babylon', 'Colossus of Rhodes', 'Pharos of Alexandria', 'Statue of Zeus at Olympia', 'Temple of Artemis', 'Mausoleum at Halicarnassus'];
```

<!--
Build a web page to display the list of wonders along with their locations. Your page should include an HTML file and a JavaScript file.
-->

The JavaScript should take the list of wonders, run them through the [Location IQ](https://locationiq.com/) API, and add a DOM element to the page for each including its name and coordinates.

Feel free to use your Ruby solution as a starting point. The learning goal here is working with axios and rendering the results in a web page, not deciphering the Google Maps API.
