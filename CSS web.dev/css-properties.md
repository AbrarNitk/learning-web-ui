# Properties

This document contains my random learning.


# `display`

The `display` attribute in CSS is used to control how an element is displayed in the layout of a web page. 
It determines the type of box or formatting context an element generates, which affects how other 
elements interact with it and how it is rendered on the page.

- `block`: The element generates a block-level box. It starts on a new line and takes up the full 
  available width of its parent container.
- `inline`: The element generates an inline-level box. It flows within the text of a line and does 
  not start on a new line. It only occupies the space necessary to contain its content.
- `inline-block`: The element generates a block-level box, but it behaves like an inline element. 
  It flows within the text and does not start on a new line, but it allows you to set width and height properties.
- `none`: The element is not displayed at all, effectively removing it from the layout. It won't take up any 
  space, and the element will be hidden from the user.
- `flex`: The element generates a flex container. It enables the use of flexbox properties to control the 
  layout of its child elements.
- `grid`: The element generates a grid container. It enables the use of CSS grid properties to control the 
  layout of its child elements.



# `display: flex`

- This property is applied to the container to create a flex container. It enables the Flexbox layout 
  for its child elements.
- `flex-direction`: This property defines the main axis direction and the flow of the flex items. 
  It can take one of four values: row (default), row-reverse, column, or column-reverse
- `justify-content`: This property aligns the flex items along the main axis of the container. It can take 
  values such as flex-start, flex-end, center, space-between, space-around, and space-evenly.
- align-items: This property aligns the flex items along the cross axis of the container. It can take values 
  such as flex-start, flex-end, center, baseline, and stretch.
- `align-items`: This property aligns the flex items along the cross axis of the container. It can take 
  values such as flex-start, flex-end, center, baseline, and stretch.
- `flex-wrap`: This property controls whether flex items wrap to multiple lines if they overflow the container. 
  It can take values like nowrap (default), wrap, or wrap-reverse.
- `flex-grow`: This property specifies how flex items grow relative to each other to fill the available 
  space. It determines the distribution of remaining space along the main axis.
- `flex-shrink`: This property specifies how flex items shrink relative to each other when the available 
  space is limited.
- `flex-basis`: This property specifies the initial size of the flex items before the remaining space is 
  distributed.

## Reference

- Flex Direction: https://css-tricks.com/almanac/properties/f/flex-direction/
- [Responsive Layouts](https://css-tricks.com/responsive-layouts-fewer-media-queries/)