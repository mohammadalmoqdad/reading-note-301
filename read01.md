# Responsive Overview
* The idea or need of it comes from the crazy increasing in the number of people that are using phones which will become more than the people those are using the desktop applications.
* is focused around providing an intuitive and gratifying experience for everyone. .
* Responsive web design is broken down into three main components: including *flexible layouts*, *media queries*, and *flexible media*.
* Relative Viewport Lengths in CSS are :
  - `vw`: Viewports width
  - `vh`: Viewports height.
  - `vmin`: Minimum of the viewport’s height and width
  - `vmax`: Maximum of the viewport’s height and width.
* in media query Each media query may include a media type followed by one or more expressions.
  - Common media types include **all**, **screen**, **print**, **tv**, and **braille**.
* Logical Operators that are allowed in Media Queries are `and`, `not`, `only`.
  - EX: `media all and (min-width: 800px) and (max-width: 1024px) {...}`
### Mobile First :
- One popular technique with using media queries is called mobile first. The mobile first approach includes using styles targeted at smaller viewports as the default styles for a website, then use media queries to add styles as the viewport grows.
* Turning off the ability to scale a website is a bad idea. It harms accessibility and usability, preventing those with disabilities from viewing a website as desired.

# Float
* It is a CSS positioning property that is used to control the positions of the elemnts or their position in the flowof elements in the web page.
* Even if there are Strong tools like ***flex box*** and ***Grid*** the Float is still used and useful but in smaller instances 
* the propertity `clear` is really imporan when using floatbecause the property set on it will not move up adjacent to the float like the float desires, but will move itself down past the float.
* *Clear* property:
  * to clear the float after the floated element so they not moved from the wanted place to the float flow 
  * its values are either both, left, right and each one determine from which side the float will be removed.
