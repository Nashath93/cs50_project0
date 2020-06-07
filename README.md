# Project 0

Web Programming with Python and JavaScript

In project0 I chose to design a personal website about myself. A template for a personal portfolio by using html, css, bootstrap and SaaS.

The website contains a custom css file, custom SaaS file, 4 html files and few images.

index.html file:
This page contains an unordered list and image. Unordered list has used to design navbar/menu and the image displayed in the menu.
A css media query has used to display only the last name when screen width reduced to 700px. Full name displays when the screen width larger than 700px

aboutus.html file:
This page contains three tables describing my personal details, qualifications and work experiences. Table designed using bootstrap.
CSS class and id selectors have used to change the colour of table header and table data.
All three tables have the same style of header. Therefore, SaaS inheritance technique used to extend a common table designing style to all three tables.

blog.html file:
This page contains blog posts. The page has divided into two columns using bootstrap grid (ratio: 10:2). First column contains a responsive banner/image about the post and blog description has written below the image. The next column contains list of recent posts.

contactus.html file:
This page contains a bootstrap form component with text inputs, email input, textarea and a button.
SaaS nested feature and variables have used to color the background of input fields.
the background colour of the page change to light blue when screen width reduces to 600px. Also, the background colour of the textarea field chenge to yellow when the width of screen reduced to 700px.

custom-style.css file:
this css file cotains .id and .class selectors more then 5 times.
@media quaries to change the font size of footer content and background colour when screen width shortened to 600px,

custom-saas.scss file:
This SaaS file contains variables, nested feature and inheritance feature, Inheritance feature used to design tables in about me page as it contains three tables with same header style.
Media queries used to display only the last name from full name when screen width shortended to 600px.
