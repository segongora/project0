# Project 0

Web Programming with Python and JavaScript

My project consists of a short and brief description of me, my interests and some recent events that occurred to me. I also include some pictures of me, and a contact page with my mail in it. It has 4 different .html pages which are:
- index
- photos
- about
- contact

It uses 2 different style.css, one being the normal .css stylesheet and the other being the .scss in which I use variables, nesting and inheritance.

Every .html file uses a navigation bar, a component I used from Bootstrap and which at the same time uses an unordered list. The nav bar had a styling so it will stick to the top of the page instead of being left out after scrolling and also color. The buttons used to navigate between the pages had some styling like font, font size and color, and have a class to 'deactivate' the button if it's in it's page.

In the first .html (index) is the main page, and I decided to use a Jumbotron to write recent events in my life, with a big title and a button at the end. The title uses a variable for the color given and the button uses inheritance for the styling and variable for the color. The button also redirects to the about page.

The second .html (photos) is just a page where I put some images of my semester abroad and use the column grid to create a two image layout and then just one. In this page I used responsive-mobile query so that when resized, the images would still look good and also taking advantage of Bootstrap columns so pictures would stack correctly. The titles in all pages have resizing with the use of @media .

The third .html (about) is a very simple page with an h1 title, and a table to show my likes and dislikes.
The table component, which I used from Bootstrap, has only the original Bootstrap dark-styling. I wrote there my likes and dislikes and thats all.

In the fourth .html (contact) I use a Bootstrap component called Card. I use a title, an image, a button and a footer. The title has responsive properties as well as the header and the image. I used nesting within the card components (header, body, image and footer) so it would be easier to organize and style this specific component. The button at the bottom which has a link to email me, also uses a variable for it's background color and a inheritance for normal and hover styling (which is the same as the first button in index).

That's my whole project, it's a very simple project but uses all of the requests made for this project.

Thank you for reading, Sergio Gongora.
