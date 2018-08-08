# Features

All users can:

* View list of articles, list of tags
* View articles by tags
* View individual article and post comments

Only logged-in users can:

* Create, edit, delete articles
* View, edit, create and delete authors
* Author account creation:

If there are zero authors in the system, anyone can access the form in new_author_path (/authors/new) to create the first author account
Subsequently, new author accounts are created by users with existing account. Access to new_author_path (/authors/new) form will be blocked unless user is logged in.

## Components

Built on Ruby v2.3.0, Rails v5.0.7
Paperclip gem for image file attachment (Paperclip is dependent on ImageMagick program)
Sorcery gem for authentication
Uses PostgreSQL database in production

### Concepts

This application demonstrates the following concepts using Ruby on Rails

Designing an MVC (Model, View, and Controller) web application architecture
RESTful design principles
Relational Data Modeling and Relationships
Data Schema Migrations
HTTP Request Handling and Routing
Web Views with HTML forms, partials, and view helpers
Using Rails generators (e.g. scaffold, scaffold_controller)
Using Ruby gems for additional functionality

#### Live Version

[Demo](https://bloggerforum.herokuapp.com)
