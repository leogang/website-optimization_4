This website was largely pre-built by Udacity, but I optimized it for a >60 page fps and a >90 Google Developers PageSpeed Insights score.

Optimizations:

    Optimized order of render-blocking elements (js and css) with DOM tree construction steps in mind
    Applied async and/or defer where appropriate
    Minified the css and js files
    Compressed unnecesarily large image file sizes
    Reduced the number of background pizzas generated on each page scroll to the minimum number displayed at any given time
    Improved speed of changePizzaSizes() by moving unchanging variables outside of for loops
    Improved speed of updatePositions() by moving unchanging variables outside of for loops

Build Steps:

    Build via index.html
