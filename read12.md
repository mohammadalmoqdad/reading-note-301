# EJS Partials
* It is a function come in handy when you want to reuse the same HTML across multiple views, the best part of it that if you wanted something to be reflected on all pages Partials will do the job!

* Usaully it is used for the header and the footer, that because they are the same for all pages. So after building them in Partails folder and adding a page for the heade and footer we have to call them in all pages that contains the header and footer(moostly all pages) using the most important method here `inlude()`.

* The `<%- %>` tags allow us to output the unescaped content onto the page 
  -  the `-` is important when using the `include()` statement since you don’t want **EJS** to escape your HTML characters like ‘<’, ‘>’, etc….

