# README

This project is builded with Ruby on Rails.

It uses for authentication devise gem.
THis gem handle the  sign in, sign up and email validation

The database for production is postgres. For development is Sqlite

The routes for the users CRUD are:

| Verb   | Resource         | Description   |
|--------|------------------|---------------|
| GET    | /users           | Get all users |
| GET    | /users/new       | Form for new user |
| POST   | /users           | create a user |
| GET    | /users/{id}      | Get the detailed info for a user |
| GET    | /users/{id}/edit | Get the edit form  |
| PUT    | /users/{id}      | Update the user  |
| DELETE | /users/{id}      | delete the user    |