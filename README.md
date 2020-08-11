# SASS
## GOAL:
* Being able to explain what a CSS-Preprocessor is
* Generate some CSS from your CSS preprocessor (SASS)
* Being able to minify your CSS output
* Knowledge of the following SASS features:
  * Variables
  * Mixins (Functions)
  * Nesting
  * Partials & Import
  * Extend/Inheritance
  * Operators (Math) 
 
### Your mission is to rewrite the example.css to a scss file with the following changes:

### Part 01
* Make one mixin for the 3 lines of the box-shadow styling.

* Make the general padding the same everywhere with one variable. (red=16px, blue=8px), the footer h6 should have double the padding of the other elements. Use "operations" to do this. Do NOT hardcode the padding inside your scss.

* Nest the styling rules of grouped elements, like the sections in the Article. Make use of extend to re-use the same CSS for the "success", "error" and "warning" messages.

### Part 02
* In the HTML, add 2 links called "blue" & "red".
* Clicking one of the 2 links should change the text to red/blue with a good matching background (keep it readable)! All the other CSS should be the same, to do this combine SASS variables with file imports.
Take some time to think how to do the structure of this exercise, and how many files you will need. It might be good to discuss this with your fellow juniors!

### URL to page: https://nikkizol.github.io/SASS/
