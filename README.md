# ETG-Inventory-Management-Mini-Project
This Inventory Management Project will ease down the work of Owner as well as Customer. 
-> Diifernt Functionalities in this Inventory-Management-Mini-Project
  * loadJson(): This function will load the json file which contain the inforamtion of different Product. It also maintain the bill of a customer when customer purchase a product.
  * display(): This function will display the details of different Product to a customer.
  * getDetails(): It will take the input from the customer,about the product they want to purchace.
  * process(): First this function will check whether the input product is there in the inventory or not and also chech whether stock is sufficient or not. If it is sufficient then it will call update function and return the bill of that product to calling function.
  * updateRecord(): This function will update the stock in the record.json file.
  * billing(): This function will return the total bill of a customer. It also maintain the sales and update the record of sales in sales.json file. 
