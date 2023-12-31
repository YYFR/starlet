# Starlet Estates

Starlet Estates is a website for property management, sales and rental services.

## Table of Contents

- [Starlet Estates](#starlet-estates)
  - [Table of Contents](#table-of-contents)
  - [Introduction](#introduction)
  - [About](#about)
  - [Wireframes](#wireframes)
  - [Deployment](#deployment)
  - [Problems](#problems)
  - [Testing](#testing)
  - [Credit](#credit)

## Introduction

This website aims to provide end-to-end management services for rental property portfolios. It helps landlords find suitable tenants, facilitates property purchases and handles compliance and repairs.

## About

I chose to create this website as I had done some work in the property field.
The goal of this site is to reassure and provide peace of mind to landlords, the reviews section shows that they will be in good hands. This website has been made with a clear goal of providing peace of mind to property owners, which can be seen on the home page and the services.html page. The contact button has been designed as a strong call to action to allow potential customers to get in touch.

First Time Visitors:
Understand what the site is for and how to navigate the site. A description of what the site is is included on the home page. For more information regarding our services the user can see details of our services on the services.html page. The contact button has been designed to stand out on both pages, as the goal of the site is to attract new clients.

## Wireframes

The wireframes for this project can be found in the following links:

- [Paper Wireframe](assets/images/paperwireframes.jpg)
- [Balsamiq Wireframe](assets/images/homewireframe.jpg)

## Deployment

To Deploy the site using GitHub Pages:

Login (or signup) to Github.
Go to the repository for this project, <https://yyfr.github.io/starlet/>.
Click the settings button.
Select pages in the left hand navigation menu.
From the source dropdown select main branch and press save.
The site has now been deployed, please note that this process may take a few minutes before the site goes live.

This is the link to the deployed site on GitHub Pages:
<https://yyfr.github.io/starlet/>

This is the link to the source code on my GitHub repository:
<https://github.com/YYFR/Starlet.git>


## Problems

I have had many stressfull problems whilst creating this site.
Firstly I had been using the terminal incorrectly, which resulted in none of my work being submitted to GitHub for the first part of my project. I also stupidly didn't document my problems straight away and relied on remebering my problems which didn't work.

I have also tried to use Bootstrap in my project, however I only added it in middle of the project so it messed up some of the styles that were already working well, so I decided not to include it.

Another problem as seen in the Screenshot, was that I was trying to create 3 boxes to showcase our services, but I was trying to use a table to do that which wasn't ideal.

- [Screenshot of one of my problems](assets/images/Screenshot.png)

I also struggled with making sure the #cover-text works on smaller devices.

I fixed this html test fail by removing the section element from the div that was wrapped around the contact-button as it wasn't needed.

- [html test fail](assets/images/htmltestfail.png)

I fixed this contact.html fail by removing the unnecessary body tag as seen in the screenshot below.

- [contact.html test fail](assets/images/contacttest.png)

I tried to test the responsiveness of my website by using https://responsivedesignchecker.com/ however I received an error message response.
I fixed this by using the URL from Github Pages and not the URL of the website generated from the coding terminal. 

- [RESPONSIVE DESIGN CHECKER error message](assets/images/Responsivecheck.png)
  

  
## Testing

I used https://validator.w3.org to test for bugs in html.

- [html test](assets/images/htmltest.png)

I used <https://jigsaw.w3.org/css-validator/> to test for bugs in css.

- [css test](assets/images/csstest.png)

I also used Lighthouse from Chrome develepor tools.

- [Lighthouse Desktop](assets/images/lighthousedesktop.jpg)
- [Lighthouse Mobile](assets/images/lighthousemobile.jpg)

I have used responsivedesignchecker.com to test on desktop, tablet and mobile devices individually.

- [Desktop](assets/images/desktopcheck.png)
- [Tablet](assets/images/tabletcheck.png)
- [Mobile](assets/images/mobilecheck.png)

I viewed the desktop, laptop, tablet and mobile devices on a single page together, at https://ui.dev/amiresponsive 

- [Am I Responsive test](assets/images/amiresponsive.png)

I have also tested it in Chrome develepor tools on desktop, tablet and mobile, as well as shared the link with some family and friends who viewed it on desktop and mobile devices.

MANUAL TESTING:

Logo: The logo responds by becoming larger when hovering over it and takes you back to the Home page when clicked on.

Navigation Menu: All links have been tested and take you to the right page. The Navigation Menu is displayed on all 3 pages of the website to be able to move around between pages easily, without using the back button.

Background Image: The images reflect on the property theme of the site and load nicely on all pages. It also includes a zoom animation on the Home and Services page.

Background Image Text: The text is clearly visible and can be clearly seen on all devices. On the Contact page, the form is clearly displayed and matches the color scheme of the image.

Reviews: The reviews match the color of the Logo and are clearly visible on all devices.

Services: The Services section matches the color of the Logo and Contact button and stacks nicely when viewd on smaller devices as opposed to side by side when viewed on larger devices.

Contact Button: The Contact Button works on all pages and changes color when hovered over. The button has been designed to stand out nicely to attract potential clients to send their contact details.

Social Media Links: The links are consistent on all pages and have been tested to make sure they open in a new window.

## Credit

I started by looking at a couple of property websites to get a feel for what it should look like, I also looked at previous projects I had worked on to gain some inspiration.

<https://www.w3schools.com/> was also a good tool, they also allow you to run small snippets of code to see how they would work.

I used the Code Institute link https://formdump.codeinstitute.net/ to view submitted data from the contact form.

Images have been downloaded directly from google chrome.

- [FontAwesome](https://fontawesome.com/): The website uses FontAwesome for displaying icons.
- [Google Fonts](https://fonts.google.com/): The website uses the "Inter" and "Playfair" fonts with a fallback of sans-serif.

Last but not least Code Institute for providing me with a great facilitator as well as a great mentor and superb tutor support.
