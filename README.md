# my-profile-starter-main

updated my website 

One of the major purposes of a portfolio website is to show off your projects. So we'll need to build a section to showcase projects you've worked on in the past.

This section is probably the most tedious to style, but Flexbox won’t stop being our friend.

The HTML for this section is in the code snippet below:
Looking at the HTML, there are three projects in total, all in their individual divs with the class name of project-container and project-card. These class names will be instrumental in styling the projects consistently.

The containing section element itself has a class of projects, and an id attribute of projects as well. The class name is for styling, and the id is for linking it to the Projects link on the navbar.

The projects have their individual images with the class name of project-pic, their titles with a class of project-title, more details with the class name of project-details, and links with the class name of project-link.

How to Style the Project Section
First of all, I will give the whole section a background color by setting the greyish color (--bg-color) we declared in the CSS variables as the value.

I will also reduce the width and height of the project images by usung the project-pic class. Then I'll use Flexbox to put the projects side by side.What is the script above doing?

The first line selects the scroll-to-top button with the id attribute attached to it in the HTML. We used the querySelector() method here. You can also use the getElementById() method.

In the remaining lines, I used the click eventListener to get the user’s click action and exploit the scrollTo part of the windows object to make the button functional.

With this functionality, when the user clicks on the scroll-to-top button, the page scrolls to the top and left side of the website smoothly. I did this by setting top to 0, left to 0, and behavior to smooth.
