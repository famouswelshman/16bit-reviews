# MILESTONE 3 – Data Centric Development 

Github Link: https://github.com/famouswelshman/reviews-16bit.git

Website is hosted via Heroku and can be found via link : https://reviews-16bit.herokuapp.com/

# Purpose of this project – Milestone 3
The purpose of this project was to create a User friendly, front and back-end application to allow user to Create, Read, Update and Delete data under their own user login.

Users can read review data and registered users can view, add, edit and delete their review data.

A website application that allows users to view 16 bit console game details and user reviews by method of search using key words in relation to the console brands available or key words pertaining to the games featured on the site. Upon completion of user registering a username and password, user can further search and add their own reviews alongside the game and click on a star based rating function. User will be able to edit and/or delete their reviews and whilst this information is visible to all users, editing and deletion will only be achieved by the user who added this.

# Project Ideas

Retro game reviews
16 bit game reviews
To build a retro games review website application allowing users to add, edit and delete their own review content.

## Name Ideas:

Retro Ratings
16 Bit Reviews
16bit.com
BitBit
Megabit Reviews
Retro Reviews

## Definition of the genre:
16 bit (4th generation console games) including: 
Mega Drive
Super Nintendo
Neo Geo

## Main Technologies
Required: HTML, CSS, JavaScript, Python+Flask, MongoDB
Additional libraries and external APIs which include Bootstrap.

* Html & CSS
* Python + Flask
* MongoDB
* Heroku
* Jinja
* Javascript / Jquery

## Optional
* Bootstrap material design
* Materialize (Pre built page layout)

# User Stories:
* Visitors want to know more about the content of the site.
* New visitors want to easily navigate the website.
* User wants to view the website content on any device including a desktop and a mobile handset.
* Users want to register their details on the site to be able to add their own reviews.
* User wants to be able to search the home page for review information using text search words such as game name or console name.
* The user wants to be able to view other user reviews.
* Users want to be able to edit and delete their own reviews.
* User wants security features in place so that other users cannot edit or delete their own reviews.

### User story 1
First time user will visit the website application and be able to view a homepage consisting of a layout of reviews based on users input. They can search the application via the search facility in order to return reviews which are relvant to their search. This could be a search for a specific console or a game name or indeed review content. The user can then view this content in their own interests.

### User story 2
First time user can view the content of the application via the home page and navigate via the navbar to registration page and create an account. Once user is logged in they can still view all review data content but logged in functionality allows them to create their own reviews and add to the application which in turn will show via the home page. 

### User story 3
User who is logged into the account would like to open all the review data relevant to their account and they can do this by clicking on the ‘Manage your reviews’ link within the navbar. This page will filter and display all the review content relavent to the user. 

### User story 4
User who is logged into the account would like to return to their previous review and edit this to either add to the content or simply amend it and be able to save this which will in turn update to the backend database and then return to display on the homepage. Alternatively, user can access their review information and be able to delete this from the application all together, in turn removing this data from the database.

## Structure:
* Each web page will display consistent Navbar and footer along with hero image.
* Layout will display the review data in a semetrical display allowing users to click and open upon command. Search function will allow user to quickly group 
reviews relevant to their search word.
* Review data will load up on seperate page and providing they are the user logged in will allow edit and delete functions.

# Website UX
The idea was based on similar review based websites but for the purpose of reviewing a selective genre of video games, namely the 16bit era of gaming.
Users can access the website and instantly view reviews set out on the home page. There is a search bar function that allows the user to quickly search for specific review details according to their requirements.

The website is basic in it's design and layout but this adds to the simplistic theme of the site which is based on the 16bit game genre. Content is bold and bright and the website is easy to navigate.

Users have the facility to create a login via the login page where a username and password are required for setup and to protect their details. This then allows registered users to to create their own review information and add it to the the application and/or edit or delete this information further.

## Features:
* User friendly, responsive site that loads quickly and is intuitive. Immediately displays the content and shows the purpose of this application.
* Simple Navbar to quickly navigate to the relevant pages that is also collapsable for smaller media.
* Search and filter feature to display relevant reviews based on category search items.
* Users can add, edit or delete their own reviews and can view other users reviews but cannot edit or delete.


# Nice to have features
Since the home page of the app is displaying all content review cards then it would be nice to intergrate some pagination which would be able to layout the review cards 
according to a page system enabling the user to scroll through pages of layout rather than have to scroll down screen and view everything entered as content onto the application.

Although the user can add their reviews, the application doesnt currently support the ability to host all reviews relevant to the same game name. In other words, the single topic of one game does not allow users to add their reviews specifically to this game title, something that can be further implemented by adding all game choices to the Mongo Database and allowing the user to select at the time of creating a review. All similar reviews can then be grouped under that game name heading so the user has access to all reviews which are in relation to that specific game name.

In this project I did not implement a 404 error page if there was a break in the program, something I would like to introduce in the future so that the user is aware that they have
got to an area which is not valid. This is typical of a scenario where another user could type in the edit_review function directly into the browser but since I have edited the code to return the user to log in screen this might be something for future projects where a 404 error page would instead pop up to notify the user that this is not possible and to return to another page within the application.

A nice feature to have would be a like facility where users have the ability to click a thumbs up or a thumbs down function per review and/or a star ratings visual on each review to show to users how others have ratef their review content.

An admin account facility that can control all activity across the application.

# Future Features
Links to retro gaming purchase websites.
Forum and/or chat facilities within the application allowing users to discuss various topics in relation to this genre of retro gaming.

# MS3 Wireframes ---- Using Balsamic
So the early design ideas were centered around a sort of Netflix style web application, displaying multiple review content on the home page and the allowing the user to 
search by key words for review data relevant to the search and then being able to open that review detail in full on a seperate template on page. The overall design had to be quite bold and vibrant since the subject was retro video games. I designed the project specifically to cover the 16 bit genre of gaming since this would limit the amount of content submitted and this was a personal choice of mine since I have a keen interest in retro games as opposed to more modern day gaming consoles.

The key here was to present the review data in a symetrical fashion and allow the user to scroll through the page either before or after search. I did also consider 'pagination' of the content since the overall content submitted could be quite significant.

The home page would display multiple reviews and the responsive element of the page meant that the amount of content shows would be reduced based on screen media sizes.

## Desktop Home Page Template
![wireframe1](https://github.com/famouswelshman/reviews-16bit/blob/main/static/wireframes/desktop_home.png)

## Desktop Open Review Page Template
![wireframe2](https://github.com/famouswelshman/reviews-16bit/blob/main/static/wireframes/desktop_review_template.png)

## Medium Media Open Review Page Template
![wireframe3](https://github.com/famouswelshman/reviews-16bit/blob/main/static/wireframes/medium_review_template.png)

## Mobile Open Review Page Template
![wireframe7](https://github.com/famouswelshman/reviews-16bit/blob/main/static/wireframes/mobile_review_template.png)

# Database Schema (MongoDB)
![MongoDB_schematic](https://github.com/famouswelshman/reviews-16bit/blob/main/static/wireframes/MongoDB_Schematic.jpg)



# Validation

# Code Validation
## HTML
HTML code for all pages passed through W3C Markup Checker shows some warnings and errors in relation to Jinja templating.
## CSS
CSS code passed via WC3 CSS Validator with no errors.
## Javascript
Checked via Jshint.com and no errors
## Flask (Python)
1 error remains showing under Gitpod for app.py and this shows 'env' imported but unused. This instruction to include environment was in the training module
therefore kept this code in the Flask/python app. Some warnings included the addition of Docstring which I then included in the app.py. Warnings that still
remain visible are in relation to placeholder image not conforming to Upper case although this does not effect the functionality of the application.

# Testing
Testing done within browser via Dev Tools
My testing of the application was done predominantly using Google Chrome from desktop. The application is responsive via Dev tools and although the application content is slightly compremised on smaller devices it’s still viewable and the functionality is still available. Content on a medium media device shows the content similar to desktop. The colapsable navbar is available and makes for easy navigation.
Links within the application such as image and script were updated as url_for links in order to function across the application hosted via github and Heroku. In the first instance of creating this application I maintained static links which would not display when uploaded via Heroku.

# Bugs
The bugs in this project came about if user were to copy and paste an edit/delete link from another user id into the browser. I managed to edit the app.py file so that In the event that a different user would attempt to add an edit or delete extension to the file, flask would identify the user and if the current user was incorrect then the function would refer the user back to the login page in order to prompt the user to login.

Issues with the loading on the Gitpod IDE. Seemed that there were server issues causing the environment function to stop communicating. By stopping the workspace and re-loading managed to fix the fault.

# Account creation
Several registrations made on the site to prove that this functionality works. The database records the username and password and access to the application is then valid.

# Functionality
The user logged in allows access to their respective review content, allowing to edit and delete their content only. User who is logged in does not have access to other user review content and cannot edit and delete any data other than their own.

## HTML
Testing for responsive element of this app took considerable time although i chose a pre built template from Bootstrap as the framework for my front end application but this required additional
containers and the use of a cards insert from Bootstrap to visually display the review data.

## CSS
The css file was built on basic structure to ensure the application was responsive. Part of the css file was part of the Bootstrap pre-built web page which I factored into use in this project.

## Javascript
Minimum of Javascript was added to this project but the feature included is a fail safe prompt which actions a dropdown prompt to the user when they click on the delete button in order to delete a review. This function prompts the user to acknowledge their request to delete and allow user to complete this action by confirming yes to delete or no to return to the content.

## Flask (Python)
Creation of the app.py based on the Flask framework within Python incorporates the main functionality as per the code institute learning module but in addition to this includes original functions for user to view their own content grouped together on the 'Manage your reviews' page and being able to access individual review content by its respective id according to Mongo DB.

# Project Challenges
Getting the review cards to show up in sequence and semetrically on the home page required selecting use of Bootstrap grid code to enable the content of each review to show in a structured fashion on screen and be responsive to all media screen sizes.
&nbsp;
&nbsp;
![name](https://github.com/famouswelshman/reviews-16bit/blob/main/static/wireframes/card_template.jpg)]


![img input](https://github.com/famouswelshman/reviews-16bit/blob/main/static/wireframes/image_input.jpg)]
&nbsp;
Since I wanted to include a URL image address input in the 'Create_review' the image link submitted would then need to be visible within the review cards. In order to achieve this, the correct use of {{}} and its respective link was used - "img_url": request.form.get("img_url"). This maintained a connection to the database and the specific img_url category in the reviews collection in order to return the img_url data.

![img_after](https://github.com/famouswelshman/reviews-16bit/blob/main/static/wireframes/image_input_after.jpg)]
&nbsp;
&nbsp;
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
* https://www.romsgames.net/ - using their game covers as address link url's


# Other Credits
StartBootstrap - E-Commerce template downloaded and customized for project
https://pretagteam.com/ - Javascript Pop-Up to notify user before deletion of data.


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




