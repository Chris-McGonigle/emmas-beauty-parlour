# Testing for client website 'Emma's Beauty Parlour'

The following document outlines all testing carried out on the client website, Emma's Beauty Parlour. 

During the initial construction process, the Dev Tools functionality of Firefox was used to test CSS code initially, where it was then tweaked to the desired outcome.  

## Automated Testing

### Validator Testing

* HTML

HTML was tested using the [W3C Markup Validation Service](https://validator.w3.org/)

Four errors were found as detailed in the following screenshot:

![HTML Testing Results](./testing-images/html-testing.png) "HTML testing results" 

#### Error fixes

1. Stray /li tag was causing this error. Nested li element correctly in dropdown menu. Retested: ERROR PASSED.

2. Stray /i tag identified. Removed element causing error. Retested: ERROR PASSED.

3. Atribute polaroid caption not allowed on div at that point. Added additional div inside parent div to provide caption. Restyled CSS of caption. Retested: ERROR PASSED.


* CSS

CSS was tested using the [W3C CSS Validation Service - Jigsaw](https://jigsaw.w3.org/css-validator/)

One error and five warnings were found as detailed in the following screenshot:

![CSS Testing Results](./testing-images/css-testing.png) "CSS testing results"

### Unfixed Bugs