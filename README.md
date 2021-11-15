# Professional Portfolio

## This week's task was to create a professional portfolio that can be revisted and updated over time. The site should be created with HTML and CSS and showcase some of the things we've learned in the first few weeks of the program. 

Link to portfolio: https://chris-tijerina.github.io/professional-portfolio-ctijerina/

The assignment was framed with the idea of what a potential employer would be looking at. For example: 
>as an employer I want to view a potential employee's deployed portfolio of work samples so that I can review samples of their work and assess whether they're a good candidate for an open position

There were a set of recommended things I could do that would give an employer a good idea of my previous work. I will describe them and my approach to them below: 

>when I load their portfolio then I am presented with the developer's name, a recent photo or avatar,and links to sections about them, their work, and how to contact them.

I did some research into effective portfolio design and found similar themes and ideas to when I researched how to make a good resume, so I followed a similar pattern. I chose a color palette that would keep my page consistent, engaging, and would fit accessibility standards for contrast. I also wanted to make sure that my sections and tiles for work were properly set up for screen readers. 

I sketched a box model image that looks similar to the finished product to start with and started thinking of the different css elements I would use before I got started. 

Outside of a picture and my name, I knew that I would have 4 different works that I've done and my contact information at the bottom. As far as my contact information is concerned, I left out any information that would normally be part of an application process, such as phone number and address, as including it could be an issue on a publicly available page. 

>When I click one of the links in the navigation then the UI scrolls to the corresponding section

>When I click on the link to the section about their work then the UI scrolls to a section with titled images of the developer's applications

This portion was simple by using ```<a href>``` for the different sections, but I did notice an issue with the scroll not actually going to the top of section due to the sticky navigation bar. So I had to add in a ```scroll-margin-top``` in order to offset the size of the nav bar. 

>When I am presented with the developer's first application then that application's image should be larger in size than the others

This was where I deviated from my original design after I was working on the tiles for the different works. While using the Chrome Dev Tools, I was able to tweak the size and shape of the tiles until they fit the criteria and also looked good. 

>When I click on the images of the applications then I am taken to that deployed application

This part ended up being tougher than I thought it would be. I originally had background images on the content tile itself, only to find out that it would clash with the clickable image. A little research showed a way to create a clickable image link through the use of ```<a href>``` that would have a link to the text, but an ```<id>``` that would allow me set a background image and all the formatting for the tile in the css. 

>When I resize the page or view the site on various screens and devices then I am presented with a responsive layout that adapts to my viewport

In order to make sure that everything looked well on a mobile device I spent time in Chrome Dev Tools to resize the viewport and make changes based off of what was or wasn't working out. Using flex boxes and % size, it seems to have been successful. 


