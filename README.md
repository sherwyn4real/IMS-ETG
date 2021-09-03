# IMS-ETG
## An Inventory Management System using Python(Jupyter Notebook)

* Sell_Products.ipynb is the main jupyter notebook file which houses the entire code that interfaces with a customer
* Add_Products.ipynb works with the seller. When new products are bought into the inventory, they get updated here
* records.json is a dynamic database that houses the available products in the inventory and updates the same, as and when products are sold to customers
* sales.json stores the details of products sold on a particular day. It contains arrays of dictionaries and can filter them based on date of purchase





### The products in the inventory are first shown to the customer as a menu like this:

![image](https://user-images.githubusercontent.com/62534363/132044393-c7a2743d-f159-4594-a49e-bd8dbca3dd66.png)


### The customer is then asked if they want to filter products by category of their choice. If yes, then a filtered list is further shown to them like so:

![image](https://user-images.githubusercontent.com/62534363/132044662-ebd4a456-afc4-444c-a9b3-514d032b7e20.png)


### The customer then enters the product ids of all the products that they want along with the quantity needed and the program proceeds to show the shopping cart and thereafter, the bill is generated:

![image](https://user-images.githubusercontent.com/62534363/132045197-e70c39c6-544c-4068-9ee7-d06ea514aa40.png)

### Bill generated looks like this:

![image](https://user-images.githubusercontent.com/62534363/132045308-28e3334d-76a0-4872-bef4-bfcb8fdfefef.png)


### Products that are sold are recorded in the sales file(sales.json) as follows, after updating the inventory(records.json):

![image](https://user-images.githubusercontent.com/62534363/132045521-7e65abff-8bd6-4a40-b2af-69ed99defee3.png)


![image](https://user-images.githubusercontent.com/62534363/132046811-9006eef0-7ec6-45c8-90be-1c05f35965e1.png)


### Products can also be added to the inventory with the help of the Add_products.ipynb file:

![image](https://user-images.githubusercontent.com/62534363/132045702-555d813b-d2ac-4372-b466-45567f9682d5.png)



### Finally, if the quantity of a product needed by a customer, exceeds the the quantity in the inventory, or if a wrong product id is entered by the customer, then they are alerted accordingly:

![Screenshot 2021-09-03 231235](https://user-images.githubusercontent.com/62534363/132046279-be597d82-e522-49f1-ba77-58137678081c.png)


![image](https://user-images.githubusercontent.com/62534363/132046415-ae15509e-d761-4029-a058-92d78a39e9f6.png)


