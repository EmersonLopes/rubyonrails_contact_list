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

```