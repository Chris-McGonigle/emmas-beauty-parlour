# Emma's Beauty Parlour

Emma's Beauty Parlour is a sole trader beautician business based in Tempo, County Fermanagh, Northern Ireland.

Following a hiatus from work due to a pregnancy and the covid pandemic, the client is recommencing business, but has moved from rented retail premises to premises adjoining her dwelling house.

Until now the client had been using social media channels and word of mouth to drive business leads, but during the pandemic she seen how useful a website was for her competitors during lockdown and now wants to get one set up for her own business.

## Site Design Considerations


### Client Expectations

The basic functions that the client wants the website to feature are:
* a list of the services provided (including pricing structure and any relevant Health & Safety Information)
* a CV/professional experience section
* photos of procedures and/or finished product photos
* detail the new business location
* a section for client testimonials
* a contact/enquiry form

The client wishes the site to convey a feeling of peace and relaxation as is in keeping with the overall ethos of the business and the sector in general.

The client also wishes to have the ability to include extra functionality at a future date, including online booking and eventually an e-commerce section.

If possible, the client also wishes to be able to monitor the traffic to the site.

The website is aimed at a female audience, who make up 95% of the clients custom.

### User Stories/Expectations

1. As a user, I want to easily ascertain the purpose of the website.
2. As a user, I want to be able to easily find out the services on offer.
3. As a user, I want to be able to find out the cost of each service provided. 
4. As a user, I want to be provided with a short description about each service and the time it will take.
5. As a user, I want to be provided with directions to the business.
6. As a user, I want to be able to easily find the business contact details. 
7. As a user, I want to be able to find social media links to the business.
8. As a user, I want to be able to provide feedback or comment through the site without having to exit and use my mail client.
9. As a user, I want to be able to navigate through the site freely, in a manner which is easily understood.
10. As a user with disabilties, I want to be able to navigate through the site freely without obstruction.
11. As user, I want to be able to view the website on any of my devices without any loss of functionality.


<!-- Discuss colour pallette choices-->


## Wireframes

### Homepage

![Desktop Version](./assets/wireframes/homepage-desktop.png)

![Mobile Version](./assets/wireframes/homepage-mobile.png)

### Services Offered Pages

![Desktop Version](./assets/wireframes/services-pages-desktop.png)

![Mobile Version](./assets/wireframes/services-pages-mobile.png)

### Contact Us Page

![Desktop Version](./assets/wireframes/contact-form-desktop.png)

![Mobile Version](./assets/wireframes/contact-form-mobile.png)


## Features
<hr>

### Initial Deployment Features

* Navigation Bar

  * Each page contains a fully responsive identical navigation bar at the top of the screen.
  * Identical styling helps to promote an overall inclusive feel to the site, and pulls pages together across a common theme.
  * The bar contains links to all other pages of the site, enabling the user to quickly navigate through the site without having to utilise their browser navigation buttons.  

* Landing Page Image

* Services Pages

* Location Map

* Contact Form

* Footer

### Future Features

* Online Booking

* Ecommerce Site

## Technologies Used

* HTML5
* CSS3
* Javascript (For Google Map in Location Section and Contact Form Submit Confirmation)
* Balsamiq
* Adobe Photoshop
* Firefox Developer tools
* Google Chrome Developer tools
* Google analytics
* JSFiddle
* Github
* Gitpod
* Favicon.cc
* W3C Markup and Jigsaw validation tools


## Testing

All technical testing carried out during the lifetime of this project can be found by following this link to the dedicated [Testing documentation](../testing/testing.md)

### Client and User Expectation Testing

#### Client feature expectation testing

1. a list of the services provided (including pricing structure and any relevant Health & Safety Information)
  * Result: TEST PASSED
    * All services provided by the client are highlighted on the homepage, and also have dedicated pages for each service

2. a CV/professional experience section
  * Result: TEST PASSED
    * A section about the client including details of their qualifications and work history is included on the homepage

3. photos of procedures and/or finished product photos
  * Result: TEST PASSED
    * Photographs of each service have been included on the homepage and also each dedicated service page.

4. detail the new business location
  * Result: TEST PASSED
    * a map to the clients business premises and text directions have been included on the homepage

5. a section for client testimonials
  * Result: TEST PASSED
    * client testimonials regarding each individual service are included on each respective page

6. a contact/enquiry form
  * Result: TEST PASSED
    * a contact form has been included on a separate page, and is linked to from all other webpages on the site

#### User Stories/Expectations

1. As a user, I want to easily ascertain the purpose of the website.

  * Result: TEST PASSED
    * All visuals and text used leave a user in no doubt that this website is a beautician business providing a number of services.

2. As a user, I want to be able to easily find out the services on offer.

  * Result: TEST PASSED
    * All services provided by the client are highlighted on the homepage, and also have dedicated pages for each service.

3. As a user, I want to be able to find out the cost of each service provided.

  * Result: TEST PASSED
    * The cost of each service provided by the client is highlighted in a table on specific pages where similar treatments are grouped together for ease of reference.

4. As a user, I want to be provided with a short description about each service and the time it will take.

* Result: TEST PART PASSED
    * Each service page provides a brief description of the service being offered. Time taken for these services however are not available. 
    * The client advises that the time taken for each service differs per client, depending on their indiviudal needs. The client felt that including a time could possibly provide a custiomer with a false impression of time taken, as they may have to take longer than standard.

5. As a user, I want to be provided with directions to the business.

  * Result: TEST PASSED
    * a map to the clients business premises and text directions have been included on the homepage.

6. As a user, I want to be able to easily find the business contact details.

  * Result: TEST PASSED
    * the clients phone number for booking is included in a footer at the bottom of each page. A separate contact form is also provided for those users who wish to make contact via text.

7. As a user, I want to be able to find social media links to the business.

  * Result: TEST PASSED
    * a link to each of the client's social media accounts is included in a footer at the bottom of each page.

8. As a user, I want to be able to provide feedback or comment through the site without having to exit and use my mail client.

  * Result: TEST PASSED
    * A separate contact form is provided for those users who wish to make contact via text. All other site pages can access this contact form directly using the dropdown navigation menu on each page.

9. As a user, I want to be able to navigate through the site freely, in a manner which is easily understood.

  * Result: TEST PASSED
    * each page is indentical in style and form, to promote a sense of inclusiveness across all sites pages, that is to say the site design and colours remain consistent across the site
    * a navigation dropdown is provided on each page, allowing a user to navigate freely between pages, without the use of browser back or forward buttons
    * a scroll to top button is included on all pages to allow a user to quickly return to the top of each page with a single press, instead of having to scroll back up again. 

10. As a user with disabilties, I want to be able to navigate through the site freely without obstruction.

  * Result: TEST PASSED
    * HTML is written in a logical order, with semantic elements enabling screen readers to easily ascertain the structure of the site
    * Alternative text was included on all images were required, to allow older browers or those using screen readers to ascertain what each image is.
    * The site was tested using [WAVE](https://wave.webaim.org/) to evaulate the accessibility of the site. Any errors identified by WAVE were actioned and passed,.

11. As user, I want to be able to view the website on any of my devices without any loss of functionality.

  * Result: TEST PASSED
    * The dev tools function of Mozilla Firefox was used to ensure that the website remained responsive across various screen sizes and devices, including iPhone 5, iPhone X, Galaxy S9, and screen sizes ranging from 800px to 1440px.
    * The website [Am I Responsive](http://ami.responsivedesign.is/#) was used to double check responsiveness across various devices. The resulting screenshot is used as the introductory image to this project. 



## Deployment
<hr>

The site was deployed to GitHub pages. 

The steps to deploy are as follows:
* In the GitHub repository, navigate to the Settings tab
* From the source section drop-down menu, select the Master Branch
* Once the master branch has been selected, the page will be automatically refreshed with a detailed ribbon display to indicate the successful deployment.

The live link can be found here - 

## Credits
<hr>

1.  [W3Schools](https://www.w3schools.com/) Tutorials were used to help in the coding of the dropdown navigation bar, the parallax scrolling effect and the insertion of the location map using Google Maps API.

2. The creation and styling of the Polaroid image was adapted from a tutorial by [Savv Studio](https://medium.com/@SavvStudio/tutorial-make-your-images-look-like-polaroid-pictures-with-html-and-css-7b1120732dd1). 

3. The scroll to top button was adapted from a Youtube tutorial by [CodingNepal](https://www.youtube.com/watch?v=HP3ZSd3ko5Y)

4. I viewed numerous tutorials on Youtube for help with the box model, display properties and the flex-box model. Specifically, tutorials by [Web Dev Simplfied](https://www.youtube.com/channel/UCFbNIlppjAuEX4znoulh0Cw), [Kevin Powell](https://www.youtube.com/channel/UCJZv4d5rbIKd4QHMPkcABCw) and [Traversy Media](https://www.youtube.com/channel/UC29ju8bIPH5as8OGnQzwJyA) helped further my understanding of positioning.  

5. Colour Pallette choice were influenced by a blog piece on calm colour pallettes by the [Muffin Group](https://muffingroup.com/blog/calm-color-palette/) 

6. Images for the site were sourced copyright free from [Adobe Stock](https://stock.adobe.com/uk/), [Pexels](https://www.pexels.com) and [Unsplash](https://unsplash.com). All other pictures are supplied by the developer and are originals by him.

7. Text for the About Us section was adapted from an article by [Emma Hanna Make Up and Beauty](http://emmahanna.com/about-emma-hanna-professional-make-up-artist-belfast-northern-ireland/)

8. Text for the relaxation section was taken from a blog article on [WellbeingPeople.com](https://www.wellbeingpeople.com/2019/04/15/why-relaxation-is-so-important/)

9. Text for the waxing section was taken from an article on [SecretSpa.co.uk](https://secretspa.co.uk/guide-to-waxing/)

10. Text for the nails section was taken from an article on [WebMD](https://www.webmd.com/beauty/features/more-beautiful-nails-a-dozen-tips#1)

11. The confirmation form submitted pop up was adpated from a tutorial on [Stack Overflow](https://stackoverflow.com/questions/59225218/how-to-display-a-confirmation-message-after-form-submission)

12. The favicon for the site was created using [favicon.cc](https://www.favicon.cc/) and inserted with help from a tutorial on [Stack Overflow](https://stackoverflow.com/questions/11893478/add-favicon-to-website)

13. Website traffice is monitored using [Google analytics](https://analytics.google.com/analytics/web/)

14. The PDF document used on the Waxing page was authored by [Harley waxing](https://harleywaxing.co.uk/)