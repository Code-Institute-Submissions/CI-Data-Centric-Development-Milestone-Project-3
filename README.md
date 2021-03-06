# Data-Centric-Development-Milestone-Project-3

<h1 align="center">
  <a href="https://galway-charity-projects.herokuapp.com/" target="_blank"><img src="https://res.cloudinary.com/daqyuuzq9/image/upload/v1603642648/Galway_Charity_Projects_youzgg.png" alt="Galway Charity Projects"/></a>
</h1>

<h2 align="center">
Galway Charity Prjects(GCP) - A home for Galway's volunteering community to come together to support local charities. 
</h2>
<div > 
Before Covid-19 people, interested in volunteering, would often look beyond their own county and even country for volunteering oppotunities.  The recent times have taught us all how powerful the impact can be when we support local. 
Today, some charities are struggling because they cannot get access to volunteers to support their projects and some volunteers are lost as they don't know what projects they can support in their area. 
[Galway Charity Projects](https://galway-charity-projects.herokuapp.com/) is a place to encourage local volunteers and charities to engage more and work together to strengthen our community
<br>
<br>
Features of the site include easy to view project list and detail page and simple registration process for charities which I hope will allow users to achieve the following: 

* Allow *charities* to register their project
* Enable *volunteers* to search live projects in their area and get in touch with the charity to find out more. 
* *Project Detail Page - Select a project,* they should see the instructions, any downloadable files, and a contact for the charity.
<br>
In Phase one we are focusing on the city of Galway with the intention to build on this for all the cities and towns in Ireland to encourage people to learn more about the volunteering opportunities close to home. 
<br>

[Click here to view the page now!](https://galway-charity-projects.herokuapp.com/)

</div>

## Table of Contents
1. [**UX**](#ux)
    - [**Project Goals**](#project-goals)
    - [**Charity goals**](#charity-goals)
    - [**Volunteer goals**](#volunteer-goals)
    - [**Developer and Business Goals**](#developer-and-Business-Goals)
    - [**User Stories**](#user-stories)
    - [**Design choices**](#design-choices)
    - [**Wireframes**](#wireframes)
    - [**Database**](#database)

2. [**Features**](#features)
    - [**Existing Features**](#existing-features)
    - [**Features Left to Implement**](#features-left-to-implement)

3. [**Technologies used**](#technologies-used)

4. [**Testing**](#testing)

5. [**Deployment**](#deployment)
    - [**How to run this project locally**](#how-to-run-this-project-locally)

6. [**Credits**](#credits)
    - [**Content**](#content)
    - [**Media**](#media)
    - [**Code**](#code)
    - [**Acknowledgements**](#acknowledgements)

7. [**Disclaimer**](#disclaimer)

## UX

### Project Goals

The primary goal of Galway Charity Projects (GCP) is to provide a clean, intuitive and engaging site to help people find out more about the ongoing charity projects close to them. 

GCP has two target audiences: Local charities and the local community/volunteers looking to support. 

### Charity Goals

Local charities want and need project support: 
- They want to get their message out there about the projects they have live and need support on. 
- They want to make sure the community is aware of they different initiatives
- They want an easy way to register their projects online

GCP can help local charities owners because:
- It provides a platform for local charities to share their projects. 
- It ensures their listing is live and active on the site.
- Charities can easily submit their projects for the site using a simple form
- GCP also offers them the feature to update their projects when details change or remove them one complete. 
- Charities can also indicate projects that need urgent support



### Volunteer goals

People want to make the extra effort to support local where they can and give back to the community and volunteering is a great way to do this but 
sometimes they might not always be aware of the different opportunities and projects in their area. 

Volunteers and members of the local community can:
- Learn about new charity projects in Galway
- Find out more information on different projects via a detail page
- Discover which projects might need urgent support
- Have a one stop location where they can find out all about the local charity 

GCP can help meet the needs of the community because: 
- It can offer a list view of all live projects. 
- Provide a search feature on the projects page to filter to the volunteers interest. 
- It displays in an engaging and simple way.
- It has been designed with user experience as a priority to easily guide them through the site 

### Developer and Business Goals

- A well designed directory of charity projects that strives to have a positive imact on the community. 
- Good and clean programming that is robust and scaleable with the increase of cities and charities joining. 
- A professional looking first attempt of using python, flask, materialize which the developer is excited to make a part of her portfolio and continue to develop in the future

### User Stories

As a charity owner, I want:
1. To register my charity
2. Create new charity project listing and share details. 
3. Edit, update and delete a project when necessary. 

As a volunteer and member of the community, I want:
1. Discover more about the volunteering opportunities in my area based on my catagories of interest
2. A visually and operationally appealing site that makes if simple to learn more about local charitiy projects. 
3. Easily view the details of a specific project.

As an admin user, I want:
1. To view all projects
2. Create, edit, update and dleete project categories when needed



### Design Choices

The overall feel of the site is one that is visually appealing and simple to follow. The following design choices were made with this in mind:

**Fonts**

- The primary font **Roboto** was chosen because it is a crisp, sharp and easy to read font. It was inspired by the logo created on Canva.com. 

**Colours**

- The primary colour choices for this site is purple and blue.  This has been inspired by the county colours of Galway and also the blue as an uplifting balance. 
A basic pallet was chosen to ensure the infomration on the page was the main focus.

**Styling**

- On the listing page cards have a minimalist design and rounded edges and a drop shadow to highlight these areas on the page more.  
- Design and styting consistency was important on this site to help linking and combining the related areas together. 



**Home Tile Images**

- At present these have been kept simple and will be considered again int the future. 



**Header and home Banner images**

- A strong header was chosen to make the logo and heading memorable 
- The homepage image was chosen for its friendliness and warmness of complimentry colour palette. 



### Wireframes

During the early part of the project wireframes were created using pen and paper and on [Pages](https://www.apple.com/pages/). 

- [Link](https://drive.google.com/drive/folders/14ucGfk0wU4zXHGPPJoB9GMs4_lIcOa28?usp=sharing)


### Database
Database

This website has a MongoDB database called: galway_charity_projects_manager
The database consists of 3 collections(tables)
- Users
- Projects
- Project Categories
<div align="center">
<img src="https://res.cloudinary.com/daqyuuzq9/image/upload/v1603730576/Screenshot_2020-10-26_at_16.41.55_hnoews.png" alt="Screenshot: Homepage" >
</div>
*This database was a good fit for the complexity level of this project - in the future I would review the options available*



## Features
 
### Existing Features

#### *Visible to all users*
<div align="center">
<img src="https://res.cloudinary.com/daqyuuzq9/image/upload/v1603733800/screencapture-8080-c73c8b14-6269-4ff6-b900-aebfb54111b9-ws-eu01-gitpod-io-index-2020-10-26-17_36_20_ccay9g.png" alt="Volunteer View"><br>
</div>

1. **Home - Site Overview**
    - On arriving at the homepage page the user is presented static content to share a brief overview of the site and two key option cards - 
        - LEFT: They can select the Volunteer card - View Projects Action
        - RIGHT: They can select the Volunteer card Charity - 
            - If user is logged in - Create Project Action
            - If user is not logged in - Log in to get started Action
    - They can select Galway and be directed to the Galway Catagory Page



2. **All Projects**
    - Charity projects list page contain a card list of all the available projects and a call to action on the card to "Find out more"


3. **Project Detail**
    - On selection of a charity project the user is directed to a project detail page. 

4. **Login / Register your Charity**
    - The option to Login or Register your charity is visible to all users from the accourn tab in the navigation bar. However, only those registered can use the login feature. 
<div align="center">
<img src="https://res.cloudinary.com/daqyuuzq9/image/upload/v1603734391/Screenshot_2020-10-26_at_17.46.23_qoylgn.png" alt="Screenshot: Login Register Nav Bar"><br>
</div>

5. **Error handling pages**
    - Error page templates have been created for errors 403, 404 and 500
    - A funtion called is_valid_id has been set up to ensure pages which contain a project or category id are mroe robust to code injection. 


#### *Visible to registered users*

<div align="center">
<img src="https://res.cloudinary.com/daqyuuzq9/image/upload/v1603733988/Screenshot_2020-10-26_at_17.39.37_piuotf.png" alt="Screenshot: Galway logged in user Nav Page"><br>
</div>

1. **Create/Edit/Update/Delete Project**
    - Registered users can create a new project and if needed later they have the ability to edit,update and delete the project
    - When a user choosed to delete a project a modal will pop up first to promp the user to confirm they do want to delete the project. 

2. **Logout**

    - Both logged in Users and Admin can log out by clicking the Log Out menu item from the navigation bar. 
    - They will be redirected to the homepage


#### *Visible to admin*

<div align="center">
<img src="https://res.cloudinary.com/daqyuuzq9/image/upload/v1603733923/Screenshot_2020-10-26_at_17.38.16_girpuo.png" alt="Screenshot: Galway Catagory Page"><br>
</div>


1. **Project Categories**
    - Full CRUD funtionality for categories
        - Create Category
        - Read Category
        - Edit Category
        - Delete Category
    - When the *admin* chooses to delete a project a modal will pop up first to promp the user to confirm they do want to delete the project. 


    - To view please use the following login details: 
        - *Username*: admin
        - *Password*:123123123



### Features Left to Implement

Future features may include but not limted to: 
1. **Profile** - 
    In the future I would like to build out the Charity Profile page
    - At present it exists in the project but I have removed it from the navigation as I ran out of time to update it correctly 
    - Password update feature
2. **Project Detail Page** - Create project sign up to sync with Charities DB
3. **Project List Page** - Pagination
4. **Admin User** - at present admin is identified with just username == admin I would like the ability to have multiple admins

<br>

## Technologies Used


### Coding Languages
- This project uses the following languages:
    - [Python](https://www.python.org) - Flask,flask_pymongo, bson.objectid, werkzeug.security
    - [BSON](https://www.mongodb.com/json-and-bson)
    - [JQuery](https://jquery.com) - The project uses **JQuery** to simplify DOM manipulation.
    - [HTML5](https://www.w3schools.com/html/) - Semantic markup language.
    - [CSS3](https://www.w3schools.com/css/)-  Cascading Style Sheets to enhance the design of the site and support where materialize was limeted

- This project uses the following apps:

    - [GitPod](https://www.gitpod.io/) - **GitPod** was used as the main IDE while building the website.
    - [MongoDB](https://www.mongodb.com/) - Database
    - [Heroku](https://www.heroku.com) - Deployment
    - [GitHub](https://github.com/) - This project uses **GitHub** to store code and manage version control.
    - [Cloudinary](https://cloudinary.com/) - This project uses **Cloudinary** to store images. 

- UI/UX This project uses the following Frameworks and sites to support the Design:

    - [Materialize](https://materializecss.com/) - The project uses **Materialize** as design framework to simplify the structure of the website and make the website responsive easily.
    - [Google Fonts](https://fonts.google.com/) - The project uses **Google fonts** to style the website fonts.
    - [Font Awesome](https://fontawesome.com/changelog/latest) - Icons are primarily sourced from Font Awesome
    - [Canva](https://www.canva.com/) - This project used tools in **Canva** to edit, crop and save images. **Canva** was also used to source all imagery and design of banner, logo and tile elements. 
    - [Colour picker](https://chrome.google.com/webstore/detail/eye-dropper/hmdcmlfkchdmnmnmheododdhjedfccka?hl=en) was also used to ensure color consistency over the entire project. 

<br>

## Testing 


### **Feature Testing**


#### Volunteer User Story - Non Session User

Possible Actions
- View Home Page
- View list of live projects
- View Project Detail Page for more information on a project with contact info for charity

##### *View Home Page*
- Launch Site via URL - https://galway-charity-projects.herokuapp.com/
- **Expected Result:** Directed to site homepage

##### *View Projects*
- Launch Site via URL - https://galway-charity-projects.herokuapp.com/
- Try to find the project list
    - **Option 1** - Click the *View Projects* link from the navigation menu
        <div align="center">
        <img src="https://res.cloudinary.com/daqyuuzq9/image/upload/v1603741629/Screenshot_2020-10-26_at_19.46.50_yurvxn.png" alt="Screenshot: navigation"><br>
        </div>
    - **Option 2** - On the home page click the *View Projects* link from the Volunteers card 
        <div align="center">
        <img src="https://res.cloudinary.com/daqyuuzq9/image/upload/v1603741635/Screenshot_2020-10-26_at_19.46.56_a1wmwl.png" alt="Screenshot: home card"><br>
        </div>
- **Expected Result:** Directed to project list view page

##### *View Project Details*
- When on the project list page click the "Find out more" button on the 
    <div align="center">
    <img src="https://res.cloudinary.com/daqyuuzq9/image/upload/v1603741746/Screenshot_2020-10-26_at_19.48.56_lg4rxn.png" alt="Screenshot: home card"><br>
    </div>
- **Expected Result:** Directed to Project Detail Page

<br>

#### Charity User Story - Session User

Possible Actions
- View Home Page (as Volunteer User Story)
- View list of live projects (as Volunteer User Story)
- View Project Detail Page for more information on a project with contact info for charity (as Volunteer User Story)
- Register Charity
- Login
- Logout
- Create a Project
- Edit/Update own Project
- Delete Project

##### *Find Register Charity Page*
- Launch Site via URL - https://galway-charity-projects.herokuapp.com/ --> Arrive on homepage
- From the navigation menu click *Account* --> then click "Register Your Charity"
- **Expected Result:** Directed to Charity Registration Page
##### *Register Charity*
- While on the Registrstion page fill out details on the form - All fields are required and form validation built in - user will be prompted to fill in all fields
- Click *Register* button
- **Expected Result:** 
    - Directed to homepage
    - Success flash message to appear confirming successful registration - "*Project Successfully Added*"
- **Defensive Design:** 
    - Enter a dupicate username --> warning flash message returned

##### *Login*
Launch Site via URL - https://galway-charity-projects.herokuapp.com/
- Try to find the Login page
    - **Option 1** - From the navigation menu click *Account* --> then click *Login* 
        <div align="center">
        <img src="https://res.cloudinary.com/daqyuuzq9/image/upload/v1603734391/Screenshot_2020-10-26_at_17.46.23_qoylgn.png" alt="Screenshot: navigation"><br>
        </div>
    - **Option 2** - On the home page click the *Login to create your project* button from the Charity card 
        <div align="center">
        <img src="https://res.cloudinary.com/daqyuuzq9/image/upload/v1603743074/Screenshot_2020-10-26_at_20.10.29_l1pxr9.png" alt="Screenshot: home card"><br>
        </div>
- **Expected Result:** 
    - Directed to Login Page

- Fill in username and password 
- **Expected Result:** 
    - Directed to Home page
    - Success flash message to appear with welcome message to user - "*Welcome 'username'*"
- **Defensive Design:** 
    - Enter a wrong username --> warning flash message returned - "*Incorrect Username and/or Password*"
    - Enter a wrong password --> warning flash message returned - "*Incorrect Username and/or Password*"


##### *Logout*
- From the navigation menu click *Account* --> then click *Logout* 
- **Expected Result:** 
    - Directed to Homepage
    - Success flash message confirming you have logged out --> "*You have been successfully logged out*"

##### *Projects (CRUD)*
##### *Projects Create*
- From the navigation menu click *Create Projects*
- Fill out form all fields required except for *Project Image URL* and *This Project Requires Urgent Support*
- Click the "*Submit Project*" button

- **Expected Result:** 
    - Directed to Project List page and will see new project live on the page
    - Success flash message to appear --> "*Project Successfully Added*"
- **Defensive Design:** 
    - User will be prompted to fill out required fields and won't be able to submit untill populated
    - If the *Project Image URL* isn't populated, [jQuery function](https://stackoverflow.com/questions/54674829/render-default-image-in-flask) will be called to populate with default image

##### *Projects Read*
- As Volunteer User Story

##### *Projects Edit/Update*
- Registered user will have the abilty to edit a project
- Navigate to the project detail page
    - From the navigation menu select *View Projects* then select the project to edit 
    - From the project detail page select the edit button on the card
- **Expected Result:** 
    - Directed to Edit Project page
    <div align="center">
    <img src="https://res.cloudinary.com/daqyuuzq9/image/upload/v1603744208/Screenshot_2020-10-26_at_20.27.29_xbrh8j.png" alt="Screenshot: detail card"><br>
    </div>
 
- User can edit details and click the *Update* button
    - **Expected Result:** 
        - Directed to Project List page
        - Success Flash message --> "*Project Successfully Updated*"
- User can cancel changes and click the *cancel* button
    - **Expected Result:** 
        - Directed back to the project detail page to review

- **Defensive Design:** 
    - To project the integrity of all projects a registered user is only able to edit a project they created


##### *Projects Delete*
User can delete a project by clicking the *Complete* button
- **Expected Result:** 
    - Pop-up mondal to ask user to confirm deletion
    - Project deleted from list
    - User directed back to project list page
    - Success Flash message --> "*Project Complete*"

- **Defensive Design:** 
    - To project the integrity of all projects a registered user is only able to delete a project they created
<br>

#### Admin User Story

Possible Actions: 
- Access to all registered user features
- Added feature of project category management 


##### *Login*
- To test admin feature please use the following login details: 
    - *Username*: admin
    - *Password*:123123123

##### *Category (CRUD)*
##### *View Categories*

- Log in with username == admin
- Select *Project Categories* from the navigation menu
    <div align="center">
    <img src="https://res.cloudinary.com/daqyuuzq9/image/upload/v1603733923/Screenshot_2020-10-26_at_17.38.16_girpuo.png" alt="Screenshot: detail card"><br>
    </div>
- **Expected Result:** 
    - Directed to Project Category list page 
    <div align="center">
    <img src="https://res.cloudinary.com/daqyuuzq9/image/upload/v1603745740/Screenshot_2020-10-26_at_20.47.14_auo4xc.png" alt="Screenshot: detail card"><br>
    </div>

**Defensive Design:** 
- Only admin can view the categories to protect 
 

##### Project-Category Create
- On project category list page click "*Add Project Category*" button
- Directed to Add Category page
- Enter new category name and click the "*Add Project Category*" button
<div align="center">
    <img src="https://res.cloudinary.com/daqyuuzq9/image/upload/v1603746049/Screenshot_2020-10-26_at_21.00.38_ykrekx.png" alt="Screenshot: detail card"><br>
    </div>

- **Expected Result:** 
    - Directed to Project Category list page 
    - Success Flash message --> "*New Category Successfully Added*"
    - New category card appears on list page


##### *Project-Category Edit/Update*
- On project category list page click "*Edit*" button on the category card you'd like to edit
- **Expected Result:** - Directed to Edit Category page
- Make edit to category or cancel changes
- **Expected Result:**
    - Directed back to list page
    - If changes made flash message --> "*Category Successfully Updated*"

##### *Project-Category Delete*
- On project category list page click "*Delete*" button on the category card you'd like to remove
- **Expected Result:** 
    - Pop-up mondal to ask user to confirm deletion
    - Category deleted from list
    - User directed back to project category list page
    - Success Flash message --> "*Category Successfully Deleted*"



### Defensive Design Testing

- As detailed above all features have been designed with the consideration to the session user to manage the user actions and visibility
- Navigation menu items have been restricted based on session user

#### **Error pages**
Error messages have been implemented for errors - 403, 404, 500
Testing: 
- The 404 error page was tested manually by entering in incorrect URL pat
- The links on the 404 page were tested by clicking and checking they redirected correctly. 



### **Code Validators**

To ensure all code was clean, bug free and most importantly for python PEP8 compliant the following validators were used on the site: 

- [W3C HTML validator](https://validator.w3.org/) to validate CSS code
- [W3C CSS Validator](https://jigsaw.w3.org/css-validator/) to validate CSS code
- [JSHint](https://jshint.com) to validate jQuery Code
- [PEP8 Validator](http://pep8online.com/) to validate Python code

### **Site UI/UX & Browser Compatibility Testing**

- Manual testing was carried out on this site by the developers family members to review the UX and site responsivness
- Chrome dev tools were used to review responsivness on multiple device sizes
- Cross browswer testing was also attempted on chrome and safari


## Deployment

### Requirements for Deployment
- Gitpod of IDE of choice
- Python3 to run your application
- PIP to install all app requirements
- Database --> MongoDB Atlas account for database development
- Heroku account

### Source Code

This project was developed using the [GitHub IDE- GitPod](https://www.gitpod.io/) , committed to git and pushed to GitHub via the terminal in GitPod

The code for *Galway Charity Projects* is stored on this [GitHub repository](https://github.com/lhynes/CI-Data-Centric-Development-Milestone-Project-3), the following steps were taken: 
1. Log into GitHub. 
2. Navigate to the site [repository](CI-Data-Centric-Development-Milestone-Project-3) 
3. From here you can clone the repo. 
To clone this project from GitHub:
 - Follow this link to the [GitHub repository](https://github.com/lhynes/CI-Data-Centric-Development-Milestone-Project-3).
 - Under the repository name, click "Clone or download".
 - In the Clone with HTTPs section, copy the clone URL for the repository. 
 - In your local IDE open Git Bash.
 - Change the current working directory to the location where you want the cloned directory to be made.
 - Type ```git clone```, and then paste the URL you copied in Step 3.
```console
git clone https://github.com/USERNAME/REPOSITORY
```
 - Press Enter. Your local clone will be created.


The Master Branch is up to date containing the most recent version of the project. 

### Heroku Deployment

This project has been bepoyed to Heroku. 
Automated pushes were enabled from my [GitHub repository](https://github.com/lhynes/CI-Data-Centric-Development-Milestone-Project-3) to Heroku. 
The following steps were following for setting up deployment on Heroku: 
1. Create requirements.txt file:  In GitPod IDE enter ```pip freeze > requirements.txt``` to the teminal 
2. Create a Procfile: ```echo web: python app.py > Procfile```
3. User git add, commit and push to ensure requirements.txt and Procfile are in the [GitHub repository](https://github.com/lhynes/CI-Data-Centric-Development-Milestone-Project-3)
4. Create new app in Heroku : galway-charity-projects (Region Europe)
<div align="center">
    <img src="https://res.cloudinary.com/daqyuuzq9/image/upload/v1603748143/Screenshot_2020-10-26_at_21.35.15_hyx6dg.png" alt="Screenshot: Heroku New App"><br>
    </div>

5. Heroku Deployment method -->  GitHub - confirm linked to project repo
<div align="center"></div>
    <img src="https://res.cloudinary.com/daqyuuzq9/image/upload/v1603748304/Screenshot_2020-10-26_at_21.37.44_ollrlm.png"><br>
    </div>

6. Set up config vars - Settings --> 
<div align="center"></div>
    <img src="https://res.cloudinary.com/daqyuuzq9/image/upload/v1603748411/Screenshot_2020-10-26_at_21.37.44_huazpb.png"><br>
    </div>

7. Once set up return to Deploy tab and select --> Deploy Branch
<div align="center"></div>
    <img src="https://res.cloudinary.com/daqyuuzq9/image/upload/v1603748537/Screenshot_2020-10-26_at_21.41.15_n5fk9b.png"><br>
    </div>

8. Once complete app was live  - [Click here!](https://galway-charity-projects.herokuapp.com/)

*Sample ENVpy file*
<br>
```import os```

```os.environ.setdefault("IP", "0.0.0.0")```
```os.environ.setdefault("PORT", "5000")```
```os.environ.setdefault("SECRET_KEY", "!LL%Ha&</M|IZsa|<>}V<4hH^/;V>L")```
```os.environ.setdefault("MONGO_URI", "mongodb+srv://Loop2020:ThisWi11b3Fun2020@myfirstcluster.rjtfq.mongodb.net/galway_charity_projects_manager?retryWrites=true&w=majority")```
```os.environ.setdefault("MONGO_DBNAME", "galway_charity_projects_manager")```




## Credits

### Content

- The concept, design and text for this project was created by the developer. 

### Media

#### Images
- The Galway Charity Projects logo was created using [Canva](https://www.canva.com/).
- All imagery for the site was sourced from [Canva](https://www.canva.com/).


### Code
- Code was primarily inspired by the Task Manager mini project tutorials. 

### Acknowledgements

I would like to extend a special thanks to my Code Institute Mentor Anthony Ngene for kind support and time throughout this project.
Thank you also to the tutors for their support and the wider slack community - I've learned so much during this project and can't wait to revisit it again in the near future. 


#### Disclaimer
The content of this website, including the images used, are for educational purposes only.