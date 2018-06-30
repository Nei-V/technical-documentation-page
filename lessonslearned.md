1. Tried to apply more classes and use them instead of targeting the elements name or tag

2. showing code - especially HTML. You have to escape the HTML, so what I did was to use <pre> (preformated text) and inside it the <code> tag. this in adition to using <span> around the signs like " <" or ">". There are shortcuts in VS code to surround some text with tags using emmet, and this makes it managable. 

3. another way to escape the tags is using the escape char (like &lt;) . the easiest way to do it is to find a site that does that for you like https://www.freeformatter.com/html-escape.html  . Just checkit in case there are special characters that might brake the site's escaping mechanism (that's probably base on regex rules.)

4. in HTML5 you can use H1 more times, for example in different sections because of the semanti web

5. using overflow-x, overflow-y  to use scrollbars. you can use hidden or scroll. aslo, you can use unset property if you want to cancel hidden or scroll (for examaple in a media query). It some cases you can use be used with overflow:none .

6. using text decoration:none to remove underline,

7. using vw unit (that's 1 precent of the view width) - I sometimes didn't manage to get it work as I expected.

8. more usage of grid, flexbox and media queries.

9. usage of position:fixed - this taks the element out of the document flow, so you have to make up for it using bigger padding on subsequent elemnts.