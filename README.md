# Javascript Cut, Copy, Paste
In this example, you can see parts of the DOM tree being removed, duplicated, and placed elsewhere on the page. The HTML has an extra p element after the list, which contains a quote. It is moved to a new position under the heading. In addition, the first list item is detached from the list and moved to the end of it.

## Components that make the app run
* A jQuery selection is made containing the p element at the end of the page, and this is cached in a variable called $p.
* That element is copied using the .clone() method along with its content and child elements. It is stored in a variable called $clonedQuote.
* The paragraph removed.
* The cloned version of the quote is inserted after the h2 element at the top of the page.

## How to run the app locally
* In your terminal type
```
git clone https://github.com/bostonhuman/javascript-copy
```
* Open `cut-copy-paste.html` to run the app.
