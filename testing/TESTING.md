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

1. On screens over 800px, flex-direction was set to 'revert'. Changed flex-direction value to 'row'. 

Retested: ERROR PASSED.

2. Font family names contained whitespace in error on lines 179, 297 and 354. Fixed font names to correct syntax. 

Retested: WARNING REMOVED.

3. The transform properties of the polaroid client image presented with an unknown vendor extension warning. Removed -ms and -webkit transform extensions. 

Retested: WARNING REMOVED.

The CSS was then retested in it's entirety. All errors were found to be fixed and warnings removed. No new issues had arisen.

![CSS retest results](./testing-images/css-retest.png) "CSS retest results"

### Accessibility testing

To test for any accessibility issues, the web accessibility evaluation tool (WAVE) by [WebAIM](https://wave.webaim.org) was used on each page. 

The following results were found.

#### Homepage

![Homepage accessibility results](./testing-images/homepage-accessibility.png)

1. The ten errors returned were all due to missing aternative text in the image map area. As this was embedded using a Google API, I am unable to address these errors at present until I have developed further skills in their use. 

Retested: UNABLE TO RETEST.

2. 12 low contrast errors were found on the page. Upon closer investigation, these errors were found to be exclusively on the page headings. Possible solutions were to darken the text colour, or to provide a contrasting background to the headings to help them stand out. Using [Google Colour picker](https://htmlcolors.com/google-color-picker), the original colour #34a0a4, was adjusted to make it slightly darker, whilst still maintaining the original design brief of using calm natural colours such as greens and creams. #27787a was selected and tested. 

Retested: CONTRAST ERRORS FIXED