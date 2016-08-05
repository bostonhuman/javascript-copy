# Javascript Cut, Copy, Paste
In this example, you can see parts of the DOM tree being removed, duplicated, and placed elsewhere on the page. The HTML has an extra p element after the list, which contains a quote. It is moved to a new position under the heading. In addition, the first list item is detached from the list and moved to the end of it.

## Components that make the app run
A jQuery selection is made containing the p element at the end of the page, and this is cached in a variable called $p.
