bamazon 

Node.js & MySQL

Overview
In this activity, I created an Amazon-like storefront using MySQL and Node.js. The app will take in orders from customers and deplete stock from the store's inventory. 

The app requires Node.js and the installation of the inquiry, mysql, and cli-table modules from node.js. 
NODE.JS CAN BE FOUND HERE: 
https://nodejs.org/en/

To install the proper modules: From the terminal, be sure you are in the directory containing bamazonCustomer.js.
**In order to properly install a database you must first enable servers with mamp and create a database!
Type the following in your terminal:
npm install inquiry
npm install mysql
npm install cli-table

How app functions:
A MySQL database called bamazon.db is created. 
A table inside of that database called products is created.
The products table should have each of the following columns:
-item_id (unique id for each product)
-product_name (name of product)
-department_name
-price (cost to customer)
-stock_quantity (how much of the product is available in stores)

Populate this database with around 10 different products. (i.e. insert "mock" data rows into this database and table)
Then the user will run the node application called bamazonCustomer.js. Running this application will first display all of the items available for sale. Include the ids, names, and prices of products for sale. 
The app should then prompt users with two messages.
The first should ask them the id of the product they would like to buy. The second message should ask how many units of the product they would like to buy. Once the customer has placed the order, your application should check if your store has enough of the product to meet the customer's request.
If not, the app should log a phrase like "Insufficient quantity!", and then prevent the order from going through. However, if your store does have enough of the product, you should fulfill the customer's order.
This means updating the SQL database to reflect the remaining quantity. Once the update goes through, show the customer the total cost of their purchase. 

Link to video walk-through:
https://drive.google.com/file/d/11JM2M0wQEWaOclvK5WkxKr8-36cxqXTI/view 