# P2 Slugs - Recipe Website
# _Recipebox_
Recipebox is a website centered around recipes, where you can filter through recipes, select ingredients that affect your money and amount, create a recipe, and give input to the website that will be displayed as a community suggestion! It is a fun project that was inspired by Zelda's game Breath of the Wild, with the ingredients selection part and interesting food names! This project helped us learn A LOT throughout Trimester 2. We gained experience working with the languages HTML, CSS, Python, and Javascript. We learned how to use GET/POST requests, got a lot of practice with app routes, learned how to layout and run our website through a views and wsgi file, learned how to work with data and transfer it across pages using Jinja, got practice with algorithmns and programming skills like functions and varibales, and used Javascript functions to do cool actions on the frontend! We even learned a lot about deployment and setting up a virtual enviornment to run our project. Our website is running from a Raspberry Pi and we have an accessible domain name to anyone. This project allowed us to learn the AP CSP College Board Fundamentals and show our knowledge in one place. As a team, we collaborated, worked toegther, and took planning steps each week to reach our goals.


## Check out our [Padlet](https://padlet.com/evag55486/yrby94rn6jf2s3dm) with more detailed information about our project!
Team Members: Eva Gravin, Sophie Lee, Ali Saad, Linda Long

## Project Links:

### > [Scrum Board](https://github.com/p2slugs/recipebox/projects/1) (tracking sheet + schedule) | includes ticket items/cards

### > Link to Running Code: http://recipebox.cf | [Git Repository](https://github.com/p2slugs/recipebox/)

### > [Easter Egg Location](http://recipebox.cf/easteregg?)

### > [College Board Project Considerations](http://recipebox.cf/easteregg?) located in CB Targets Page of Easter Egg

### > [The Recipe Box Commercial](https://youtu.be/d6E0ru6qDYM)

## Instructions on How To Run
You can run our website from any device by going to this link: recipebox.cf. You can also run our code on your own computer by downloading the repository files. 

You will be directed to the home page, where an overview of the website is given. Toggle through the tabs at the top to explore the website!

You can put in a recipe, suggestion, buy ingredients, and view the about us page, contact page, home page, and sign up form.

## Descriptions on Project Technicals and Meeting College Board Requirements

### HTML & CSS
sophie: gave home page a new look (updated the css and html). we now have more color, a website that has larger text and more elements (rather than the previous minimalist look), and a nicer dark mode appearance. as you can see on the repl sample code, we now have an webpage icon on the tab and a different looking cursor and scrollbar. since this is a completely new html and css code, I am working on repl as I feel that it is less risky to make sure I don't lose any important information. I've been learning more about css elements and commands, as well as javascripts.

[scrum board ticket](https://github.com/p2slugs/recipebox/projects/1#card-54300634), [code on repl](https://repl.it/@sophieleeajh/recipebox#index.html), [view site on repl - LINKS DO NOT WORK B/C I ONLY WORKED ON HOMEPAGE THIS WEEK](https://recipebox.sophieleeajh.repl.co/)

### Ingredients Page
eva: Users can select ingredients from the inventory and they will get highlighted in the right column. The buttons turn green when you select them, and all of this was done using Javascript functions and events. Also, when each ingredient is clicked, it increases the user's amount of ingredients by 1. And, the amount of money that the ingredient costs, gets subtracted from the total starting amount. This was done by using functions, varaibles, and if/then/else statements. The data for each of the ingredients' information is displayed from the ingredients.py file using Jinja and a for loop. It aligns with the College Board requirements and our goals because it uses algorithmns, procedures, lists, variables, functions, and dictionaries in our project.
sophie: compiled information for all the ingredients necessary for the database (ingredients.py)

[See Ticket in Scrum Board](https://github.com/p2slugs/recipebox/projects/1#card-55130180), [See Code, ingredients.py](https://github.com/p2slugs/recipebox/blob/main/ingredients.py), [See Code, ingredients1.html](https://github.com/p2slugs/recipebox/blob/main/templates/ingredients1.html), [See Runtime Page on Website](http://recipebox.cf/ingredients1)

### Terms and Conditions Page
linda: Users can now access the Terms and Conditions page, which tells the customer what will be legally required of them if they subscribe to our service. Including sections such as definitions, acknowledgements, disclaimers and disputes resolutions, the T&C agreement protects our team and helps us developers to notify and communicate with users in advance. It aligns with the College Board requirements and our goals because we plan to implement more algorithmns, procedures, and use of lists in our project.

[See Ticket in Scrum Board](https://github.com/p2slugs/recipebox/projects/1#card-55262851), [See Code](https://github.com/p2slugs/recipebox/blob/main/templates/terms.html), [See Generated Terms and Conditions](https://www.termsfeed.com/live/2590dfed-f4b7-4b3a-b46f-559db16d0ac0)

### Social Contact Page 
ali: This is going to be a page where users can access the developers contact information like email, phone numbers, and youtube videos/channel. It is a good addition to the website because it gives information about us and allows the users to contact us. It connects to the users and hopefully allows our website to have a greater impact on the web and in the community. This aligns with the College Board requirement, the impact of computing. It shows how we have coded something that can have an outreach to people.

[See Ticket in Scrum Board](https://github.com/p2slugs/recipebox/projects/1#card-54727793), [See Code](https://github.com/p2slugs/recipebox/blob/main/templates/contact.html), [See Runtime Page](http://recipebox.cf/contact)

### Easter Egg
sophie: designed a secret(?) page for the easter egg and put in information for our journals, AP learnings, ourselves, and addition information/resources. compiled all the various easter files into one main file to avoid confusion and messy organization. easter egg page can be found under the about us.

[See Ticket in Scrum Board](https://github.com/p2slugs/recipebox/projects/1#card-54300711), [See Code](https://github.com/p2slugs/recipebox/blob/main/templates/easteregg.html), [See Runtime Page](recipebox.cf/easteregg)

### Recipes Page
sophie: gathered data for the many recipes from the game we were inspired by; used a filter system to organize all the different types of potential dishes users can cook (organized by buff and category of food). added descriptions of each meal and featured what the ingredients necessary for the dish. also learned how to host files (images on the page) via Dropbox and made use of javascript animations.

[See Ticket in Scrum Board](https://github.com/p2slugs/recipebox/projects/1#card-55043364), [See Code](https://github.com/p2slugs/recipebox/blob/main/templates/recipes.html), [See Runtime Page](recipebox.cf/recipes)


### About Us Page
eva: Uses the files about.html and aboutus.py to display every team member's data from py file. The py file defines each group memeber and uses variables to store different things like their name, fact, and grade. Another variable called profile makes a dictionary with the previous variables and is returned. Finally, a list with each defined person is returned as about. In the html page, it does for about in aboutus, and then sets all of the variables equal to what they are goes through them. This is how the data is filtered through and displayed. Jinja is used for the variables. This uses dictionaries, lists, data, algorithms, and a for loop which matches with the College Board requirements.

[See Ticket in Scrum Board](https://github.com/p2slugs/recipebox/projects/1#card-56565556), [See Code, aboutus.py](https://github.com/p2slugs/recipebox/blob/main/aboutus.py),[See code, about.html](https://github.com/p2slugs/recipebox/blob/main/templates/about.html) [See Runtime Page](http://recipebox.cf/about)

### Raspberry Pi Deployment 
eva: The website is running from a Raspberry Pi, and the domain name allows it to be easily accessed by anyone and reached by the community (a CollegeBoard requirement, impact of computing). It uses linux, nginx, and gunicorn to set up a virtual environment to run the webiste. We can verify the status of it running and update the link when the we make changes through Github by perfoming git pull. In order to run like this, our website has a wsgi.py file, in addittion to our views.py files, and a requirements1.txt file.

[See Ticket in Scrum Board](https://github.com/p2slugs/recipebox/projects/1#card-52932294), [See Code, wsgi.py](https://github.com/p2slugs/recipebox/blob/main/wsgi.py) ,[See Code, requirements1.txt](https://github.com/p2slugs/recipebox/blob/main/requirements1.txt)

### Add Recipes
eva: On the add page of our website, you can input information about a recipe like its name, ingredients, and steps, and all of the information will get stored in a database (myrecipe.db). Then, that information is displayed to show the user they recipe they made by retriving the data from the database with Jinja and varibales on the html page. The views file, defines the function adding a recipe and sets the variables. The py file, addpython.py, creates the database and puts the information into it. This ticket is important for meeting the College Board requirments because it focuses on data and using it, a main focus.

[See Ticket in Scrum Board](https://github.com/p2slugs/recipebox/projects/1#card-56566247), [See Code, views.py](https://github.com/p2slugs/recipebox/blob/main/views.py), [See Code, addpython.py](https://github.com/p2slugs/recipebox/blob/main/addpython.py),[See Code, addtable.html](https://github.com/p2slugs/recipebox/blob/main/templates/addtable.html), [See Runtime Page](http://recipebox.cf/addtable)

### Sign Up Form
linda: Users are able to fill in their information for each field on the sign up form and the main data for your name, email, phone number and email would saved to a database (recipe.db). It will also redirect them to the ingredients page. Unfortunately, something with the updated html/css styling caused it to stop working. Worked on the background color, font color and format to make the page more user-friendly.

[See Ticket in Scrum Board](https://github.com/p2slugs/recipebox/projects/1#card-52933177), [See Code in views.py](https://github.com/p2slugs/recipebox/blob/main/views.py), [See Code, form.html](https://github.com/p2slugs/recipebox/blob/main/templates/form.html), [See Runtime Page](http://recipebox.cf/form)

## College Board and Crossover visibility / Suggestions
Our project aligns with the Collge Board requirements, as we have algorithmns, procedures, lists, data, functions, variables, iteration (for loop) in our project. Our project is also meeting the College Board Project Requirements by showing an impact of computing with the contact page, showing computing systems and newtworks functioning on the internet with the runtime link, showing creative development throughout our programming process together overtime, showing programming with UI to design/present to the user, and showing data, algorithms, and programming to create code as we develop our recipe database, ingredients page, and user submit form.

## Code Review Focus
See our tickets listed above with links to code. ^

## Who am I in computer science?
### Ali Saad
I have solidified my basics in python coding and am working to achieve mastery.
I have grasped the concept of HTML5 forms and pages and the front/back end data exchanging along with buidling up template pages with Jinja code.
I am just now learning about the basics of curating data and am working on improving my workflow between front end and back end code.

### Linda Long
I can develop web frontends  using HTML, CSS, and BootStrap.
I know how to use HTML forms, HTML5 validation, and build Jinja templates.
I can port forward a Raspberry Pi web server.
I need to understand Database concepts like using web sessions & establishing tables to setup and manage user accounts
I am learning how to do backend work with SQL databases, specifically SQLite and SQLalchemy utilizing the Flask framework.

### Sophie Lee
I took APCSP because I wanted to expand my horizons and learn some coding basics. I've become familiar with building Flask web servers and with Python in general. Due to my previous HTML and CSS experience, I've also improved and learned more about frontend coding as well.

### Eva Gravin
I know how to build a Python/Flask web server.
I can run a Flask server from a Raspberry Pi machine with a virtual environment, Gunicorn, and Nginx.
I can use some Linux commands in terminal.
I know how to port forward.
I am confident in using Jinja, Flask templates, app routes, and variables.
I have designed frontends with HTML, CSS, and Bootstrap.
I have a basic understanding of Python.
I have worked with REST APIS and have a basic understanding of how they work.


##
## Previous Weeks:
## Big Tickets Week of February 8 - Crossover
### Ingredients Page
Users can get indredients which they can makes recipes with. The ingredients will be shown on a different page and kept track of how many the user has. The ticket can be found [here](https://github.com/p2slugs/recipebox/projects/1#card-54620246).(eva)

[See Frontend](https://github.com/p2slugs/recipebox/blob/main/templates/ingredients1.html), [See Backend](https://github.com/p2slugs/recipebox/blob/main/ingredients.py)

### Displaying Data in HTML
Updated HTML, CSS, and overall frontend. Worked on the data and figuring out how to display it from the csv file. The ticket can be found [here](https://github.com/p2slugs/recipebox/projects/1#card-54580718).(sophie)

See github commits for track of code.

### Login Session
Users can become premium members and login to the website via the sign in page. Fill in information for each field in order to have your data stored. The preferences you put in can influence the ingredients you see later. The ticket can be found [here](https://github.com/orgs/p2slugs/projects/1#card-53870964) in the scrum board. (linda)

[See Code](https://github.com/p2slugs/recipebox/tree/main/views/pythondb), [See Form](https://github.com/p2slugs/recipebox/blob/main/templates/form.html)

### Customer Support Page
This is a new page in our website and it is where users can submit questions they have to the website. The goal is for the questions to all be recored for us to see. The ticket can be found [here](https://github.com/p2slugs/recipebox/projects/1#card-54727793).(ali)

[See Code](https://github.com/p2slugs/recipebox/blob/main/templates/customersupport.html)

## Big Tickets
### Login Session
Users can become premium members and login to the website via the sign in page. Fill in information for each field in order to have your data stored. The preferences you put in can influence the ingredients you see later. The ticket can be found [here](https://github.com/orgs/p2slugs/projects/1#card-53870964) in the scrum board.

[See Code](https://github.com/p2slugs/recipebox/tree/main/views/pythondb), [See Form](https://github.com/p2slugs/recipebox/blob/main/templates/form.html)

### Easter Egg Work
In the hidden menu of our website (the easter egg), there are College Board project considerations which includes information about how our project meets the standards in a table, a profiles page for every member of the team with their "I am" statements, and track of AP learnings with our jorunals. The layout of the easter egg was imrpoved this week and this ticket can be found [here](https://github.com/orgs/p2slugs/projects/1#card-54303099) in the scrum board.

[See Code](https://github.com/p2slugs/recipebox/commit/5a0dc45a4533a57e53dfa2c32e0499e1cf045330)

### Crud Database
Users are going to be able to create their own recipes which get added into a table. It will store their name, the recipe name, ingredients, and steps. The ticket can be found [here](https://github.com/orgs/p2slugs/projects/1#card-53870824) in the scrum board. Work is still being done on these files and curating is in the process.

See Code- [html file](https://github.com/p2slugs/recipebox/blob/main/templates/add.html), see in intellij: [view/control file](), [model definition file](), [model crud file]()

### HTML and CSS
The UI work done this week includes a dark/light mode button that changes our website's theme when clicked! Click the button in the top left corner of the website to test out this feature. Sophie did this ticket and the ticket it can be found [here](https://github.com/orgs/p2slugs/projects/1#card-53870926) in the scrum board.

[See Code](https://github.com/p2slugs/recipebox/blob/main/templates/base.html)

## Past Completed Goals 1/11-1/15
###  1. HTML, Project Overview Page 
- __description:__ Changing the look of the website included updating the color palette, the fonts, font size, and formatting of the text. The CSS was updated to make the website more interactive and user-friendly. Although there are some pages that are not up to date, the recipes page is working well with the new format.
- __link to code:__ [base.html](https://github.com/p2slugs/recipebox/blob/main/templates/base.html) and [overview.html](https://github.com/p2slugs/recipebox/blob/main/templates/overview.html)
- __instructions to evaluate:__ review [here](http://99.88.196.26/) to see updates on the filtering system and overall appearance.
### 2. Sign Up Form 
- __description:__ creating a sign up form with html/css/js using a recipes theme. Changed the background color, font color and format to make the website more user-friendly. Goal for next week is to find out how to store the data input after users sign up.
- __link to code:__ [form.html](https://github.com/p2slugs/recipebox/blob/main/templates/form.html), [base.html](https://github.com/p2slugs/recipebox/blob/main/templates/base.html) and [views.py](https://github.com/p2slugs/recipebox/blob/main/views.py); Check Github Contributions above for specific changes.
- __instructions to evaluate:__ the website can been viewed from this link http://99.88.196.26/. Click on the sign up form tab and you will see information & profile pages where you can fill out to be our subscriber. You can check the box to rate the website, and click on the yellow bar and scroll through and select your favorite snack, so that we can genenerate users' responses and recommend you personalized meals.  
### 3. Deploy with Raspberry Pi 
- __description:__ getting the website deployed this week was a big ticket which is a card in the Scrum Board called *deploy with raspberry pi*. First, Eva had to get the site running well through Intellij, as there was a problem after transfering from repl. She edited the base.html to make room for other pages' content and allow the pages to be seen when navigated from the navabar. She edited the views.py file, made a wsgi.py file, made an init.py file, and a requirements1.txt file in prep of deployment. Following Mr. Mortensen's steps for deploying, she was able to get a virtual environment finally created but ran into more problems later on. By the running the website through her raspberry pi, she got the website up for everyone to see on her personal ip address (port forwarded).
- __link to code:__ [wsgi.py](https://github.com/p2slugs/recipebox/blob/main/wsgi.py), [init.py](https://github.com/p2slugs/recipebox/blob/main/__init__.py), [views.py](https://github.com/p2slugs/recipebox/blob/main/views.py), [base.html](https://github.com/p2slugs/recipebox/blob/main/templates/base.html); Check Github Contributions above for specific changes
- __instructions to evaluate:__ the website can been viewed from this link http://99.88.196.26/ 
### 4. User Request Form Output/Storing Inputted Data 
- __description:__ after building a user input form, Ali's goal was to try and store a user's inputted name and comment on a seperate page or index by making a index template page to intake information from the input form. He was successful in getting the index page to work for the user's name, but it still working on finding a solution for the comment. This ticket is in the Scrum Board called *User Request Form Output/Storing Inputted Data*
- __link to code:__ http://99.88.196.26/ ; Check Github Contributions above for specific changes
- __instructions to evaluate:__ the website can been viewed from this link http://99.88.196.26/.  Click on the recipe request page and you will see a fill-in section. After clicking submit, a page redirect should occur where the name typed in should be stored.

## Scrum Master Grading Based on Above and Individual Support
__Individual Support__

Ali 19/20
1. tickets/cards: User Request Form Output/Storing Inputted Data; Ali would lose a point this week because the ticket didn't perfectly match up with his code. Though he was ale to store user inputted names on a seperate page through the index template, he wasn't able to store user comments on that same page, which he needs to try and fix next week. Everything else went well with Ali, regarding his code and success with the templates he worked on.
2. evidence of code: [views.py](https://github.com/p2slugs/recipebox/blob/main/views.py), [sign.html](https://github.com/p2slugs/recipebox/blob/main/templates/sign.html), [index.html](https://github.com/p2slugs/recipebox/blob/main/templates/index.html)
3. guidance for running and reviewing code: the website can been viewed from this link http://99.88.196.26/. Click on the recipe request page and you will see a fill-in section. After clicking submit, a page redirect should occur where the name typed in should be stored.

Linda 19/20
1. tickets/cards: I completed the sign up form, and helped a little on solving issues with deployment. I learned from Ms. Trish Ladd's lectures and her templates to create a sign up page with html/css/js with our project's theme. I changed the colors, fonts and text formats on the form so they matched the recipes theme. Together with Eva, we found out specific files that needed to be added and Eva did the deployment. Next week I need to find out how to store the data input after users sign up. 
2. evidence of code: [form.html](https://github.com/p2slugs/recipebox/blob/main/templates/form.html), [base.html](https://github.com/p2slugs/recipebox/blob/main/templates/base.html) and [views.py](https://github.com/p2slugs/recipebox/blob/main/views.py)
3. guidance for running and reviewing code:the website can been viewed from this link http://99.88.196.26/. Click on the sign up form tab and you will see information & profile pages where you can fill out to be our subscriber. You can check the box to rate the website, and click on the yellow bar and scroll through and select your favorite snack, so that we can genenerate users' responses and recommend you personalized meals.

Sophie 19/20
1. tickets/cards: 1) Find out how to filter recipes with tags - successful; can check progress on recipes.html or the recipes page, 2) Clean up appearance of site and make main pages look similar - definitely made the website more aesthetically pleasing on the main pages, but some other pages (such as sign up and about us) did not match the css, thus -1pt.
2. evidence of code: Check out [base.html](https://github.com/p2slugs/recipebox/blob/main/templates/base.html), [recipes.html](https://github.com/p2slugs/recipebox/blob/main/templates/recipes.html), and [overview.html](https://github.com/p2slugs/recipebox/blob/main/templates/overview.html) for my updates on the code.
3. guidance for running and reviewing code: the website can be viewed at http://99.88.196.26/. The "recipes" page should feature a filtering system where you can select what you want to see based on meal types and dietary preferences.

Eva 18/20
1. tickets/cards: I completed the the raspberry pi big ticket item, also helped with minor changes like adding in the about us pictures. I did a lot for getting the website able to run and it worked out in the end! I had to fix our Intellij problem, make an init.py, wsgi.py file, and edit the views.py file as well. I plan to get it running solely with the new way later on. As scrum master, I also spent a lot of time on the README.md to show our code for this week.
2. evidence of code: code can be seen in links above in description of big ticket #3 as well as commits in repo. also here: [wsgi.py](https://github.com/p2slugs/recipebox/blob/main/wsgi.py), [init.py](https://github.com/p2slugs/recipebox/blob/main/__init__.py), [views.py](https://github.com/p2slugs/recipebox/blob/main/views.py), [base.html](https://github.com/p2slugs/recipebox/blob/main/templates/base.html); Check Github Contributions above for specific changes 
3. guidance for running and reviewing code: to run and review code, you can view the running website at http://99.88.196.26/ and see the files in github


__Grades From Scrum Master__
| Team Member | Grade  | Reasoning |
| ----------- | ------ | --------- |
| Eva (SM)    |   18/20   |      I focused most of my attention on getting our website to run with the raspberry pi this week. I setup our project with the following files: wsgi.py, init.py, requirements1.txt, and edited files like about.py, views.py, and imported images. I would have liked to get the website running with the new way that Mr. M provided directions for, but after getting the virtual environment to work I ran into more problems. I still fufilled my task of getting it running but plan to do it the new way in the following week(s) by going to tutorial again. For this reason, I'm taking off 2 points.        |
| Ali         |   19/20   |     Ali got the recipe request form to store user's inputs and display what they entered. There is also a link that takes you back to the main page. It was much needed in our website. I agree with his score and give him 19/20.      |
| Sophie      |   20/20   |     Sophie changed the css of the website, added the recipe cards, formatted the aboutus page better, as well as the add recipes page and overview page, and definitely put in a lot of work. It was a hard task and I think her score should be 20 instead of 19.      |
| Linda       |   19/20   |     Linda created the sign up page which is really cool, along with the design! She also put in effort to help me with the raspberry pi issues. I agree with her score!      |

## Project Overview
A cooking website that has a database for recipes. We will use web scraping to find recipes. They will be organized into different categories, all using data. There will also be forms to add recipes, which we will use GET, POST, and SQLalchemy for. Our project purpose is to create a website using more advanced techniques than Trimester 1 and present it to the community at Night At The Museum, our teacher, and College Board. We will learn how to do more with data, Python, Flask, SQLalchemy, HTML, and CSS. In addition, we will deploy our website on Raspberry Pi so people from wide area network can all access. 

## Project Components
- home page
- recipes & ingredients page
- about us page
  - describes project overview in further detail (like a README)
  - introduce team members (goals, skills, etc.)
- navigation bar will be implemented
- recipe box / cooking tips / “like” a recipe feature?
- categories of food (16 types of food total)
  - breakfast
  - lunch
  - dinner
  - dessert
- Random Recipe Generator (API Webscraping)

## Delivery Plans & Milestones
- Fridays: asynchronous days / end of every school week
- Midterm: Jan 19-22
- N@tM: March 8-12
- College Board: May 13 (AP exam)

## Weekly Log
- Jan 6: tech talk about deployment and DevOps; 7 layers of the OSI model
- Jan 5: test prep on data and the Internet; took a quiz on the student lecture we had; missed one question about IP addresses/how the binary sysytem is related to it
- Jan 4: class discussion of 2 minute review for Thur/Fri, new year routine, and project reflections
- Dec 16: tech talks and scrum master presented an overview of project 
- Dec 14: reflected on project plan in class and started working on codes
- Dec 11: asynchronous day; each worked on individual assignment including ui mock-up, looking into CRUD, start of code, and gathering more data
- Dec 10: finalizing project plan desriptions and overviews; final updates to journals
- Dec 8/9: tech talks and practice exam corrections; no new updates on project plan
- Dec 7: updated repo name, moved Google Doc project plan to readme, organized responsibilities on scrum board
- Dec 4: filmed video, planned goals on scrum board, and created a table of collaborators
- Dec 3: created [project plan](https://docs.google.com/document/d/1j8Poc5Uar2J0xh_4jdK0nkSDv1neLWqGaCXjXDnQRRg/edit?usp=sharing) and wrote in new recipes for data collection, individual tasks were to find a breakfast recipe and put it on the [recipe doc](https://docs.google.com/document/d/14oFXFl3pcBhb3CPn6F3FZB0GHa1upJOBGRTt-Ql9KWw/edit?usp=sharing)
- Dec 2: created new organization and repo

## Goals
- get website deployed
- do more with data and allow multiple ingredients and steps to be added to one recipe
- solve intellij problems with running and commit more with intellij instead of repl to track progress
- work on ui/html
- solve webscrpaing/api

## Collaborators

| Team Member | Github Contributions  |
| ------------- |:---------------------:|
| Eva         | [Github](https://github.com/evagravin)|
| Ali         | [Github](https://github.com/Ali-Saad)|
| Sophie      | [Github](https://github.com/sophieleeajh)|
| Linda       | [Github](https://github.com/lindalonglong)|

## College Board / Teacher Requirements (Track to Meeting Them)

| Big Idea Number / Requirement           | Big Idea Summary  | Project Goal To Meet Each Requirement |
| -------------------------- |---------------------| ----------------------------------|
| Big Idea #1                | Creative Development: Collaboration, Design, Development, Function, Purpose, Resolving Errors | Working together as a team of 4 to come up with ideas and implement them. Collaboration between group and pair shares. Journals to keep track of progress. |
| Big Idea #2 and #3:        | Data, Algorithms and Programming: Using data, algorithms, and programming to create code. | Using SQLalchamey to create a database for our recipes and have the ability to add more recipes. Going beyond the Python fundamentals with logic and data. Using GET and POST, Python backend, and creating a data related UI. Having the ability to create, read, update, and delete recipes.|
| Big Idea #3:               | Algorithms and Programming: Using algos and programming to design and present to the user. | Creating a great UI desgin for our data filled website. Using HTML, CSS, and Javascript. Making a visual storyboard before putting it into our website. We will have options to go to different recipe pages and add in your own recipes. |
| Big Idea #4:               | Computing Systems and Networks: How computing systems and networks function on the internet.| Deploying our website on a Raspberry Pi server, using HTTP protocol for communication, using GET to request data, and POST to update the data. We will use an internet router. |
| Big Idea #5:               | Impact of Computing: The effects that computing can have and with our project. | Deploying our website onto the internet with a Raspberry Pi, sharing it to the community through Night At the Museum, and sharing it with College Board (AP Test). |
