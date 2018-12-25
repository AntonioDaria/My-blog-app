
# BumbleBells feedback blog

This application has been created for BumbleBells child care to enable the users to have access to a user friendly platform, where they can leave feedback and comments in regards to the service received.
From the business point of view this blog app it is used to make improvements and act upon feedback received.

Ruby version
 - ruby '2.5.1'

Database
 - postgresql for production
 - sqlite 3 for test environment

```
Features:
 - Users can sign up
 - Users can be given admin access to delete posts, categories and users
 - Users can log in
 - Users can also log out
 - Users can post feedback
 - Users can post feedback based on categories
 - Users can view feedback based on categories
 ```

Installation Instructions:
  - Clone The Repo
  - Install Rails,
  - Run Bundle Install for all your Gem needs
  - Run DB:Create
  - Run DB:Migrate

How to Run Locally:
  - Navigate to project directory
  - Run Bin/Rails Server
  - Available on http://localhost:3000/


Instructions for Testing:
  - Unit test and integration test created with Rails
  - To run execute the following command: Rails test

Instructions for Contributions:
  - Repeat all installation instructions.
  - Think of some new Features
  - Implement them.
  - Use TDD at all times.

Deployed on:
   https://bumble-bells-blog.herokuapp.com/


Technologies Used in The Production of Csv Uploader;
  - Rails with Active Record
  - Heroku
  - Rubocop
  - Bootstrap
  - Jquery-rails
