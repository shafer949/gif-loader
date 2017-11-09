# Gif Loader

This project contains starter files used to create a way to search for gifs using the [Giphy Api](https://developers.giphy.com/docs#operation--gifs-search-get) using vanilla JavaScript.

This project is used to enforce core concepts.  As such, successful completion of this project would mean that you are using the following techniques:

## The Task

Given the included stylesheet and html files, write JavaScript so that when a user enters text into the search bar and submits,
 a request for a gif is made and the image would appear beneath the input, replacing the previous gif.

* Proper usage of `const` and `let`. No usage of `var`
* Usage of arrow functions.  No usage of function declarations
* Grabbing the document items without reaching for jQuery
* *Fetch*ing data from the [Giphy Api](https://developers.giphy.com/docs#operation--gifs-search-get) without using a 3rd party library
* Attaching event listeners
* Usage of es6 template strings
* Handling asynchronous code via `callback`, `promises`, or `async/await`

### Assignments

To be completed after the above requirements are met.

As our project stands currently, the paragraph tag doesn't update to reflect the newly added gif.

* update the paragraph tag

Right now our API fetches a bunch of results when a request is made! Let's just limit that to 5.

* Limit the amount of gifs coming back to 5.

**If you attended one of my class sessions, then in your code, you have the line:**
 `searchGiphy(inputText)`

 After that line, we use `.then()` to have some code run.  What is that code doing? That make that more functional by extracting it out into its own function to `updateFields`.
* Remove the logic after the `.then()` and refactor it into its own function.