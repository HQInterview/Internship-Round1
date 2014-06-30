# PHP / SQL Internship #1

This document contains description and requirements for Round #1 of interview for internship developer position. Applicant can chose to use PHP or Node.js.

## Goal

Verify applicant's ability to work with a PHP or Nodejs framework, APIs, AJAX and CSS framework. Verify that applicant is able to write clean code.

## Requirements

Implement a simple website with 

* a list of products
* and a form to add a new product to database

### Business requirement

Each product has the following attributes: Name, Description, Price (amount + currency), URL to product image.

Business person needs to be able to add a new product and see a list of all products already added in a database.

### List of products

In the list needs to be the following attributes:

* ID (autoincrement ID from database)
* Name
* Description
* URL to product image
* Price (amount with currency)
* Price converted to USD - automatically convert price to USD

### Adding a new product

Create a form that handles adding a new products to database.

In the form, user can choose price with one of the following currencies: USD, EUR, THB, HKD, SGD, AUD.

* Form needs to be secured so that an SQL injection is not possible.
* Show success or error message after submission.
* Use appropriate form validations for all input fields.
* Save product data to the database.

**BONUS QUESTION:** Use AJAX to validate & submit the form.

### Currency conversion

In the product list, convert the price from EUR, THB, HKD... to USD using one of the free APIs (Yahoo Finance, Google, ...). It needs to be real time (currency exchange rate can be cached for a few hours).

### Submitting the assignment

Fork this library on GitHub, push your solution and create a pull request.

Prepare a "how-to" quick manual for us about how to run the project - which URL to run, which SQL to run in database before we run it etc.

Make sure we can easily run the project. It needs to "just work." :)

## Additional info

* Use any PHP or Nodejs framework you want or no framework at all, it's up to you.
* Use [Twitter Bootstrap](http://getbootstrap.com) CSS framework to create a beautiful form and list of products.
* The code needs to work after we pull it and try it (no bugs).

**BONUS QUESTION:** Cover code with unit tests (at least some parts of it).

## What we will be checking?

* Quality & re-usability of the code
* Is the code easy to understand? Is it clean? Well commented?
* Does he/she implement the code according to PHP best-practices?
* Are there any bugs? 
* Did he/she solve the business requirement?
* Is the website (form + list) easy to use for the end-user?

