# EJS
* it stands for *Embedded JavaScript templating*.

* The path pacckage is taking two paths and join them 
* the function render going to render html elements inside the ***.ejs*** file.
* we can send values to the file of th ***.ejs*** by writting htem in the render function after the name of the ***.ejs*** file that I will take the HTML content from it.
  - The send variable name could be anydata type but whan send it, it should by the an obect roperty.
  - to recieve that variable and know it is a variable it should be put like this: `<%= variableNameinEJS %>`.
* forthe loops they should be written in hte EJS file and send them te values by writting the loop it self like this `<%= for(var x in y){ } %>` `
  - we can close te for without do that in te same line and may be their is some html code between them.
* HTML content and ejs that is written in the `layout.ejs` will be rendered in each page ofhte routes.
* `include` function is used in ***ejs*** to bring the code that is written inside the included file and run it .

# Google Books API's
* it is just connection to API's of google and ask them for information of a user, and when do that the user will be asked if the application he use is authenticaed if yes then google will send the information of that user in two ways,*private* which will need authentication and 2.0 token, or must provide either the API key or an OAuth 2.0 token, or both.
 