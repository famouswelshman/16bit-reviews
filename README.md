# MILESTONE 3 – Project Ideas

Github Link:

Website is hosted via Heroku at :

# Purpose of this project – Milestone 3
The purpose of this project was to create a User friendly, front and back-end application to allow user to Create, Read, Update and Delete data under their own user login. CRUD

User can read and user registered can add, edit and delete.

A website application that allows users to view 16 bit console game details and user reviews by method of search using key words in relation to the console brands available or key words pertaining to the games featured on the site. Upon completion of user registering a username and password, user can further search and add their own reviews alongside the game and click on a star based rating function. User will be able to edit and/or delete their reviews and whilst this information is visible to all users, editing and deletion will only be achieved by the user who added this.

# Project Ideas

Retro game reviews
16 bit game reviews

## Name Ideas:

Retro Ratings
16 Bit Reviews
16bit.com
BitBit
Megabit Reviews
Retro Reviews

## Definition of the genre:
16 bit (4th generation console games including: 
Mega Drive
Super Nintendo
Neo Geo

## Main Technologies
Required: HTML, CSS, JavaScript, Python+Flask, MongoDB
Additional libraries and external APIs

* Html & CSS
* Python + Flask
* MongoDB
* Heroku
* Task Manager
* Jinja
* Javascript / Jquery

## Optional
Bootstrap material design
Materialize (Pre built page layout)

# User Stories:
* Visitors can want to know more about the content of the site.
* New visitors want to easily navigate the website.
* Users want to register their details on the site to be able to add reviews and rate the game.
* The user wants to be able to view other user reviews.
* User wants to be directed to where they can buy the game.
## Features:
* User friendly, responsive site that loads quickly and is intuitive.
* Simple Navbar that is also collapsable for smaller media.
* Search and filter feature.
* Users can add, edit or delete their video games data and review.
## Structure:
* Each web page will display Navbar.
* Layout will display the games in a semetrical display.
* Game and review data will load up on each page.


# Website UX



# Website features


# Future Features

# Page Layout, Typography and Color Scheme

# MS3 Wireframes ---- Using Balsamic

# Database Schema (MongoDB)

User Collection
Schema



Games
Schema

# Testing

## HTML
## CSS
## Javascript
## Flask (Python)



# Validation

## HTML
## CSS
## Javascript
## Flask (Python)

# Summary of Testing
# Project Challenges
Getting the review cards to show up in sequence and semetrically on the home page required selecting use of Bootstrap grid code to enable the content of each review to show in a structured fashion on screen and be responsive to all media screen sizes.
&nbsp;
&nbsp;
![name](https://github.com/famouswelshman/reviews-16bit/blob/main/static/wireframes/card_template.jpg)]


![img input](https://github.com/famouswelshman/reviews-16bit/blob/main/static/wireframes/image_input.jpg)]
&nbsp;
Since I wanted to include a URL image address input in the 'Create_review' the image link submitted would then need to be visible within the review cards. In order to achieve this, the correct use of {{}} and its respective link was used - "img_url": request.form.get("img_url"). This maintained a connection to the database and the specific img_url category in the reviews collection in order to return the img_url data.

![img_after](https://github.com/famouswelshman/reviews-16bit/blob/main/static/wireframes/image_input_after.JPG)]
&nbsp;
Fixing the review form together to be responsive and capture the data with (required), ensuring the correct database fields where added to transfer data to MongoDB.




# Deployment

## Github
https://github.com/

I originally had a Github account setup for previous milestone submissions therefore for this project the same setup applied albeit this time, since the 
project code is driven by python then Github would serve as a virtual platform to host the files and have the files be accesible for marking.
Since this project is driveN by Python(Flask) then Github would not be able to host this as a complete, functioning application and was therefore linked to Heroku.

# Gitpod

My project was created using the Gitpod IDE. All folders and files were created and saved to the repository and the workspace was accessed daily to edit, create and delete 
the neccessary content. Since this projects content required numerous dependencies, it was recommended that we use the Code Institute full template since this came with 
all the neccessary pre-installed tools to enable use of the various programs. Project created included regular commits to show detail of its construction. Final project accessible via Github, main branch set to public.

## Heroku
https://id.heroku.com/login

In order to run this project application, an account was required to be setup via Heroku. Deployment setup required which required connection to the Github repository and then
creating the app in order to view. In order for the data to be accessed from MongoDB, we had to setup the connection details via the Confi Vars input fields where the DB name and secret key will be stored. This process of linking both Github and MongoDB was shown via the Task Manager mini project during the learning modules therefore the process
of it's setup was relatively straightforward and differs slightly in that unique database name and connection details would be different.

## MongoDB
https://account.mongodb.com/

In order to meet the project requirements, the use of MongoDB as a non-relational database was required. Here is where the data is stored as a result of the python app submit functions running on the application. In turn, selective data is then returned to the application to be read, edited and deleted as per the user who is signed into the application. The connection between the project files and the DB is maintained via the env.py file and this is classed as hidden and does not get uploaded to Github for security purposes.




# Media Credits
* www.16bitgladiators.com - Use of art for custom Logo created with Photoshop

# Other Credits
StartBootstrap - E-Commerce template downloaded and customozed for project

## Libraries used
* Flask a framework of Python used to build the web application.
* Jinja template language.
* PyMongo used to link Flask and MongoDB database.
* MongoDB was used for the database.
* Bootstrap used for content styling.
* Font Awesome for font and symbols.
* StartBootrstrap used for pre-built page layouts.
* Jquery (Javascript) included in the project for front end animation of buttons and navbar, dropdown etc.
* Werkzeug used for hash password security.
* GitHub used for Git version control and Gitpod was used for IDE.
* Heroku used for deplyment of the application.

---------------------------------------------------------------------------------------------------------------------------------------------------------

# NOTES - To be deleted upon completion of the Readme 

* Feel free to reuse the authentication from the mini-project. The focus of this milestone project is on the data, rather than any business logic.
* If you reproduce someone else's work, you must credit it.
* 




SUBMISSION PROCEDURE:
You should submit your milestone project for this module by filling out the form on the Project Submissions page and providing links to both your source code on GitHub and the live deployed project (e.g. on Heroku or GitHub Pages). Submit each project whenever it's ready so that you'll be able to use the assessor's feedback to guide your work on the following projects.

-----------------------------------------------------------------------------------------------------------------------------------------------------------