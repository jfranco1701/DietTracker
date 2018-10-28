# User Stories

#### As a general user, I want to create an account, so I can begin tracking my diet.
* I can enter my email address, name and password from the create user page.
* I can click the “Sign-up” button and the system will create a new account providing the email address has not been previously used.

#### As a general user, I want to login to the site, so I can track and view the progress of my diet. 
* When not logged on to the system, I can enter my email address and password on the login page.  
* I can click the “Login” button and if the proper credentials have been entered, the system will log me in.

#### As a general user, I want to be able to display a graph of my progress, so I can view the progress of my diet.
* When logged in to the system, I can view a graph of my progress from the site's home page.

#### As a general user, I want to search for food items I have consumed and add them to a meal, so I can track my daily intake.
* I can enter my search criteria for the food or beverage item.
* I can click the "Search" button to search user created meal items and the USDA Food Composition Database using their REST API.
* I can view the results that meet my search criteria.
* I can select an item from the list.
* I can save the food item, quantity and meal type in the system.

#### As a general user, I want to be able to create custom food items that can be saved in the system, so I can track items that are not found in a search. 
* I can click the "Create" button and enter the information about the food item.
* I can click the "Save" button to store the item in the system.

#### As a general user, I want to create a list of favorite food items, so I can easily add items that I eat regularly.
* I can click on the "Add to Favorites" link to store the item in the My Favorites list.
* I can click on the "Remove" link from the My Favorite Items page to remove the item.

#### As a general user, I want to add my current weight, so I can track my weight loss.
* I can click on the "Add Weight" button and enter the date and weight information.
* I can click on the "Save" button to store the information in the system.

#### As an admin user, I want to be able to review custom food items added by users, so I can prevent inappropriate entries.
* I can view a list of all the custom food items.
* I can select an item and click on the "Delete" button which will remove it from the system.

# Mis-user Stories

#### As a malicious user, I want to login as a registered user using a brute-force attack, so I can steal personal health information.

#### As a malicious user, I want to script the creation of multiple users, so I can perform a denial of service attack.

#### As a malicious user, I want to create custom food items that contain malicious scripts, so I can carry out cross-site scripting attacks.

# Website Mockup

#### Default Page
<img src="https://github.com/jfranco1701/DietTracker/blob/master/docs/Default.jpg" width="50%">

#### Create User Page
<img src="https://github.com/jfranco1701/DietTracker/blob/master/docs/New User.jpg" width="50%">

#### Login Page
<img src="https://github.com/jfranco1701/DietTracker/blob/master/docs/Log In.jpg" width="50%">

#### Home Page
<img src="https://github.com/jfranco1701/DietTracker/blob/master/docs/Home.jpg" width="50%">

#### Add Meal Item Page
<img src="https://github.com/jfranco1701/DietTracker/blob/master/docs/Add Meal Item.jpg" width="50%">

#### Search Item Page
<img src="https://github.com/jfranco1701/DietTracker/blob/master/docs/Search Item.jpg" width="50%">

#### Create Item Page
<img src="https://github.com/jfranco1701/DietTracker/blob/master/docs/Create Item.jpg" width="50%">

#### My Favorites Page
<img src="https://github.com/jfranco1701/DietTracker/blob/master/docs/My Favorites.jpg" width="50%">

#### Add Weight Page
<img src="https://github.com/jfranco1701/DietTracker/blob/master/docs/Add Weight.jpg" width="50%">

#### User Item Review Page
<img src="https://github.com/jfranco1701/DietTracker/blob/master/docs/Item Review.jpg" width="50%">

# Architecture Diagrams

### System Context Diagram
<img src="https://github.com/jfranco1701/DietTracker/blob/master/docs/System Context Diagram.jpg" width="75%">

### API Component Diagram
<img src="https://github.com/jfranco1701/DietTracker/blob/master/docs/API Component Diagram.png" width="85%">

