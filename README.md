# jbav

## Remove unnecessary padding from main region
* The main region contains excess padding that pushes down the content by 80px. This is not noticeable at higher resolutions, but becomes a problem for mobile.

## Manually set image height for resolutions with width of < 480px
* WordPress is automatically scaling the main header image based on screen resolution.

* At mobile screen sizes this scaling is off

* This overrides that scaling with a static height of 250px on smaller screens

## Usage:
* Adding contents of style.css to your WordPress style sheet will implement these fixes