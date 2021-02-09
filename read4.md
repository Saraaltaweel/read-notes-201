## Links

* Links are created using the `<a>` element. Users can click on anything between the opening `<a>` tag and the closing `</a>` tag. You specify which page you want to link to using the href attribute.
example:
`<a href="www.youtube.com">youtube</a>` here when click on youtube it will open youtube page.
You can use any link .
You can use it in tables and in list paragraph .....

## Target
If you want a link to open in a new window, you can use the target attribute on the opening `<a>` tag. The value of this attribute should be _blank.
example:
`<a href="http://www.imdb.com" target="_blank">` Internet Movie Database`</a>` (opens in new window)

## Layout
* It is common to group a number of elements together inside a `<div>` For example, you might group together all of the elements that form the header of a site (such as the logo and the main navigation). The `<div>` element that contains this group of elements is then referred to as the containing element.

## Functions
* These statements update the message at the top of the page. The function acts like a store; it holds the statements that are contained in the curly braces until you are ready to use them. Those statements are not run until the function is called. The function is only called on the last line of this script.
example:
`var msg = 'Sign up to receive our newsletter for 10% off!';`
`function updateMessage() {`
`var el = document.getElementByld('message'};`
`el .textContent = msg;`
`}`
`updateMessage(};`

## FUNCTION EXPRESSIONS
 we can make calculate process in js such as:
`function area (width, height)`
`return width * height;`
`};`
`var size= area (3, 4) ;` 
here will be the answer 12
