# Gif Loader

This project contains starter files used to create a way to search for gifs using the [Giphy Api](https://developers.giphy.com/docs#operation--gifs-search-get) using vanilla JavaScript.

This project is used to enforce core concepts and builds off of the `master` (starter) branch, so it is encourages that those tasks be completed since these challenges build off of that.

As with the last project, successful completion of this project would mean that you are using the following the task with these techniques in mind:

* Proper usage of `const` and `let`. No usage of `var`
* Usage of arrow functions.  No usage of function declarations
* Grabbing the document items without reaching for jQuery
* *Fetch*ing data from the [Giphy Api](https://developers.giphy.com/docs#operation--gifs-search-get) without using a 3rd party library
* Attaching event listeners
* Usage of es6 template strings
* Handling asynchronous code via `callback`, `promises`, or `async/await`

## The Task

We just received notice from QA that our last project is good, but only having one gif image pop up isn't good enough--the people want options!

* When a user searches for a GIF, 5 images will show
* Given that 5 images have shown, their related paragraph tags show their respective url.

If the new developer on our team changes our url, or the server doesn't respond, then the fetch request fails.

* `.catch` the error and log out a `String` to the console.

### Assignments

To be completed after the above requirements are met.

* When a user enters the page, `.focus` should be given to the `input` tag.

* When a user submits the form, _focus_ should be taken away.

Currently, if our `fetch` request rejects, then we simply log out a string. Let's make this more apparent to the user:

* Given a rejected promise, then the `.catch` method should update the paragraph text with something that lets the user know.

Feel free to research your own solutions to solve the problems, below are methods that may be of particular use:

`createElement()`, `appendChild()`, `removeChild()`, `blur()`

## Brownie Points

Let' Make this more future proof! Who knows the next time QA will say they want 10 or 3 or 7 GIFs to show up.

* Given a user has landed on the page, another input will show up inside the search form.
* When a user submits the form, then number inside the input will be used as the `limit` for the api to search for
* Given that `limit` is now a variable, the amount of GIFs that display is up to the user.
* Regarding the newly added input, set a `max` and `min` so this `range` has reasonable limits.

Lastly, remember that [MDN](https://developer.mozilla.org/en-US/) is the defacto resource for JavaScript (and more) and appending a method or function name to MDN in your search bar is a great way to get documenation on what you want ie "Google: MDN createElement"