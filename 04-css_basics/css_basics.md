# CSS (Cascading Style Sheets)
* Style Sheet - a list of CSS rules / rule sets
  * div {<br>
  color: red;<br>
  margin: 20px;<br>
} <br><br>
p {<br>
  font-weight: bold;<br>
}
* Selectors -  how we target the elements that we want to style on a web page, i.e., div and p from the above example
  * selectors can also be classes and attributes
* Declarations - list of key-value pairs, i.e., color: red; from the example above
* Rules - made up of selector and declarations
  *  div {<br>
  color: red;<br>
  margin: 20px;<br>
}

## Colors/Hex Codes
* Colors - e.g., white, black, yellow, and green
* Hex Codes - e.g., #42f4f1 and #ab55ef
  * The first two channels make up the red color, e.g., 42 in #42f4f1
  * The second two channels make up the green color, e.g., f4 in #42f4f1
  * The last two channels make up the clue color, e.g., f1 in #42f4f1
  * 0 represents the darkest shade for each channel
  * f represents the brightest shade for each channel
  * #000000 is black
  * #ffffff is white
  * #440000 deep maroon color
  * #EE0000 brighter red

## Inline Elements
* Don't take up any more room than their content needs
* span, img, strong, em, a, and more...

## Block-Level Elements
* Take up the whole width of a page regardless of content
* * p, div, h1, h2, h3, ul, li, and more...

## Nesting Elements
* Often see inline elements nested in block-level elements
* But block level elements shouldn't be nested in inline elements
* You can nest block-level elemnts in other block-level elements though

## Margin & Padding
* Margin controls the space outside the element border
* Padding controls the space inside the element border
* For block-level elements margin and padding is used all around the element, i.e., the top, bottom, left, and right
* For inline elements the margin is used only on the left and right and the padding is used on the top, bottom, left, and right
* When the page is made smaller inline elements collapse on top of each other
* If there is a margin for two block-level elements that are next to each other the largest margin is chosen (margin collapse)
* Setting the display of inline elements to be inline-block allows inline elements to have margin at the top and bottom

## Summary
* What CSS is and how to add it to a webpage
* Basic selections and some different declarations/properties
* Hex codes and the VS Code color picker
* Inline and block-level elements (and inline-block)
* Margin and Padding