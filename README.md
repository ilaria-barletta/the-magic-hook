# The Magic Hook
![The magic hook on multiple devices](assets/images/Site%20Devices.png)

This website is for crochet aficionados and people interested in learning the basics of crochet. It has everything one can possibly need to know before starting to crochet. It provides basic information regarding the first stitches to learn and useful links to youtube videos showing how the stitches are made. It's a guide anyone interested can use in order to quicky understand how to pick up a yarn and an hook and how to create something. 
/*Add link here to deployed website*/

----
## Features

__Navigation Bar__ :This section is present in all the pages and the style is consistent. It contains the name of the website, the logo (the logo image has been taken from google images), and a navigation bar to the home page, gallery and get in touch page. It is reponsive and the page in which the user is gets also highlighted for them to better locate themselves.
![The navigation bar](assets/images/navbar-readme.png)

__About me section__: The about me section has a background that let the user better understand what the website is all about and a small picture of myself (the backgroung image has been taked from google image and rotated by myself for aesthetic reasons). This section explains the intention of the website and it is my personal welcome to anyone who looks for it or simply finds it. 
![The about me section](assets/images/aboutme-readme.png)

__Basics section__ :This section consists mainly of two lists one for "tools" and one for "stitches". It is a brief but effective guide to start crochet and understand what's needed and how to work the stitches. In the stitches list, some are underlined. They are links and if clicked will take the user to youtube videos that are tutorials. They come from 2 channels in particular: "FiberFlux" and "Crochet Guru".
![The basics section](assets/images/basics-readme.png)

__Templates section__: This section is composed of 3 short but nice templates that will help the user in their first projects. All of them have backgrounds that I have made a bit transparent playing with opacity in css. The background images for the snowman template and the blanket template come from google images. 
![The templates section](assets/images/templates-readme.png)

__Footer__ :This section,like the navigation bar, is also present in all the pages and the style is as well consistent. I have styled the icons taken from fontawesome.com using colors close to the logo colors in the header section for aesthetic reasons. If clicked the icons will take the user to the facebook, twitter and instagram websites and they will all open in a new tab. 
![The footer section](assets/images/footer-readme.png)

__Gallery page__ :The gallery is composed by a series of images of crochet projects that I have arranged in a grid and that is responsive on different devices. The images come all from one of my personals instagram accounts. 
![The gallery page](assets/images/gallery-readme.png)

__Get in touch page__ This page consist of a form that lets the user contact me. The user details and contact information fields present a placeholder text to guide the user in fillling the form. The reason to contact me section instead as a checkboxes structure to let the user indicate the reason why they are contacting. 
![The Get in touch page](assets/images/form-readme.png)

----
## Testing
__Manual testing__ : I have tested the website manually to make sure it works as expected on multiple screens. The mediaquery are working as intended as, when resizing the page to different sizes, the elements behave correctly. I have also tested that all links open in a new tab and the form works as intended as well.
![Testing the form](assets/images/form-testing-readme.png)

__Validators__: The website has been tested using [css](https://jigsaw.w3.org/css-validator/validator?uri=https%3A%2F%2Fvalidator.w3.org%2Fnu%2F%3Fdoc%3Dhttps%253A%252F%252Fcode-institute-org.github.io%252Flove-running-2.0%252Findex.html&profile=css3svg&usermedium=all&warning=1&vextwarning=&lang=en#css) and [html](https://validator.w3.org/nu/?doc=https%3A%2F%2Fcode-institute-org.github.io%2Flove-running-2.0%2Findex.html) validators. All tests have returned no errors. The website has been also tested using lighthouse. Both desktop and mobile testing have returned accessibility of 100%.
![Validators html and css](assets/images/Validators-readme.png)
![Validator lighthouse](assets/images/Lighthouse-readme.png)

__Fixed Bugs__: While developing the website I have encountered some issues that have arised when I tested on different screen sizes. 

1. The basics section in the homepage was originally written using the float property. While resizing, the content would overlap and go to the wrong position making it really hard for the user to read. To solve this, the section is now re-written using a flex layout. 
2. The templates section originally had a fixed height that made the text go outside the containers when re-sizing. Removing the fixed height and adding padding to give the space around the content has solved the issue.
3. When writing the gallery, originally there were more columns that I had to reduce in order to make the images display nicely on all screens. 
4. The background images gave me some issues as they were not the right size to fit the containers (in some cases they were repeating and in some others they were too zoomed in). I had the issue on the homepage in the about me section as well as in the templates section. I also had the same issue when adding a background image to the form. By reasearching online I have found some css properties that let me decide how to display the image. I.e. background-position, background-repeat and background-size. 
----
## Deployment
----
## Credits 
1. The background image for the about me section and form comes from google images
2. The video links in the stitches section come from youtube. In particular they come from 2 channels: "FiberFlux" and "Crochet Guru".
3. The templates images were taked from google images
4. The icons in the footer were taken from [Font Awesome](https://fontawesome.com/)
5. The images in the gallery page come from one of my instagram accounts: "Littletreasure365".
6. The code to make the social network links was taken from the CI Love running project