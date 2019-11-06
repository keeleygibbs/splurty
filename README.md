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

#Create quote
Quote.create(saying: 'Example 1.', author: 'Mark Cuban')

#Updating a quote
Quote.find(id).update_attributes(saying: ‘your text here’, author: ‘your text here’)
