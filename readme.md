# Bamazon

This application implements a simple command line based storefront using the npm inquirer package and the MySQL database backend together with the npm mysql package. The application presents the interface in the perspective of the customer. 

### Prerequisites

In order to run this application, you should have the MySQL database already set up on your machine. If you don't, visit the MySQL installation page to install the version you need for your operating system. Once you have MySQL isntalled, you will be able to create the Bamazon database and the products table with the SQL code found in Bamazon.sql.

### Installing

To run the customer interface please follow the steps below:

	https://github.com/Teega/bamazon.git
	cd bamazon
	npm install
	node bamazonCustomer.js

## Running the app

Once the app launches, the customer is presented with a list of products. The following information is presented:
  - Item ID
  - Product Name
  - Department 
  - Price
  
The customer is then asked the following questions in sequential order: 
  1. Please enter the Item ID which you would like to purchase.
  2. How many do you need?
    If the product is in stock and the desired quantity is available the following message appears: 
    "Congratulations, the product you requested is in stock! Placing order!
    Your order has been placed! Your total is $29.950000000000003
    Thank you for shopping with us!"
    
    [Bamazon Demo] (https://goo.gl/75FPyU)


## Acknowledgments

* Hat tip to anyone who's code was used
