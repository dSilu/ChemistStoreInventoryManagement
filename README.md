# ChemistStoreInventoryManagement

Inventory Management Project with JSON

This is an Inventory Management project for a chemist store or warehouse.

Problem Statement:
1. A chemist wants to automate his works.
2. To make a purchase book that stores the purchased history in a JSON file and uses it every time new products were bought.
3. The purchase JSON file gets updated automatic with every purchase.
4. To make a sells book that stores every data of selling in a JSON file that gets automatically updated every time a product is sold.
5. Another Search Notebook that searchs the store Inventory data and tells the availibility of a product.
6. The Search Notebook also saves the search data in a JSON file that helps the shop owner to understand people's need.

There are 4 JSON files i.e. 
i.   'chemist_store.json'    : The primary file that has the store data (Inventory data) of the shop.
ii.  'Purchase_Record.json'  : The JSON file to store every purchase data. 
iii. 'Sells_Record.json'     : The JSON file to store every sell data.
iv.  'Search_History.json'   : The JSON file to store search history of customers.

There are 3 Python Notebooks i.e.
i.   'Chemist_Store_Purchase_Notebook.ipynb : To process purchase of both existing and new products.
ii.  'Chemist_Store_Sells_Notebook.ipynb    : To process sells data and to generate bill 
iii. 'Search_engine_Notebook.ipynb          : To provide customers a user friendly searching engine of the store Inventory. 

** Enter the last 4 digits of the product id. To find the poduct ID use search engine.**

Note: 
1- The Search_engine_Notebook.ipynb takes medicine's name and if the medicine is available in the store, it returns the Product ID and price.
2- If the Medicine is not available, the Search_History.json file stores the data and lets the Owner know.
3- The Search_engine_Notebook only takes particula medicine Name. Hence, Try to write accurate name, if not found input the name with adding or removing the other parts of name as per choice.
