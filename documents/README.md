# README.md | Wigwam Garden Solutions
## (User Centric Front-End Development Project)

## Table of Contents
1. Introduction & Site Description
2. Instructions for running code in Gitpod
3. Content & Media
4. Deployment & Testing / Bugs
5. Acknowledgements


# Introduction & Site Description
(site description goes here)
A website to...
Aims of the website: 
- External User's Goal
- Site Owner's Goal 
- - Increase customer base
- Potential Features to include
- - Social media Links etc. 
- - Images and testimonials 

# Instructions
Instructions for running code in Gitpod

# Features
## Site-Wide Features

## Navigation Bar
The navigation bar is at positioned at the top of the screen across all site pages.
It is fully responsive and collapses into a navigation menu when viewed on mobile devices.
The navbar lets users navigate easily from page to page without having to press the back button.
The navigation links have a rollover effect to turn the link text from white to grey when the cursor hovers over them. This allows the user to easily select the desired link.
Additionally, the current page the user is viewing is indicated in the navbar by the link text turning a solid colour from the default white to grey.

![navbar](/documents/screenshots/navbar.png "Navbar")

## Footer

The footer is positioned at the bottom of each site page. Its function is to contain copyright information and provide social media links to Facebook, Instagram and Pinterest.

The grey line above the footer separates its involvement from the rest of the page and emphasises the end of the scrollable content.

![footer](/documents/screenshots/footer.png "Footer")

# Home Page Features

## Image Carousel
The image carousel is the first thing the user will see when they visit the site. On desktop it fills the entire viewport. It's purpose is to tell the user about the company and showcase current features, promotions or recent projects through the use of photographic media and captions. The links within the captions hint to the user to explore different pages across the site to learn more information about the services on offer from Wigwam Garden Solutions.

The image carousel is fully responsive to fit all screen sizes. It is controlled with navigation arrows (forward and back). On page-loading, it will be static. However, once the user makes contact with the navigation arrows, it will begin to autoscroll through the images left to right. 

![carousel-image-1](/documents/screenshots/carousel-1.png "Carousel Default Image")

## Recent Projects Gallery

The recent projects gallery showcases the company's recent work. It is a space for advertising the diverse range of services that they offer and to encourage the user to explore ideas for a potential project they might have in mind.

The images are fully responsive, showing as a 3x4 Bootstrap grid on desktop and displayed in a vertical stack on mobile.

### Desktop View

![recent-projects-gallery](/documents/screenshots/recent-projects-1.png "Recent Projects Gallery")

### Mobile View

The images all have a CSS applied zoom transition on hover as well as the cursor which changes from a pointer to a zoom-in style cursor to encourage the user to click on them.

### See The CSS Transition in Action:

![recent-projects-image-css-rollover](/documents/screenshots/recent-projects-rollover.gif "Recent Projects Image CSS Rollover Transition")

Once clicked on, a Bootstrap lg modal appears showing a larger version of the image with a caption detailing the project and the location where it was done. 

### Image Modal

![recent-projects-gallery-modal-image](/documents/screenshots/recent-projects-2.png "Recent Projects Gallery Modal Image")

### Video Modal

![recent-projects-gallery-modal-video](/documents/screenshots/recent-projects-3.png "Recent Projects Gallery Modal Video")

## Areas We Cover

This section contains an interactive iframe from Google Maps. It is a custom map that highlights the boundary of where the company covers.

The iframe is fully responsive and allows the user to drag, zoom and open the map in a new tab for better viewing. 

![map-iframe](/documents/screenshots/map-iframe.png "Areas We Cover Google Maps iframe")

## Testimonials
The testimonials section shows the user the trustability of the company.

There is a link to Google Reviews showing a 4.5 Star rating.

![testimonials](/documents/screenshots/testimonials.png "Testimonials")

# 'Our Services' Page Features
All the images on the services page have Bootstrap's 'rounded-3' class attributed to them. They are all uniform in size in keeping with the site's theme.
The images are displayed in a Bootstrap grid with three rows of two columns on desktop and one coulumn with six rows on mobile.

### Desktop View

![our-services-desktop-view](/documents/screenshots/our-services.png "Our Services Desktop View")

### Mobile View

![our-services-mobile](/documents/screenshots/our-services-mobile.png "Our Services Mobile View")

## Lawn Maintenance & Pricing Plans

![lawn-maintenance-pricing-plans](/documents/screenshots/lawn-maintenance.png "Lawn Maintenance Pricing Plans")

The Weekly Lawn Maintenance feature is the main feature of the services page.
The user is asked a rhetorical question: 'Garden becoming a bit of a jungle?' to plant the idea that they can fix the situation by purchasing one of the service plans. 

The pricing is displayed using Bootstrap cards. This tells the user that these are products & services up for purchase and allows them to compare side by side, the included services of each plan to decide which is best for them. 

The 'Pro' pricing is displayed with a dark background. This is to make it stand out and convey to the user that this is a premium service. 

The 'Pro' pricing features the price in small, strikethrough text next to regular text (<sup> <s>£50</s> </sup> £40). This shows a limited time offer and urges the user to get in touch today to get a good deal on their service plan.


## Garden Redesigns

![garden-redesigns](/documents/screenshots/garden-redesigns.png "Garden Redesigns")

Below the list of services, is the Garden Redesigns section.
This is the area of expertise that Wigwam specialise in and are reknowned for. 
This section is placed below the list of services and is separated using a top-border to serve as a horizontal rule. This is because it is a specialist service reserved for customers who are looking for more than simple odd-jobs and light construction. It is for complete garden makeovers and big jobs.


This section utilises a Bootstrap collapse to hide large amounts of information. This streamlines the look of the page and improves UX. 
By default, when the page loads, this section is hidden. When the user presses the button, the section collapses to reveal the information. 

### See the Collapse in Action:

![bootstrap-collapse](/documents/screenshots/collapse.gif "Bootstrap Collapse")

## Redesigns by Wigwam <i>- Collapsed</i>

![redesigns-by-wigwam](/documents/screenshots/wigwam-redesigns.png "Redesigns by Wigwam")

This section contains the seven steps of a Wigwam garden redesign.
The steps are layed out using a Bootstrap grid system comprised of rows and columns. 
On desktop view, there are two columns and two items per row. Step 7-Completion, is an exception and is positioned in the center of the screen to signal to the user that they have reached the end of this section. There are four rows in total. 

On mobile devices, this shrinks to one column or one item per row stacked on top of one another.

The items are read left to right, top to bottom similar to a comic strip and are intuitive, easy to follow and easy to digest.
Text content is minimal so as not to bore the user with unnecessary detail. 

Each step is numbered 1-7 with a circular styled number. These act like bullet points and provide a consistent style and a point of reference for the user.

Again, like the rest of the site, the images are styled with a CSS rollover zoom transition and have the Bootstrap 'rounded-3' attribute applied for consistency. 

At the end of the section, there is a 'Back to Top' button which when pressed automatically scrolls back to the top of the section without the user having to manually scroll all the way back up.
Having this button improves UX and adds interactivity and user control to the site.

In future, the button that triggers the collapse will include JavaScript components to make it more obvious to the user that this is a collapsable section. An example of this might include a caret-right or chevron-right icon on or next to the button that rotates when clicked becoming something resembling a caret-down or chevron-down icon. 



## Why Choose Us?

![why-choose-us](/documents/screenshots/why-choose-us.png "Why Choose Us?")

The 'Why Choose Us?' section aims to tell the user why a Wigwam garden redesign is better than the rest. It features three circular images, each serving to represent one bullet point.
"The three P's" (Professional, Personal & Permaculture) are a simple and memorable way of getting the main points across to the user. 

The word 'permaculture' is hyperlinked and left with default hyperlink styling to make it obvious to the user that this is a link. The reason for this is that most users will not understand what the word means or the significance of it in the context of garden design. 
When clicked, it opens an article from 'Permaculture Magazine' in a new tab giving more explanation as to its definition as well as providing access to the 'Permaculture Magazine' site. From there, they can explore articles and learn more.
Wigwam Garden Solutions use permaculture substantially within their designs. It is one of the company's core values and it is important to them to spread the word and educate as many people as possible to its benefits. 


# About Us Page Features

## Logo & Awards Image

![about-us](/documents/screenshots/about-us.png "About Us Section")

The logo is positioned above the awards the company has won. This instills confidence in the company and showcases their achievements. 

## About Us Paragraph
This paragraph of text tells the user about the company and what it stands for. It focuses its content around sustainable design- one of the company's core values. It is important to Wigwam that this message is made clear to customers. 

## Meet The Team Section
![meet-the-team](/documents/screenshots/team.png "Meet The Team")

The 'Meet The Team' section tells the user more about the team behind the company and the roles within it.

The button to Nicole's pinterest portfolio allows users to view her previous work and saved pins. It also provides inspiration to customers about how they would like their garden to look. 

# Free Quote Page Features

![free-quote-page](/documents/screenshots/free-quote.png "Free Quote Page")

## Form

The Free Quote page contains a form where users can submit a request for a free quote.
There is also the opportunity for users to add any comments or questions they might have.
They can also upload multiple photos of their garden for Wigwam to better see the size of the job and the work required.

![form](/documents/screenshots/form.png "Form")

## Contact Info
At the bottom of the page is also all the company's contact info. This is displayed in a single row of four columns on desktop, and a single column of four rows on mobile. 
The email link is left with default hyperlink styling to tell the user that this is a link. When clicked, opens the user's default email client to send an email to Wigwam's email address. 
The social media links open each site in a new tab respectively. 

### Desktop View:

![contact-info-desktop](/documents/screenshots/contact-info.png "Contact Info Desktop View")

### Mobile View:

![contact-info-mobile](/documents/screenshots/contact-info-2.png "Contact Info Mobile View")

# UX
## Site Goals

The goal of Wigwam Garden Solutions is to showcase the company's work...

## User Stories

## Wireframes & Site Map
Wireframes for this site can be accessed [here:](/documents/wireframes.pdf)

A Site Map can be accessed [here:](/documents/site%20map.pdf)

### As a Customer:
- I want to...



### As the site Administrator:
- I want to...

# UI
The user interface comprises of a navbar to quickly navigate from page to page without the user having to press the browser's back button.


# Testing & Deployment
# Manual Testing
Explain the testing process, fixing bugs, include screenshots/code snippets...
Explain responsiveness and browser compatibility
Use the W3C Validator and provide proof of validation
Use Lighthouse to check for accessability/usability 

- Expected
Site is expected to do X when user does Y
- Testing
Tested site by doing Y
- Result
The site did not respond due to A, B, C
or
The site acted as expected and did Y
- Fix
I did Z to the code because of D
s
<table>
<tr>
<td>Feature</td>
<td>Expectation</td>
<td>Result</td>
</tr>
<tr>
<td>Navbar</td>
<td>When </td>
</tr>
</table>

# Bugs

## Our Services Page 

### Bug Found: 11/05/2023 18:30pm

The bug found was that the image (constructing.jpg) on the page was cut off at the bottom and not cropped to fit the container. Because of this, it didn't match the style consistent with the rest of the images on this page and across the site. 

![bug-1](/documents/screenshots/bugs/bug-1.png)

The CSS applied to the image was:

![bug-1-css](/documents/screenshots/bugs/bug-1-css.png)


### Bug Fixed: 12/05/2023 11:45am

The bug was fixed by adding a new style rule to the CSS targeting the image within the container. This made sure any image with this style rule applied, matched the size of the continer (div).

The style rule was updated to include this:

![bug-1-css-fixed](/documents/screenshots/bugs/bug-1-fixed-css.png)

This resulted in the bug with said image being fixed:

![bug-1-fixed](/documents/screenshots/bugs/bug-1-fixed.png)

### Bug Found: 12/05/2023 12:10pm

The bug found was that the image (moss-min.jpg) was ever so slightly, not aligned square with image above, and so stands out and is not consistent with the style of the rest of the images on the page. 

![bug-2](/documents/screenshots/bugs/bug-2.png)

After fault-finding this didn't appear to be an issue with the CSS but rather the HTML.
The HTML was:

![bug-2-html](/documents/screenshots/bugs/bug-2-html.png)

### Bug Fixed: 12/05/2023 12:15pm

The bug was fixed by removing the Bootstrap ("container-fluid") class attribute from the section.
The HTML is now:

![bug-2-html-fixed](/documents/screenshots/bugs/bug-2-html-fixed.png)

This resulted in the bug being fixed:

![bug-2-fixed](/documents/screenshots/bugs/bug-2-fixed.png)

# Automated Testing

Tested on selenium.dev

Tested on W3C HTML Validator

Tested on Jigsaw CSS Validator

# Citations & Acknowledgements
This website was built using Bootstrap v5.3.

## The icons on this site are taken from FontAwesome v6.4.0 and are:

- [campground](https://fontawesome.com/icons/campground?f=classic&s=solid)
- [trowel](https://fontawesome.com/icons/trowel?f=classic&s=solid)
- [people-group](https://fontawesome.com/icons/people-group?f=classic&s=solid)
- [pen-to-square](https://fontawesome.com/icons/pen-to-square?f=classic&s=solid)
- [star](https://fontawesome.com/icons/star?f=classic&s=solid)
- [star-half-stroke](https://fontawesome.com/icons/star-half-stroke?f=classic&s=regular)
- [user](https://fontawesome.com/icons/user?f=classic&s=solid)
- [building](https://fontawesome.com/icons/building?f=classic&s=solid)
- [martini-glass-citrus](https://fontawesome.com/icons/martini-glass-citrus?f=classic&s=solid)
- [list](https://fontawesome.com/icons/list?f=classic&s=solid)
- [chevron-up](https://fontawesome.com/icons/chevron-up?f=classic&s=solid)
- [phone](https://fontawesome.com/icons/phone?f=classic&s=solid)
- [envelope](https://fontawesome.com/icons/envelope?f=classic&s=solid)
- [location-dot](https://fontawesome.com/icons/location-dot?f=classic&s=solid)
- [hashtag](https://fontawesome.com/icons/hashtag?f=classic&s=solid)
- [facebook](https://fontawesome.com/icons/facebook?f=brands&s=solid)
- [instagram](https://fontawesome.com/icons/instagram?f=brands&s=solid)
- [pinterest](https://fontawesome.com/icons/pinterest?f=brands&s=solid) 



## The fonts used on this site are taken from Google Fonts and are:
- [Nunito Sans](https://fonts.google.com/specimen/Nunito+Sans?query=nunito+sans) (Designed by Vernon Adams, Jacques Le Bailly, Manvel Shmavonyan, Alexei Vanyashin)
- [Lato](https://fonts.google.com/specimen/Lato?query=lato) (Designed by Łukasz Dziedzic)


### Images:

All images & videos on this site are my own unless specified otherwise below:

- [florist.jpg](https://www.freepik.com/free-photo/man-florist-working-green-house_21795137.htm#query=gardener&position=4&from_view=search&track=sph)
by senivpetro on Freepik

- [matty.jpg](https://www.freepik.com/free-photo/rural-morning-close-up-beautiful-bearded-caucasian-male-farmer-blue-t-shirt-black-pants-smiling-working-farm-picking-crop-doing-favorite-job_9696954.htm#query=gardener&position=9&from_view=search&track=sph)
by cookie_studio on Freepik

- [ricky.jpg](https://www.freepik.com/free-photo/outdoor-shot-logger-having-rest-open-air-after-cutting-trees_15755920.htm#query=tree%20surgeon&position=4&from_view=search&track=ais)
by user18526052 on Freepik

- [lawnmower-min.jpg](https://www.freepik.com/free-photo/man-cutting-grass-with-lawn-mover-back-yard_8828102.htm#query=lawnmower&position=1&from_view=search&track=sph)
by senivpetro on Freepik

- [nicole.jpg](https://www.freepik.com/free-photo/woman-gardner-greenhouse_4410517.htm#query=female%20gardener&position=40&from_view=search&track=ais)
by senivpetro on Freepik

- [decking-2.jpg](https://www.freepik.com/free-photo/empty-wood-chair_1272911.htm#query=garden%20decking&position=20&from_view=keyword&track=ais)
by topntp26 on Freepik

- [meeting.jpg](https://www.freepik.com/free-photo/close-up-coffee-table-with-two-colleague_9960699.htm#query=meeting%20coffee&position=0&from_view=search&track=ais)
by lookstudio on Freepik

- [survey.jpg](https://www.freepik.com/free-photo/new-building-project_5400347.htm#query=construction%20survey&position=17&from_view=search&track=ais)
by pressfoto on Freepik

- [garden-plan.jpg](https://www.freepik.com/free-photo/crop-hands-using-template-stencil_2091845.htm#query=garden%20plan&position=47&from_view=search&track=ais)
by freepik on Freepik

- [tradie.jpg](https://www.freepik.com/free-photo/part-male-construction-worker_11230034.htm#query=tools&position=39&from_view=search&track=sph)
by gpointstudio on Freepik

- [planting.jpg](https://www.freepik.com/free-photo/overhead-view-hand-holding-small-fresh-potted-plant_2586588.htm#query=gardening&position=5&from_view=search&track=sph)
by freepik on Freepik

- [family.jpg](https://www.freepik.com/free-photo/happy-young-family-during-picking-apples-garden-outdoors_7652653.htm#page=2&query=family%20garden%20relaxing&position=8&from_view=search&track=ais)
by master1305 on Freepik

- [constructing.jpg](https://www.freepik.com/free-photo/carpenter-man-taking-measures-wood-plank_11106766.htm#query=screwing%20fence&position=35&from_view=search&track=ais)
by freepik on Freepik

- [moodboard.jpg](https://www.freepik.com/free-photo/green-houseplant-background-plant-lovers_17599271.htm#query=garden%20concept&position=20&from_view=search&track=ais)
by rawpixel.com on Freepik

- [pruning.jpg](https://www.freepik.com/free-photo/incognito-man-cutting-overgrown-bushes_26767885.htm#query=hedge%20cutter&position=9&from_view=search&track=ais)
by Artphoto_studio on Freepik

- [award-1.png](https://pixabay.com/vectors/laurel-wreath-roman-victory-black-156019/)
by OpenClipart-Vectors on Pixabay

- [award-2.jpg](https://www.freepik.com/free-vector/trophy_34295225.htm#query=trophy&position=3&from_view=search&track=sph)
by juicy_fish on Freepik


# Future Features
