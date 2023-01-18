# [RomCom](https://jfogiato.github.io/romcom/)

## Abstract:
[//]: <>
We built a web application that allows users to generate random book covers from a pre-populated list of options. The app will generate a random cover, title, and tagline with two descriptors when the user clicks the appropriate button. The website will allow users to create their own book by inputting an image link, title, and descriptors into value fields within a form. Users can save & delete both randomly generated and user-created books to a section within the website. 
## Installation Instructions:
[//]: <> 
To access our application, go to [the project repository,](https://github.com/jfogiato/romcom) click on the green "Code" button and copy the SSH key. On your local machine, navigate to the directory location you want to use, and run the command `git clone git@github.com:jfogiato/romcom.git` to clone the repo to your local machine. In your terminal, change directories into the newly-cloned repo and run the command `open index.html` to open and run the program.
## Preview of App:
[//]: <> 
![ezgif com-gif-maker (2)](https://user-images.githubusercontent.com/57634618/206923458-0177fe05-aabb-4b4f-b768-74909a62c92d.gif)

## Context:
[//]: <> 
This project was assigned as our first paired assignment at Turing. It was a Javascript-based assignment that implemented understandings of how to use the DOM to affect and insert new HTML elements and CSS classes. The project took us 20 hours to complete and we successfully implemented all required functionality, abiding by Turing style standards and SRP/DRY principles.
## Contributors:
[//]: <> 
[Winston Calhoun](https://github.com/WinstonCalhoun)

[Joe Fogiato](https://github.com/jfogiato)
## Learning Goals:
[//]: <> 
The learning goals of this project were (1) writing clean, DRY Javascript, (2) exploring the connection between HTML, CSS, and JS, and (3) writing code collaboratively. We used GitHub, VS Code, Chrome DevTools, and interfaced with Git/GitHub using terminal commands. We worked on all parts of this project collaboratively using the driver/navigator method through Zoom. 
## Wins + Challenges:
[//]: <>
Going into this project, we had very minimal experience working with HTML and CSS. We were able to read and understand the HTML/CSS code given to us and implement solutions to manipulate it via Javascript. 

We successfully understood and implemented the use of global and local variables by using global variables as placeholders to be reassigned when necessary throughout our code, as well as assigning additional variables to the relevant DOM elements. 

We successfully built functions to manipulate both user facing data via DOM elements, and data structures within the codebase. 

An initial challenege that we faced was understanding how to initiate two event handlers to a single listener. We initially circumvented this by opting to ignore SRP and build our function to have multiple responsibilities, but after learning about event listeners more in-depth, we broke out the function into two handlers and used an anonymous function to call them both at once.

The biggest challenge we faced was implementing a listener on a child section within one of our elements. We eventually implemented a solution that appended a listener on the child element and used a listener at the parent level to trigger the functionality we needed. 
