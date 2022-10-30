# What is The Resto ? 

This is a mockup of a random restaurant website, whose working base (assets etc..) is provided in the #FromScratch course on podia by Julien Azambourg.

## How did I proceed ?

### HTML :

* I created the HTML block by block, using consistent class names as much as possible as well as semantic tags for SEO.

### SCSS :

* I chose to use Scss with a 7-1 pattern although incomplete.
* Each style element is contained in a single parent block, with the exception of the cards inherent in their containers.
* **In order to maximize the use of style sheets with a tree structure thanks to scss, certain style blocks have been optimized against the 7-1 architecture**.

### About responsive :

* There is a design for the desktop version and another for the mobile version.
* I made sure to have a break point at 780px to avoid line overflows and other breaks.
* Some elements like the footer whose background is provided as a photo forced me to push the breakpoint to 790px, otherwise I would have to make a sacrifice on the height of the footer and therefore on the resemblance with the model.

## Improvements :

Many improvements are needed to make this project a success. 
I've consider this exercise was placed in the context of model integration rendering as an MVP.
**These improvements will be added over time, we can imagine this in particular :**

* A refactoring of the code with the addition of mixines as well as clearer variables.
* Add animations, hover, keyframes.
* To be pixel-perfect with respect to the model (here it was rather a waste of time with respect to my objectives in this exercise).
* Export and develop a larger fictional project with React, which could work with a fake database and potentially use Redux if needed.
* For sure an optimized SEO with the addition of more adequate metas in the case of a deployment

*As changes are made, they will be visible on the github page, via the various commits, and the improvements will be annotated with :* :white_check_mark:

##About my goals through this creation :

* Maintaining a decent level of use as I hone my React skills. In order to remain versatile, and to learn continuously.
* Improve the structure of my code by optimizing the tree structure of my SCSS.
* Create beautiful things of course.
