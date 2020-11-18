# Grid:
* firt property is `grid-column-start` which can have a number as a value of it.
  - it starts counting from -1-.
* `grid-column-end` it used to appply same style on several elemnts and used with the first menshioned prperety.
  - need to add aditional one to reach the wanted colomn except when using the word ***span*** with the vlaue it wouls be starting from -1- too. 
* `grid-column-end` can be used also is the end value has to be greater than the start value and also the value couls be integer.
* `grid-column` can have an integers with **/** between them which means that counting grid lines will start from fist ineger to the second.
* `grid-row-start` similar to `grid-column-start` but work vertically.
* `grid-area` is shorthand for the `grid-column` and the `grid-row`.
  - Th value should be ordered like :  grid-row-start, grid-column-start, grid-row-end, followed by grid-column-end.
* `order` to define where the place of this elemeent will be out of the general ordering.;
  - it may take *-value* if thewanted pace is at the begining .
* `grid-template-columns`,`grid-template-rows` used for the size of each part or grid-box; 
  - it takes 5 values usually or as wanted.
* `grid-template-columns` can take the value: repeat(numberOfRepating, width of each box);

