A website is a collection of web pages available on the internet using a browser. Webpage is a single page that holds information in the form of a text or media.

The building blocks of a website are:

1. HyperText Markup Language (HTML)
2. Cascading style sheets (CSS)
3. JavaScript (JS)

# HTML

Consist of html elements defined by tag names and its opening and closing tags (together with their content)

## Types of HTML elements:

1. Void or empty elements eg: <hr>
2. Raw Text or text-only elemts eg: <img src="" alt = ""/>
3. Normal elements eg: <p> text </p>

## Semantic and non-semantic elements

### semantic elements:

Document structure tag <header >, <footer> <main> <nav> <section> <article> <aside>
Textual meaning tag <h1> <cite> <blockquote> <mark> <strong> <time>
media type tag <audio> <video> <picture>
correlation tags <ul> <figure><address>

## CSS

Cascading style sheets, or CSS, defines how HTML elements are to be displayed using certain rules. A CSS rule set consists of a selector and a declaration block. The selector points to the HTML element you want to style. The declaration block includes a property name and a value separated by a colon. The declaration block may contain one or more declarations separated by semi-colons.
Three ways to syyle an HTML element: inline style, embedded or internal style (defined in the head section of an HTML page within a style element.) and external style
CSS selectors - ID (#idname), class (.classname), type (div, span etc) and attribute selector

Every html element is interpreted like a box with four parts, margin, border, padding and content. This representation is called the CSS box model.

The CSS display property sets an element as a block or an in line element and the layout used for its children such as flow layout, grid or flex. The values taken by the CSS display property are block, in line block, flex, in line flex, grid, in line grid and flow route. Now let's learn about the different values of display properties in detail. The block property is used to display an element as a block. In line block is used to display an element as an in line level block container. Flex is used to display an element as a block level flex container. In line flex is used to display an element as an in line level flex container. Grid is used to display an element as a block level grid container. In line grid is used to display an element as an in line level grid container.

Can you take out HTML elements from the normal document flow? Yes, with the help of floats.

A margin can be added to the float element to push the text away, but a margin cannot be added to the text to move it away from the float element. This is because a floated element is taken out of the normal flow and the boxes or the other elements run behind the float.

Various types of positioning in CSS are static, absolute, relative, and fixed and sticky.

Static positioning is the default positioning that every element gets. It only involves putting an element into its normal position in the document layout flow. tatic positioned elements are not affected by the top, bottom, left, and right properties.

In absolute positioning, an element is positioned relative to the nearest positioned ancestor, and if an element has no positioned ancestor, it uses the document body and moves along with page on scrolling. One of the use cases of absolute positioning is adding a caption to an image. Any content added after the image tag is in normal flow, and hence it appears in the next line following the image. To write a caption over the image, use absolute position to fix this problem.

Relative positioning is like static positioning but once the positioned element has taken its place, the final position including the overlap feature can be modified. Setting the values of the top and left properties of a relatively positioned element moves the element away from its normal position like it does in absolute positioning, but over here, the other content elements do not adjust their positions to fill in the gap left by the recently moved element.

Finally, fixed positioning usually fixes an element in place relative to the visible portion of the viewport hence it always stays in the same place even if the page is scrolled. Fixed positioning works the same way as absolute positioning. The key difference between them is that while absolute positioning fixes an element relative to its nearest positioned ancestor, fixed positioning fixes an element in a place related to the visible portion of the viewport.

Relative positioning behaves like static positioning unless you add some extra properties.
