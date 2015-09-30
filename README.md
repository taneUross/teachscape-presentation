About the Teachscape Design Guideline
=======================

When to use this repo and the styleguide:
* When you don't know where else to start building the front end.
* When building the front end for a story and you would normaly start with Boostrap - instead start with the styleguide and our compile.css that has the Teachscape overrides
* When the requirements or spec says "there a widget for that" or a custom component (styling not functional) has been created.


Important Links
-------------------------
GLOBAL CSS:
To find the global teachscape css, use the styles found in assets/less/compile.css.  These have our boostrap overrides that use our variables
<a href="https://github.com/Teachscape/teachscape-presentation/blob/master/assets/less/compile.css">https://github.com/Teachscape/teachscape-presentation/blob/master/assets/less/compile.css</a>

STYLEGUIDE (Copy code snippets):
To find various Boostrap and Teachscape custom components with example code to copy and paste, visit the styleguide here:
<a href="http://teachscape.github.io/teachscape-presentation/">http://teachscape.github.io/teachscape-presentation/</a>

TEACHSCAPE LESS VARIABLES
Front end best practices suggest that less variables are used instead of hard coded values (hex colors for example) so that we don't need to track down every instance in all the css to change our themes.
Found at _css/variables here is a link to our global variables: <a href="https://github.com/Teachscape/teachscape-presentation/blob/master/_css/variables/global_ts_variables.less">https://github.com/Teachscape/teachscape-presentation/blob/master/_css/variables/global_ts_variables.less</a>


Who is maintaining this repo
----------------------------
* Tane Ross tane.ross@teachscape.com  Lead User Experience Designer
* Jim

teachscape-presentation
=======================


dot.LESS custom files to edit
==============================
* custom-font.less
* custom-font-icomoon.less
* custom-ts.less


dot.LESS custom files that can be created, for example
===========================================
* custom-focus.less
* custom-(application).less