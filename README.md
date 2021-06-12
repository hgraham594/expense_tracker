# expense_tracker

This project is being completed as RSpec learning/practice, and is following the tutorial from the book "Effective Testing with RSpec 3", by Marston & Dees.

As described in the book, the project is for a web service for tracking expenses. Customers would use some kind of client software (CLI, GIU, or even a web app) on top of this web service to track and report daily expenses.

The major parts of the app are:
* A web application written in Sinatra that will receive incoming HTTP requests (to add new expenses or search for existing ones)
* A database layer using Sequel to store expenses between requests
* A set of Ruby objects to represent expenses and glue the other pieces together

