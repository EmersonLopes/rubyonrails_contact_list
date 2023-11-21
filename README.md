# README

This README would normally document whatever steps are necessary to get the
application up and running.

Things you may want to cover:

* Ruby version

* System dependencies

* Configuration

* Database creation

* Database initialization

* How to run the test suite

* Services (job queues, cache servers, search engines, etc.)

* Deployment instructions

* ...

## Comands

These are the commands used in this project

```bash
# Create a mvc of the entity Contact with the properties name and phoe
rails generate scaffold Contact name:string phone:string

# Create a model of the entity User with the properties emails, name and password_digest
rails generate model User email:string name:string password_digest:string

# Run project
rails server
# or
rails s

# Create databases specified in the file /config/database.yml
rails db:create

# Migrate databases with files specified in folder /db/migrate
rails db:migrate

# List routes used in this project
rails routes

# Create a new user using the rails console
rails console
user = User.new
user.name = "Joao"
user.email = "joao@gamail.com"
user.save

```