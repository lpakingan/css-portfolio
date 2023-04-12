# Bootcamp Challenge #2: CSS Portfolio

## Summary of the Challenge

In this week's challenge, we were tasked with creating our own website that would host our professional portfolio. This portfolio will highlight all of our progress as the course moves forward, and will showcase projects that we have completed or will complete.

## Acceptance Criteria
```
GIVEN I need to sample a potential employee's previous work
WHEN I load their portfolio
THEN I am presented with the developer's name, a recent photo or avatar, and links to sections about them, their work, and how to contact them
WHEN I click one of the links in the navigation
THEN the UI scrolls to the corresponding section
WHEN I click on the link to the section about their work
THEN the UI scrolls to a section with titled images of the developer's applications
WHEN I am presented with the developer's first application
THEN that application's image should be larger in size than the others
WHEN I click on the images of the applications
THEN I am taken to that deployed application
WHEN I resize the page or view the site on various screens and devices
THEN I am presented with a responsive layout that adapts to my viewport
```

## Strategy

#### Wireframing
The website was wireframed in order to get an idea of what types of formatting will be used used. The red boxes refer to containers, while the blue boxes are flexbox-affected elements within the containers. The wireframe used to plan out the portfolio page design is shown below: 

![](https://github.com/lpakingan/challenge-2-css-portfolio/blob/main/assets/README_images/wireframe.jpg)

#### Breakdown of Portfolio HTML/CSS Elements
To create the webpage, a combination of flexbox, media queries, and CSS elements were used. In order to maintain the responsive design of the website, flexboxes were implemented throughout the entirety of the page within the different sections. The flexbox container elements allow for dynamic resizing of their contents whenever the browser size is changed. Media queries were also utilized in further aiding in the responsive design of the website in different pixel resolutions, such as changing the horizontal navigation bar to be vertically aligned at a certain browser width. 

To make the website more interactive, other stylistic elements for hovering over images and links with redirects were added in CSS. Specifically, the navigation links in the header have lower opacity when not hovered over. When hovered over, they become full opcacity. Clicking on any of the navigation links brings the user down to the respective section on the webpage. A more involved hovering mechanism was used for the projects section. Like the navigation bar, the icons for the different projects in the Projects section are lower opacity. However, when hovered over, the icons become opaque and increase minimally in size by using the transform-scale property. Below is an animated gif displaying the website functionalities:

![](https://github.com/lpakingan/challenge-2-css-portfolio/blob/main/assets/README_images/portfolio_demo.gif)

#### Extra Notes
All images used in this challenge are placeholder images that were used just for this challenge only and will be swapped out in the future prior to the public sharing of the portfolio website. Twitter was added in the Contact Me section's navigation bar but does not redirect to a new page as I do not currently have a Twitter account but plan to in the future. 

## Deployed Application
The final deployed webpage can be found [here](https://lpakingan.github.io/challenge-2-css-portfolio/).
