# jbav

## Remove unnecessary padding from main region
* The main region contains excess padding that pushes down the content by 80px. This is not noticeable at higher resolutions, but becomes a problem for mobile.

## Manually set image height for resolutions with width of < 480px
* WordPress is automatically scaling the main header image based on screen resolution.

* At mobile screen sizes this scaling is off

* This fix overrides that scaling with a static height of 250px on smaller screens

## Scale down large text when larger than screen size
* One of the headers had a font size that was larger than the width of most mobile devices

* Set font size of header and subheader to be smaller when screen width is < 480

## Usage:
* Adding contents of style.css to your WordPress style sheet will implement these fixes

* Number values can be changed to reach desired outcome