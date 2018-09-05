# Friend Finder (express app)

The function of this app is to connect the user with the most compatible friend in the database.

## Files

* server.js (initiates server connection)

* friends.js (stores data of people to compare against user)

* home.html (homepage)

* survey.html (Profile creation page)

* apiroutes.js (works with data from friends.js and survey.html to compare and obtain most compatible friend information)

* htmlroutes.js (creates routes for html pages)

## Dependencies

* Packages

    * express 

    * body-parser

* Libraries

    * Bootstrap (https://getbootstrap.com/)

    * Font Awesome (https://fontawesome.com/v4.7.0/icons/)

    * Sweet Alerts (https://sweetalert.js.org/)

## Step By Step 

1. Start on home page (home.html "/")

1. Prompts user to click button to create profile

1. Takes user to Profile creation page (survey.html "/survey")

1. User fills in fields

    1. If a field is left empty, user will be prompted to fill in empty field.

    1. If all fields are filled out, user will be alerted that they have a compatible match and the information will be displayed!
