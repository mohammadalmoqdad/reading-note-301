# Mustache:
  - is a logic-less template syntax.
  - It works by expanding tags in a template using values provided in a hash or object.
  - Mustache is NOT a templating engine. Mustache is a specification for a templating language. 
  - *Mustache Express* lets you use Mustache and Express together easily.
![img]('https://miro.medium.com/max/700/1*LbqYj87xlazySm6wE0Q2lA.png')



# flexbox:
* The direction of the children of the flex are:
  - row (default): left to right in ltr; right to left in rtl
  - row-reverse: right to left in ltr; left to right in rtl
  - column: same as row but top to bottom
  - column-reverse: same as row-reverse but bottom to top
  - By code they are written like: 
    - ` flex-direction: row | row-reverse | column | column-reverse;`
* Wrapping the content of flexbox done by:
  - nowrap (default): all flex items will be on one line
  - wrap: flex items will wrap onto multiple lines, from top to bottom.
  - wrap-reverse: flex items will wrap onto multiple lines from bottom to top.
* justify-content:
  -flex-start (default): items are packed toward the start of the flex-direction.
  -flex-end: items are packed toward the end of the flex-direction.
  -start: items are packed toward the start of the writing-mode direction.
  -end: items are packed toward the end of the writing-mode direction.
  - left: items are packed toward left edge of the container, unless that doesn’t make sense with the flex-direction, then it behaves like start.
  - right: items are packed toward right edge of the container, unless that doesn’t make sense with the flex-direction, then it behaves like start.
  - center: items are centered along the line
  - space-between: items are evenly distributed in the line; first item is on the start line, last item on the end line
  space-around: items are evenly distributed in the line with equal space around them. Note that visually the spaces aren’t equal, since all the items have equal space on both sides. The first item will have one unit of space against the container edge, but two units of space between the next item because that next item has its own spacing that applies.
  - space-evenly: items are distributed so that the spacing between any two items (and the space to the edges) is equal.