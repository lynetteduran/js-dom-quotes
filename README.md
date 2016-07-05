# js-dom-quotes
## Set up

1. Clone this repo and `cd js-dom-quotes`
-  Get the jQuery branch locally by typing `git checkout -b jquery origin/jquery`
- Open the index page in your browser: `chrome index.html`
- Add jQuery to the page. ([You can use this CDN](https://ajax.googleapis.com/ajax/libs/jquery/2.2.4/jquery.min.js))
- Open Chrome's developer tools: <kbd>command + option + j</kbd>

## Exercise - Selecting DOM elements

This is an exercise in finding elements on the page (in the DOM).

Your task is to write javascript **in the console** to retrieve the objects which represent these elements.

### Part 1

1. Select the `<body>`
- Select the `<header>`
- Select all of the elements with class "quote"
- Select all of the subject elements
- Select the navigation links
- Select all the quotes in the "life" section.
- Select the 'Quotes About Motivation' heading
- Select the `<p>` element containing the **second** Mark Twain quote

### Part 2

Do the same as before, but this time **with no spaces or colons in `$( )`**. That is: retrieve the target element(s) **using only DOM traversal methods** from [jQuery's documentation](http://api.jquery.com/category/traversing/tree-traversal/).

#### OK:

```js
$(".life").find(".quote");
```

#### Not OK:

```js
$(".life .quote");
```
