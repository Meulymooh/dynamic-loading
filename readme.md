# Dynamic Loading - Starting with Ajax

Link: https://meulymooh.github.io/dynamic-loading/index.html


## Objectives of the exercise

* Learn about Ajax,
* Make a simple load request with Ajax (3 pages + 1 with a navbar that calls the other pages to load in a div),
* Add a loading icon,
* Scroll to top before loading new page.

## Personal objective

Being able to use the result of the exercise later for other purposes.

## Documentation

Understanding AJAX as a Beginner Web Developer: https://www.codementor.io/sheena/ajax-tutorial-web-development-du107rzaq

JSON and AJAX Tutorial: With Real Examples: https://youtu.be/rJesac0_Ftw

## Image resources

https://unsplash.com/

## What I learned / reinforced

* Parallax: https://www.w3schools.com/howto/howto_css_parallax.asp
* Box shadow (CSS): https://developer.mozilla.org/fr/docs/Web/CSS/box-shadow
* Cover for background image (CSS): https://www.alsacreations.com/astuce/lire/1216-arriere-plan-background-extensible.html
* ScrollTo() (JS + CSS): https://developer.mozilla.org/en-US/docs/Web/API/Window/scrollTo

## Difficulties

Ajax: 
* After loading the content in my div, the navbar's shape changed and I got an XML error in the console. I thought my JS/Ajax code was wrong and tried to fix it, but it didn't work. Turned out my JS/Ajax code was right. I just created 3 full HTML pages (with "head" and "body" tags) instead of just writing pure content. 
* I initially used 3 Ajax functions to call the pages individually. It took me a while to figure out how to only write 1 for all 3 pages. I solved it by adding the same attribute to every page.

Scroll to top: After trying complicated things, turns out there's a very simple way to perform a scrolling effect with one line of JS and one CSS property (see link above). :-)

Parallax (personal addition): I initially performed a customized parallax effect using pure CSS via the "transform: translateZ" property. But once the content of the 3 pages was nested in the div of index file, the effect didn't work anymore and the content had display errors. I tried to solve the problem by adding the "preserve-3d" and "perspective" properties to my nesting div, but it didn't work either. So in the end I did it the basic way as shown on W3School, but it's not as nice as it originally was. :-(