# Title: Movie Database

 ##  Description: 
 * Movie Database is a web application that allows users to search for movies, view information about each movie (including a trailer), and save movies to a personal watchlist.

## Technologies used:

* Node.js and Express.js for the server-side application logic and routing
* Handlebars.js as the templating engine to render dynamic HTML templates
* MySQL and the Sequelize ORM for the database management and interactions
* The MovieDB API, a new package, to obtain movie data and trailers
* Bootstrap CSS framework to create a polished UI that is also responsive

## Features:

* User authentication using express-session and cookies to ensure users have a personalized experience and access to their saved movies
* Home page with a search bar where users can input a movie title or keyword to search for movies
* Results page that displays movie search results with details such as title, year, poster image, and rating
* Movie detail page with detailed information on the selected movie, including the title, release date, synopsis, poster image, and trailer
* Users can save movies to a personal watchlist, and view their saved movies in a separate page
* Deployment using Heroku to make the application accessible to the public

## Folder structure:

* The application follows the MVC paradigm with separate directories for models, views, and controllers
* The models directory contains files for the Sequelize models to interact with the database
* The views directory contains Handlebars.js templates to render the UI
* The controllers directory contains Express.js routes and middleware to handle incoming requests and responses