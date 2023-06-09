<div align= center>
<h1>Wigwam Garden Solutions</h1>
<div align= center>
<img src="assets/images/wigwam-logo.jpg" alt="Wigwam Garden Solutions Logo" title="Wigwam Garden Solutions Logo" width="175px" height="auto">
</div>
<h2>A User-Centric Frontend Development Project</h2>
<h2>by Oscar Parkin-Christie</h2>

</div>

# Contents

1. [Introduction & Site Description](#introduction--site-description) 
2. [Instructions](#instructions)
3. [Mockups](#mockups)
4. [Design Choices](#design-choices)
5. [Features & UI](#features--ui)
6. [Future Features](#future-features)
7. [UX](#ux)
8. [Wireframes & Site Map](#wireframes--site-map)
9. [Testing](#testing)
10. [Deployment](#deployment)
11. [Known Bugs](#known-bugs)
12. [Acknowledgements](#acknowledgements)


# Introduction & Site Description
This website is for 'Wigwam Garden Solutions': a garden design and landscaping company.

The site provides a space for the company to advertise its services and build its customer base by showcasing recent projects, testimonials, a list of services it offers and its brand identity. 

### Disclaimer
The example company, organisation, products, email addresses, contact information, logos, social media links, people, places and events herein are fictitious.
No association with any real company is intended nor should be inferred.

The example is for the sole purpose of showcasing my project for the User Centric Frontend Development Module for the Level 5 Diploma in Web Applications Development.


# Instructions
## Instructions for running the code in Gitpod & Viewing a Live Preview: 

- Navigate to the GitHub Repository. Click: [Here](https://github.com/ozpc99/Wigwam-Garden-Solutions)
- Click the green button: 'Gitpod'
- Sign in to Gitpod with a GitHub account.
- Create a new workspace.
- To view a live preview: 
    - Navigate to the command terminal.
    - Type: 'python -m http.server 8000' and press the enter key.
    - Click: 'Open Preview'
    - To view preview in a new browser tab, click the box with the arrow in the top right corner (Open in browser).


# Mockups

<div float= "left">
    <img src="documents/screenshots/mockups/laptop-mockup.jpg" width= "500px" alt="">
    <img src= "documents/screenshots/mockups/tablet-mockup-1.jpg" width= "500px" alt="">
</div>

## Desktop
![site-viewed-on-desktop](/documents/screenshots/mockups/desktop-mockup.jpg "Site Viewed on Desktop")

## Tablet

![site-viewed-on-tablet](/documents/screenshots/mockups/tablet-mockup.jpg "Site Viewed on Tablet")

## Mobile

![site-viewed-on-mobile](/documents/screenshots/mockups/mobile-mockup.jpg "Site Viewed on Mobile")



# Design Choices

The site has been laid out on a Bootstrap grid system. This presents contents and information in an intuitive way and makes it easy to digest. The grid system also allows for full responsiveness across all devices. 

The site's colour scheme is monochrome: black, white and grey.
The background is white to give it a clean, minimalist appearance and to make the content easy and accessible to read.

The navigation bar is a dark charcoal grey to make it stand out from other elements on the page. It also makes it obvious to the user that this is the navigation bar containing links to other pages.

The body text is black to make it accessible and easy to read. 
The page body's font is 'Lato' which is an easy to read sans-serif font.

The logo and navbar elements' colour is white and the font is 'Nunito Sans' in all caps with a CSS letter-spacing property set to 2px. This makes it easy to read and denotes each block of text as a separate navigation link. 
Each navlink as well as the logo has a CSS hover transition applied to turn the link from white to a light grey. This tells the user that this is a call to action. The link will remain the grey colour once clicked (link-active) to tell the user which page they are on.
The navlinks have padding applied to space them equidistant from one another and a 'text-center' property applied to center the navlinks on larger screen sizes. On smaller screen sizes, (tablets and mobiles), the navbar collapses and displays the links in a vertical menu. 

The site's images are displayed in rounded rectangles using Bootstrap's 'rounded-3' class attribute. This makes it easier on the eyes and more aesthetically pleasing than sharp corners. The images on the site are all of uniform proportions and this creates a consistent theme. 
The exceptions to this is on the 'Why Choose Us?' section where circular images are used instead of rounded rectangles. This is to denote focal points of interest. Each photo serves to represent one bullet point for reasons why the user should choose this company. 
Similarly, on the 'Meet The Team' section, circular images are the favoured choice to denote profile pictures for each member of the team. 

Buttons on the site are taken from Bootstrap's library and are a dark charcoal grey colour (btn-dark) which has a CSS hover effect applied, turning it to a lighter shade of grey. This tells the user that this is a call to action. 

# Features & UI
## Site-Wide Features

### Navigation Bar
The navigation bar is at positioned at the top of the screen across all site pages.
It is fully responsive and collapses into a navigation menu when viewed on mobile devices.
The navbar lets users navigate easily from page to page without having to press the back button.
The navigation links have a rollover effect to turn the link text from white to grey when the cursor hovers over them. This allows the user to easily select the desired link.
Additionally, the current page the user is viewing is indicated in the navbar by the link text turning a solid colour from the default white to grey.

![navbar](/documents/screenshots/navbar.png "Navbar")

### Footer

The footer is positioned at the bottom of each site page. Its function is to contain copyright information and provide social media links to Facebook, Instagram and Pinterest.

<i> NB- There is a bug with the social media links. 
The links only take the user to the home page of each social media site. This is because a profile page for the company has not yet been set up. In future, the links will take the user to the company's profile pages as intended.
See [Known Bugs](#known-bugs) section for more info.</i>

The grey line above the footer separates its involvement from the rest of the page and emphasises the end of the scrollable content.

![footer](/documents/screenshots/footer.png "Footer")

## Home Page Features

### Image Carousel
The image carousel is the first thing the user will see when they visit the site. On desktop it fills 85% of the viewport height. It's purpose is to tell the user about the company and showcase current features, promotions or recent projects through the use of photographic media and captions. The links within the captions hint to the user to explore different pages across the site to learn more information about the services on offer from Wigwam Garden Solutions.

The image carousel is fully responsive to fit all screen sizes. It is controlled with navigation arrows (forward and back) or with the navigation indicators. The image carousel can be adapted to include an auto-scroll attribution. However, in this version of the site, this feature has been disabled to improve UX, accessibility and user control.

![carousel-image-1](/documents/screenshots/carousel-1.png "Carousel Default Image")

### Recent Projects Gallery

The recent projects gallery showcases the company's recent work. It is a space for advertising the diverse range of services that they offer and to encourage the user to explore ideas for a potential project they might have in mind.

The images are fully responsive, showing as a 3x4 Bootstrap grid on desktop and displayed in a vertical stack on mobile.

#### Desktop View

![recent-projects-gallery](/documents/screenshots/recent-projects-1.png "Recent Projects Gallery")

#### Mobile View

![recent-projects-gallery-mobile-view](/documents/screenshots/recent-projects-mobile.png "Recent Projects Gallery Mobile View")

The images all have a CSS applied zoom transition on hover as well as the cursor which changes from a pointer to a magnifying glass cursor to encourage the user to click on them.

#### See The CSS Transition in Action:

![recent-projects-image-css-rollover](/documents/screenshots/recent-projects-rollover.gif "Recent Projects Image CSS Rollover Transition")

Once clicked on, a Bootstrap lg modal appears showing a larger version of the image with a caption detailing the project and the location where it was done. 

### Image Modal

![recent-projects-gallery-modal-image](/documents/screenshots/recent-projects-2.png "Recent Projects Gallery Modal Image")

### Video Modal

![recent-projects-gallery-modal-video](/documents/screenshots/recent-projects-3.png "Recent Projects Gallery Modal Video")

### Areas We Cover

This section contains an interactive iframe from Google Maps. It is a custom map that highlights the boundary of where the company covers. It also has the company's office located as a custom pin on the map.

The iframe is fully responsive and allows the user to drag, zoom and open the map in a new tab for better viewing. 

![map-iframe](/documents/screenshots/map-iframe.png "Areas We Cover Google Maps iframe")

### Testimonials
The testimonials section shows the user the trustworthiness of the company.

There is a link to Google Reviews showing a 4.5 Star rating.

<i> NB- There is a bug with this link. 
The link only takes the user to the google.com homepage instead of the company's profile on Google Reviews.
This is because a Google Reviews profile has not yet been set up for the company.
In future, the link will take the user to the company's Google Reviews profile as intended.
See [Known Bugs](#known-bugs) section for more info.</i>

![testimonials](/documents/screenshots/testimonials.png "Testimonials")

## 'Our Services' Page Features
All the images on the Our Services page have Bootstrap's 'rounded-3' class attributed to them. They are all uniform in size in keeping with the site's theme.
The images are displayed in a Bootstrap grid with three rows of two columns on desktop and one column with six rows on mobile.

#### Desktop View

![our-services-desktop-view](/documents/screenshots/our-services.png "Our Services Desktop View")

#### Mobile View

![our-services-mobile](/documents/screenshots/our-services-mobile.png "Our Services Mobile View")

### Lawn Maintenance & Pricing Plans

![lawn-maintenance-pricing-plans](/documents/screenshots/lawn-maintenance.png "Lawn Maintenance Pricing Plans")

The Weekly Lawn Maintenance feature is the main feature of the Our Services page.
The user is asked a rhetorical question: 'Garden becoming a bit of a jungle?' to plant the idea that they can fix the situation by purchasing one of the service plans. 

The pricing is displayed using Bootstrap cards. This tells the user that these are products & services up for purchase and allows them to compare side by side, the included services of each plan to decide which is best for them. 

The 'Pro' pricing is displayed with a dark background. This is to make it stand out and convey to the user that this is a premium service. It also features the price in small, strikethrough text next to regular text (<sup> <s>£50</s> </sup> £40). This shows a limited time offer and urges the user to get in touch today to get a good deal on their service plan.


### Garden Redesigns

![garden-redesigns](/documents/screenshots/garden-redesigns.png "Garden Redesigns")

Below the list of services, is the Garden Redesigns section.
This is the area of expertise that Wigwam specialise in and are renowned for. 
This section is placed below the list of services and is separated using a top-border to serve as a horizontal rule. This is because it is a specialist service reserved for customers who are looking for more than simple odd-jobs and light construction. It is for complete garden makeovers.


This section utilises a Bootstrap collapse to hide large amounts of information. This streamlines the look of the page and improves UX. 
By default, when the page loads, this section is hidden. When the user presses the button, the section collapses to reveal the information. 

#### See the Collapse in Action:

![bootstrap-collapse](/documents/screenshots/collapse.gif "Bootstrap Collapse")

### Redesigns by Wigwam <i>- Collapsed</i>

![redesigns-by-wigwam](/documents/screenshots/wigwam-redesigns.png "Redesigns by Wigwam")

This section contains the seven steps of a Wigwam garden redesign.
The steps are laid out using a Bootstrap grid system comprised of rows and columns. 
On desktop view, there are two columns and two items per row. Step 7-Completion, is an exception and is positioned in the center of the screen to signal to the user that they have reached the end of this section. There are four rows in total. 

On mobile devices, this shrinks to one column or one item per row stacked on top of one another.

The items are read left to right, top to bottom similar to a comic strip and are intuitive, easy to follow and easy to digest.
Text content is minimal to quickly get key points across to the user. 

Each step is numbered 1-7 with a circular styled number. These act like bullet points and provide a consistent style and a point of reference for the user.

Again, like the rest of the site, the images have the Bootstrap 'rounded-3' attribute applied for consistency. 

At the end of the section there is a 'Back to Top' button which when pressed; automatically scrolls back to the top of the section without the user having to manually scroll all the way back up.
Having this button improves UX and adds interactivity and user control to the site.

In future, the button that triggers the collapse will include JavaScript components to make it more obvious to the user that this is a collapsible section. An example of this might include a caret-right or chevron-right icon on or next to the button that rotates when clicked becoming something resembling a caret-down or chevron-down icon. 

### Why Choose Us?

![why-choose-us](/documents/screenshots/why-choose-us.png "Why Choose Us?")

The 'Why Choose Us?' section aims to tell the user why a Wigwam garden redesign is better than the rest. It features three circular images, each serving to represent one bullet point.
"The three P's" (Professional, Personal & Permaculture) are a simple and memorable way of getting the main points across to the user. 

The word 'permaculture' is hyperlinked and left with default hyperlink styling to make it obvious to the user that this is a link. The reason for this is that most users will not understand what the word means or the significance of it in the context of garden design. 
When clicked, it opens an article from 'Permaculture Magazine' in a new tab giving more explanation as to its definition as well as providing access to the 'Permaculture Magazine' site. From there, they can explore articles and learn more.
Wigwam Garden Solutions use permaculture substantially within their designs. It is one of the company's core values and it is important to them to spread the word and educate as many people as possible to its benefits. 


## About Us Page Features

### Logo & Awards Image

![about-us](/documents/screenshots/about-us.png "About Us Section")

The logo is positioned above the awards the company has won. This instills confidence in the company and showcases their achievements. 

### About Us Paragraph
This paragraph of text tells the user about the company and what it stands for. It focuses its content around sustainable design- one of the company's core values. It is important to Wigwam that this message is made clear to customers. 

### Meet The Team Section
![meet-the-team](/documents/screenshots/team.png "Meet The Team")

The 'Meet The Team' section tells the user more about the team behind the company and the roles within it.

The button to Nicole's pinterest portfolio allows users to view her previous work and saved pins. It also provides inspiration to customers about how they would like their garden to look. 

<i> NB- There is a bug with this button. 
The button only takes the user to the pinterest.co.uk home page. This is because a pinterest profile has not yet been set up for the company or for Nicole.
In future, the link will take the user to Nicole's pinterest profile as intended.
See [Known Bugs](#known-bugs) section for more info.</i>

## Free Quote Page Features

![free-quote-page](/documents/screenshots/quote.png "Free Quote Page")

The images on the Free Quote page supplement the context of the contact form. There is the company's logo, an image of a man with a tool box and an image of a man holding a plant. The images only display on desktop view and hide when viewed on mobile, this is to remove unnecessary content from smaller screen sizes for better UX and optimisation. 

### Form

The Free Quote page contains a form where users can submit a request for a free quote.
There is also the opportunity for users to add any comments or questions they might have.
They can also upload multiple photos of their garden for Wigwam to better see the size of the job and the work required.

![form](/documents/screenshots/form.png "Form")

### Contact Info
At the bottom of the page is also all the company's contact info. This is displayed in a single row of four columns on desktop, and a single column of four rows on mobile. 
The email link is left with default hyperlink styling to tell the user that this is a link. When clicked, it opens the user's default email client to send an email to Wigwam's email address. 
The social media links open each site in a new tab respectively. 

<i> NB- There is a bug with the social media links. 
The links only take the user to the home page of each social media site. This is because the social media profiles have not yet been set up for the company.
In future, the links will take the user to the company's profile page on each social media site as intended.
See [Known Bugs](#known-bugs) section for more info.</i>

#### Desktop View:

![contact-info-desktop](/documents/screenshots/contact-info.png "Contact Info Desktop View")

#### Mobile View:

![contact-info-mobile](/documents/screenshots/contact-info-2.png "Contact Info Mobile View")


# Future Features
### JavaScript
In future, the site will include JavaScript components to add animations to certain elements such as the navbar navlinks. There will also be a JavaScript animated caret icon next to the 'The 7 Steps of a Wigwam Redesign' button to make it more obvious to the user that this triggers a collapsible section. 

### Weekly Lawn Maintenance Purchasing
The Bootstrap cards containing the Weekly Lawn Maintenance pricing will contain a 'Sign up Now' button to allow users to purchase a plan without having to fill in the contact form or get in touch by other means. The site administrator will be able to manage bookings and alter this feature so users are added to a waiting list and only billed after the work has been done should demand for the service be high. 

### User Sign In & Loyalty Scheme
There will also be a page where users can create an account  where they can manage their bookings and earn loyalty points from their weekly lawn maintenance to unlock discounts. 

# UX
## Site Goals

The goal of the 'Wigwam Garden Solutions' website is to showcase the company's recent work as its portfolio and to advertise its services to increase its customer base.
It should tell the user about the company, its values and the exact services they offer.

The company is primarily focused on garden design so the site should have a large section dedicated to explaining the process the user can expect should they enquire about this service.

There should be a page with contact information for users to get in touch regarding a quote or question.
The site should include links to social media profiles for users to be able to share content with others and for the company to advertise its services and post more content such as images, videos, promotions and reviews. 

There should be a a section dedicated to testimonials for users to read reviews and gain understanding of the company's trustworthiness. 

The site should be easy to navigate, simple in its design and aesthetically pleasing.
The site should look good both on desktop and on mobile devices. 
The navbar should be responsive and should collapse when viewed on mobile devices.

The site should have a consistent colour scheme. Text content must use fonts that are consistent with their content (paragraphs or headings) across all pages. Images and icons must be styled consistently.

Site administrators should be able to easily update information such as the Recent Projects gallery with new images or videos and keep the content up to date and relevant. 


## User Stories

### As a Customer:
- I want to quickly gain a sense of the company's identity and what they stand for. I want to know more about the company, its history and the people that make it up. 
- I want to be able to view the content I want and navigate the site with ease. All the links should work and take me to where I need to go.
- I want to see what services are on offer and if possible, a rough price range.
- I want to see images or videos of the company's recent work.
- I want to be able to access their social media pages from this site.
- I want to see if I can trust this company, so reviews and testimonials must be included.
- I want to be able to contact the company if I have any questions or want to request a call back for a quote. All contact information (telephone, email, address and social media) must be available. I also want the option to be able to send over photos of my garden to ask them for their ideas on how to improve it. 
- I want to know if the company will be able to serve me, i.e. if I am in range of the areas that they cover. 
- I want to know why I should choose this company over any others and what makes them stand out from the crowd.
- If I am interested in getting my garden redesigned, I want to know what the process is involved in doing so.


### As the site Administrator:
- I want to increase customer base by advertising a wide range of services on offer.
- I want to include links to social media platforms where the company can advertise their services to a wider demographic.
- I want to be able to easily update the home page carousel with new content such as promotions.
- I want to be able to easily update the Recent Projects gallery with new content as soon as it becomes available. 
- I want to be able to easily update the Testimonials section with new up to date reviews.
- I want to be able to easily update the pricing on the Lawn Maintenance section to include limited time offers and changes in pricing.
- I also want to be able to easily update the services on offer if the company decide to specialise in other areas. 
- I want to be able to easily update the awards the company has won if they are nominated for other prizes in the future.
- I also want to be able to easily update the Meet The Team section in case the company decides to hire more staff.
- I want contact information to be accessible and clearly displayed so customers can easily get in touch regarding any questions or if they would like to request a quote. I also want to be able to easy update this information should the company move offices or change their phone number for example.
- I want to be able to collect data from the form into a database which emails each request to the company to ask for a quote or call back. I want this data to be managed securely and in line with GDPR data protection regulations.  
- I want to be able to keep the workings of this site up to date and compatible with a range of web browsers and devices by utilising version control effectively.


# Wireframes & Site Map
## Wireframes for this site can be accessed: [here](/documents/wireframes.pdf)

## A Site Map can be accessed: [here](/documents/site-map.pdf)


# Testing

## Manual Testing

### Manual Testing of Features & User Stories: [Click Here](/documents/manual-testing-process.pdf)

### See Below for Attached Screenshot Videos of the Manual Testing process:
#### Each screenshot video corresponds to a number listed in the manual-testing-process.pdf file.

1. [Screenshot: 1](/documents/screenshots/manual-testing-screenshots/screenshot-1.mp4)
2. [Screenshot: 2](/documents/screenshots/manual-testing-screenshots/screenshot-2.mp4)
3. [Screenshot: 3](/documents/screenshots/manual-testing-screenshots/screenshot-3.mp4)
4. [Screenshot: 4](/documents/screenshots/manual-testing-screenshots/screenshot-4.mp4)
5. [Screenshot: 5](/documents/screenshots/manual-testing-screenshots/screenshot-5.mp4)
6. [Screenshot: 6](/documents/screenshots/manual-testing-screenshots/screenshot-6.mp4)
7. [Screenshot: 7](/documents/screenshots/manual-testing-screenshots/screenshot-7.mp4)
8. [Screenshot: 8](/documents/screenshots/manual-testing-screenshots/screenshot-8.mp4)
9. [Screenshot: 9](/documents/screenshots/manual-testing-screenshots/screenshot-9.mp4)
10. [Screenshot: 10](/documents/screenshots/manual-testing-screenshots/screenshot-10.mp4)
11. [Screenshot: 11](/documents/screenshots/manual-testing-screenshots/screenshot-11.mp4)
12. [Screenshot: 12](/documents/screenshots/manual-testing-screenshots/screenshot-12.mp4)
13. [Screenshot: 13](/documents/screenshots/manual-testing-screenshots/screenshot-13.mp4)
14. [Screenshot: 14](/documents/screenshots/manual-testing-screenshots/screenshot-14.mp4)
15. [Screenshot: 15](/documents/screenshots/manual-testing-screenshots/screenshot-15.mp4)
16. [Screenshot: 16](/documents/screenshots/manual-testing-screenshots/screenshot-16.mp4)
17. [Screenshot: 17](/documents/screenshots/manual-testing-screenshots/screenshot-17.mp4)
18. [Screenshot: 18](/documents/screenshots/manual-testing-screenshots/screenshot-18.mp4)
19. [Screenshot: 19](/documents/screenshots/manual-testing-screenshots/screenshot-19.mp4)
20. [Screenshot: 20](/documents/screenshots/manual-testing-screenshots/screenshot-20.mp4)
21. [Screenshot: 21](/documents/screenshots/manual-testing-screenshots/screenshot-21.mp4)
22. [Screenshot: 22](/documents/screenshots/manual-testing-screenshots/screenshot-22.mp4)
23. [Screenshot: 23](/documents/screenshots/manual-testing-screenshots/screenshot-23.mp4)
24. [Screenshot: 24](/documents/screenshots/manual-testing-screenshots/screenshot-24.mp4)
25. [Screenshot: 25](/documents/screenshots/manual-testing-screenshots/screenshot-25.mp4)
26. [Screenshot: 26](/documents/screenshots/manual-testing-screenshots/screenshot-26.mp4)
27. [Screenshot: 27](/documents/screenshots/manual-testing-screenshots/screenshot-27.mp4)
28. [Screenshot: 28](/documents/screenshots/manual-testing-screenshots/screenshot-28.mp4)
29. [Screenshot: 29](/documents/screenshots/manual-testing-screenshots/screenshot-29.mp4)
30. [Screenshot: 30](/documents/screenshots/manual-testing-screenshots/screenshot-30.mp4)
31. [Screenshot: 31](/documents/screenshots/manual-testing-screenshots/screenshot-31.mp4)


## Validator Testing

### [WC3 HTML Markup Validator](https://validator.w3.org/)

#### index.html
The Home Page (index.html) passed the W3C HTML Validation Check with: NO ERRORS.

![index.html-w3c-html-validator](/documents/screenshots/index.html-w3c-validator.png "index.html W3C HTML Validator")


#### services.html
The Our Services Page (services.html) passed the W3C HTML Validation Check with: NO ERRORS.

![services.html-w3c-html-validator](/documents/screenshots/services.html-w3c-validator.png "services.html W3C HTML Validator")

#### about.html
The About Us Page (about.html) passed the W3C HTML Validation Check with: NO ERRORS.

![about.html-w3c-html-validator](/documents/screenshots/about.html-w3c-validator.png "about.html W3C HTML Validator")

#### contact.html
The Free Quote / Contact Us Page (contact.html) passed the W3C HTML Validation Check with: NO ERRORS.

![contact.html-w3c-html-validator](/documents/screenshots/contact.html-w3c-validator.png "contact.html W3C HTML Validator")

### [W3C Jigsaw CSS Validator](https://jigsaw.w3.org/css-validator/)

#### style.css

The stylesheet (style.css) passed the W3C CSS Jigsaw Validation Check with: NO ERRORS.

![style.css-jigsaw-validator](/documents/screenshots/style.css-jigsaw-validator.png "style.css W3C CSS Jigsaw Validator")

# Deployment

This site was deployed to GitHub. A link to the repository can be accessed: [Here](https://github.com/ozpc99/Wigwam-Garden-Solutions).

### Steps Taken to Deploy to GitHub.

- Download GitHub for Desktop.
- Launch GitHub for Desktop and sign in with a GitHub account.
- Click: 'File' > 'Add Local Repository.' (Ctrl+O) and upload root directory folder.
- Click 'Fetch Origin'. 
    - The software will notify you of any changes made to files since last push, if initial commit; no changes will show.
- Give a summary and description of changes made since last commit.
- Click: 'Commit to Main'.
    - GitHub will organise the files.
- Click: 'Push Origin'
    - Github Desktop will push the files to GitHub. 



# Known Bugs
### This section lists any known bugs and their fixes. 
### It provides documentation of the troubleshooting process.

## 1) Bug Found: 11/05/2023 18:30pm

The bug found was that the image (constructing.jpg) on the page was cut off at the bottom and not cropped to fit the container. Because of this, it didn't match the style consistent with the rest of the images on this page and across the site. 

![bug-1](/documents/screenshots/bugs/bug-1.png)

The CSS applied to the image was:

![bug-1-css](/documents/screenshots/bugs/bug-1-css.png)


### Bug Fixed: 12/05/2023 11:45am

The bug was fixed by adding a new style rule to the CSS targeting the image within the container. This made sure any image with this style rule applied, matched the size of the container (div).

The style rule was updated to include this:

![bug-1-css-fixed](/documents/screenshots/bugs/bug-1-fixed-css.png)

This resulted in the bug with said image being fixed:

![bug-1-fixed](/documents/screenshots/bugs/bug-1-fixed.png)

## 2) Bug Found: 12/05/2023 12:10pm

The bug found was that the image (moss-min.jpg) was ever so slightly, not aligned square with image above, and so stands out and is not consistent with the style of the rest of the images on the page. 

![bug-2](/documents/screenshots/bugs/bug-2.png)

After fault-finding this didn't appear to be an issue with the CSS but rather the HTML and a Bootstrap class attribute in the wrong place.
The HTML was:

166 | `<section class="container-fluid pb-4 my-3 border-top" id="see-more">`

### Bug Fixed: 12/05/2023 12:15pm

The bug was fixed by removing the Bootstrap ("container-fluid") class attribute from the section.
The HTML is now:

166 | `<section class="pb-4 my-3 border-top" id="see-more">`

This resulted in the bug being fixed:

![bug-2-fixed](/documents/screenshots/bugs/bug-2-fixed.png)

## 3) Bug Found: 15/05/2023 09:30am

The bug found was that the social media links located in the footer across the site, as well as the Contact Us section on (services.html) and in Nicole's bio on the Meet The Team section (about.html) only link to the homepage of each site. (e.g. facebook.com, instagram.com, pinterest.com). 

### ! THIS BUG REMAINS TO BE FIXED ! 
This is because a social media profile has not yet been set up for the company. In future these links will take the user to the company's profile page on each social media platform.

## 4) Bug Found: 15/05/2023 09:30am

The bug found was that the link to Google Reviews in the Testimonials section on (index.html) only links to Google's homepage (google.com) instead of the company's profile on Google Reviews.

### ! THIS BUG REMAINS TO BE FIXED ! 
This is because a profile has not yet been set up for the company on Google Maps and Google Reviews. In future this link will take the customer to the company's Google Reviews profile.  

## 5) Bug Found: 15/05/2023 13:35pm

The bug found was that the page did not fit the screen responsively and caused an overflow on the x-axis. This resulted in a horizontal scroll bar. This was particularly noticeable when viewed on tablet and mobile.

### Bug Fixed: 16/05/2023 10:30am

The bug was fixed by adding the `"container-fluid p-0"` class attribute to the `<html>` tag on each page. This results in a responsive webpage without any white space (padding) added by Bootstrap.
The horizontal scroll bar was removed by adding a CSS style rule to the `"container-fluid"` class attribute: `"overflow-x: hidden"`.

The website is now fully responsive across a range of viewports including mobile devices.

## 6) Bug Found: 16/05/2023 11:15am

On certain mobile devices, the image carousel caption on (index.html) was not resizing responsively causing the caption and its text to be cut off.

![samsung-galaxy-s8+-bug](/documents/screenshots/bugs/samsung-galaxy-s8-bug.png "Samsung Galaxy S8+ Bug")

### Bug Fixed: 16/05/2023 11:30am

Thanks to help from a forum post on [Stack Overflow](https://stackoverflow.com/questions/55198646/bootstrap-carousel-caption-not-responsive-html-css). I was able to fix the bug using media queries to target the font size of the text within the carousel caption for each of Bootstrap's default breakpoints.
Doing this makes it fully responsive across all screen sizes.

This resulted in the bug being fixed:

![samsung-galaxy-s8+-bug-fixed](/documents/screenshots/bugs/samsung-galaxy-s8-bug-fixed.png "samsung-galaxy-s8+-bug-fixed")

## 7) Bug Found: 16/05/2023 11:35am

The bug found was that on certain screen sizes when viewed on a mobile device, the images in the recent projects gallery were not evenly spaced and had been cut off.

![recent-projects-gallery-img-bug](/documents/screenshots/bugs/recent-projects-gallery-bug.png "Recent Projects Gallery Images Bug")

### Bug Fixed 16/05/2023  12:00pm

The bug was fixed by adding the `"img-fluid"` Bootstrap class attribute to the parent div of the `<img>`. Left and right padding was also added to all `<img>` elements in the gallery section using Bootstrap's `"px-2"` class attribute.

This resulted in the bug being fixed:

![recent-projects-gallery-img-bug-fixed](/documents/screenshots/bugs/recent-projects-gallery-bug-fixed.png "Recent Projects Gallery Images Bug Fixed")

## 8) Bug Found: 17/05/2023 09:50am

The bug found was that the form submit button does not send the form to a database.
There is also no 'Successfully Sent' message presented to the user once the button is clicked which negatively affects UX and accessibility.

### ! THIS BUG REMAINS TO BE FIXED !

This bug has not yet been fixed as a database has not yet been set up to serve the back-end workings of the form and data-handling. 


# Acknowledgements
## This website was built using [Bootstrap](https://getbootstrap.com/) v5.3.

## The icons on this site were taken from [FontAwesome](https://fontawesome.com/) v6.4.0.
They are listed below in alphabetical order:

- [building](https://fontawesome.com/icons/building?f=classic&s=solid)
- [campground](https://fontawesome.com/icons/campground?f=classic&s=solid)
- [chevron-up](https://fontawesome.com/icons/chevron-up?f=classic&s=solid)
- [envelope](https://fontawesome.com/icons/envelope?f=classic&s=solid)
- [facebook](https://fontawesome.com/icons/facebook?f=brands&s=solid)
- [hashtag](https://fontawesome.com/icons/hashtag?f=classic&s=solid)
- [instagram](https://fontawesome.com/icons/instagram?f=brands&s=solid)
- [list](https://fontawesome.com/icons/list?f=classic&s=solid)
- [location-dot](https://fontawesome.com/icons/location-dot?f=classic&s=solid)
- [martini-glass-citrus](https://fontawesome.com/icons/martini-glass-citrus?f=classic&s=solid)
- [pen-to-square](https://fontawesome.com/icons/pen-to-square?f=classic&s=solid)
- [people-group](https://fontawesome.com/icons/people-group?f=classic&s=solid)
- [phone](https://fontawesome.com/icons/phone?f=classic&s=solid)
- [pinterest](https://fontawesome.com/icons/pinterest?f=brands&s=solid) 
- [star](https://fontawesome.com/icons/star?f=classic&s=solid)
- [star-half-stroke](https://fontawesome.com/icons/star-half-stroke?f=classic&s=regular)
- [trowel](https://fontawesome.com/icons/trowel?f=classic&s=solid)
- [user](https://fontawesome.com/icons/user?f=classic&s=solid)


## The fonts used on this site were taken from [Google Fonts](https://fonts.google.com/). 
They are:
- [Nunito Sans](https://fonts.google.com/specimen/Nunito+Sans?query=nunito+sans) (Designed by Vernon Adams, Jacques Le Bailly, Manvel Shmavonyan, Alexei Vanyashin)
- [Lato](https://fonts.google.com/specimen/Lato?query=lato) (Designed by Łukasz Dziedzic)


## Images:

All images & videos on this site are my own unless specified otherwise below:

- [award-1.png](https://pixabay.com/vectors/laurel-wreath-roman-victory-black-156019/)
by OpenClipart-Vectors on Pixabay

- [award-2.jpg](https://www.freepik.com/free-vector/trophy_34295225.htm#query=trophy&position=3&from_view=search&track=sph)
by juicy_fish on Freepik

- [constructing.jpg](https://www.freepik.com/free-photo/carpenter-man-taking-measures-wood-plank_11106766.htm#query=screwing%20fence&position=35&from_view=search&track=ais)
by freepik on Freepik

- [decking-2.jpg](https://www.freepik.com/free-photo/empty-wood-chair_1272911.htm#query=garden%20decking&position=20&from_view=keyword&track=ais)
by topntp26 on Freepik

- [family.jpg](https://www.freepik.com/free-photo/happy-young-family-during-picking-apples-garden-outdoors_7652653.htm#page=2&query=family%20garden%20relaxing&position=8&from_view=search&track=ais)
by master1305 on Freepik

- [florist.jpg](https://www.freepik.com/free-photo/man-florist-working-green-house_21795137.htm#query=gardener&position=4&from_view=search&track=sph)
by senivpetro on Freepik

- [garden-plan.jpg](https://www.freepik.com/free-photo/crop-hands-using-template-stencil_2091845.htm#query=garden%20plan&position=47&from_view=search&track=ais)
by freepik on Freepik

- [lawnmower-min.jpg](https://www.freepik.com/free-photo/man-cutting-grass-with-lawn-mover-back-yard_8828102.htm#query=lawnmower&position=1&from_view=search&track=sph)
by senivpetro on Freepik

- [matty.jpg](https://www.freepik.com/free-photo/rural-morning-close-up-beautiful-bearded-caucasian-male-farmer-blue-t-shirt-black-pants-smiling-working-farm-picking-crop-doing-favorite-job_9696954.htm#query=gardener&position=9&from_view=search&track=sph)
by cookie_studio on Freepik

- [meeting.jpg](https://www.freepik.com/free-photo/close-up-coffee-table-with-two-colleague_9960699.htm#query=meeting%20coffee&position=0&from_view=search&track=ais)
by lookstudio on Freepik

- [moodboard.jpg](https://www.freepik.com/free-photo/green-houseplant-background-plant-lovers_17599271.htm#query=garden%20concept&position=20&from_view=search&track=ais)
by rawpixel.com on Freepik

- [nicole.jpg](https://www.freepik.com/free-photo/woman-gardner-greenhouse_4410517.htm#query=female%20gardener&position=40&from_view=search&track=ais)
by senivpetro on Freepik

- [planting.jpg](https://www.freepik.com/free-photo/overhead-view-hand-holding-small-fresh-potted-plant_2586588.htm#query=gardening&position=5&from_view=search&track=sph)
by freepik on Freepik

- [pruning.jpg](https://www.freepik.com/free-photo/incognito-man-cutting-overgrown-bushes_26767885.htm#query=hedge%20cutter&position=9&from_view=search&track=ais)
by Artphoto_studio on Freepik

- [ricky.jpg](https://www.freepik.com/free-photo/outdoor-shot-logger-having-rest-open-air-after-cutting-trees_15755920.htm#query=tree%20surgeon&position=4&from_view=search&track=ais)
by user18526052 on Freepik

- [survey.jpg](https://www.freepik.com/free-photo/new-building-project_5400347.htm#query=construction%20survey&position=17&from_view=search&track=ais)
by pressfoto on Freepik

- [tradie.jpg](https://www.freepik.com/free-photo/part-male-construction-worker_11230034.htm#query=tools&position=39&from_view=search&track=sph)
by gpointstudio on Freepik



## The mockups featured in the README.md file were taken from [SmartMockups](https://smartmockups.com/). 

The templates are for which are listed below:

- [African-American man using MacBook Pro](https://smartmockups.com/mockup/AA9AevNjIn5)
- [iPad Pro in the hands of a woman sitting on the couch beside the window](https://smartmockups.com/mockup/tU%24lNMrEV)
- [Sony Xperia 1 IV](https://smartmockups.com/mockup/YWH6sUgmkY5)
- [Studio Display](https://smartmockups.com/mockup/KEyIVr5llKC)
- [Tablet](https://smartmockups.com/mockup/7dCMjVzUCJm)

