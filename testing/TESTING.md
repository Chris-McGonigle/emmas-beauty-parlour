# Testing for client website 'Emma's Beauty Parlour'

The following document outlines all testing carried out on the client website, Emma's Beauty Parlour. 

During the initial construction process, the Dev Tools functionality of Firefox was used to test CSS code initially, where it was then tweaked to the desired outcome.  

## Automated Testing

### Validator Testing

* HTML

HTML was tested using the [W3C Markup Validation Service](https://validator.w3.org/)

Four errors were found as detailed in the following screenshot:

![HTML testing results](./testing-images/html-testing.png) "HTML testing results" 

#### Error fixes

1. Stray /li tag was causing this error. Nested li element correctly in dropdown menu. Retested: ERROR PASSED.

2. Stray /i tag identified. Removed element causing error. Retested: ERROR PASSED.

3. Attribute polaroid caption not allowed on div at that point. Added additional div inside parent div to provide caption. Restyled CSS of caption. Retested: ERROR PASSED.

4. Stray div tag identified. Removed surplus div tag. Retested: ERROR PASSED.

5. Stray script start tag identified. Moved all script elements inside body tags of HTML. Retested: ERROR PASSED.

The HTML was then retested in it's entirety. All errors were found to be fixed and no new issues had arisen.

![HTML retest results](./testing-images/html-retest.png)"HTML retest results"


* CSS

CSS was tested using the [W3C CSS Validation Service - Jigsaw](https://jigsaw.w3.org/css-validator/)

One error and five warnings were found as detailed in the following screenshot:

![CSS Testing Results](./testing-images/css-testing.png) "CSS testing results"

#### Error and Warning fixes

1. On screens over 800px, flex-direction was set to 'revert'. Changed flex-direction value to 'row'. Retested: ERROR PASSED.

2. Font family names contained whitespace in error on lines 179, 297 and 354. Fixed font names to correct syntax. Retested: WARNING PASSED.


### Unfixed Bugs