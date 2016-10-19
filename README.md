#Project 2 - <i>Advice.com</i>

## Overview

####Live Site: [Heroku](https://infinite-hamlet-65363.herokuapp.com/)

This project is a Ruby on Rails stack app that was largely inspried by learning how to create a simple "TODO" app.

The inspiration behind 'Advice.com' was from a website I found with a similar purpose to what I was wanting to achieve for this project. Guests would be able to read insightful and helpful advice on a variety of topics. Users who signed up and logged in would be able to create their own posts/articles seeking advice and would also be able to create comments on other users posts/articles.

## Technologies Used

* HTML & CSS
* Ruby 2.3.1
* PostgreSQL
* Rails 5
* Active Record (for Object Relational Mapping)
* ERB (Embedded Ruby for HTML)
* Heroku (for App Deployment/Hosting)
* Text Editor - Atom
* Project Planning & User Stories - Trello
* Wireframe Design - Mockingbird

## Features

* Guests are able to read existing posts on the website.
* Users who signup/login are able to create, read, update, and delete their own posts/articles and comments.

## Wireframe

Link to my <b>[Mockingbird](https://gomockingbird.com/projects/t98pjdt)</b> Wireframe.

## Project Planning & User Stories

Link to my <b>[Trello](https://trello.com/b/sEOyWa9d/ga-wdi7-project-4)</b> Board.

## Unsolved Problems/Major Hurdles

#### Unsolved Problems

* Issues with fully implementing a CSS framework
* Issues with implementing Devise security framework

#### Major Hurdles

* Was able to create basic authentication in Rails
* Was able to correctly have 'Comments' model associated with 'Articles' model
* Was able to solve spacing issue on "Articles/Index" route with 'Title' and 'Text' of existing articles/posts
* Was able to utilize background image and have it fit the page correctly

## Future Development

* Utilize either Bootstrap or Foundation CSS framework for better styling/responsiveness
* Utilize Devise security framework for greater flexibilty and more features
* Better use of the 'Home/Index' page
* Create various topics and create dedicated pages for each topic
* Create NavBar and Footer
* Create an 'About' page
* Create an 'Admin' that could CRUD all users articles and comments for moderation purposes
* Create a 'Chat' app so users can chat in real time about a particular topic
