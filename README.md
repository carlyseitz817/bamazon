# Bamazon

![Demo](https://user-images.githubusercontent.com/45019573/54568646-0774ba80-49a6-11e9-8784-f997571afb32.gif)

Bamazon is a CLI (command line interface) application that allows user to go through a mock process for buying items. The steps in the process are as follows:

1. User runs `node bamazonCustomer.js` in their command line

2. Table containing information with information for available products is shown.

3. User is prompted to input the ID and quantity of the item they'd like to purchase.

4. Application checks if store can meet customer request with available inventory. 

5. If the store doesn't have enough inventory of the requested item, the app displays a message to tell the user not enough inventory is available to fulfill their request, and then prevent the order from going through. However, if it does, the application will successfully submit the order and continue on to step 6.

6. Update the SQL database to reflect the remaining quantity.

7. Show the customer the total cost of their purchase.