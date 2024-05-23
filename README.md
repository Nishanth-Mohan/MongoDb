<h1 align="center">Hi 👋, I'm Nishanth M</h1>
<h3 align="center">A passionate frontend developer from India</h3>

-  Task name: **MongoDB Day 1**
-  Language used: **MongoDB**
-  Discription: **I have displayed the summary of MongoDB queries for retrieving information from a product database.**

  **1) db.products.find({})** <br>
   This query retrieves all documents from the "products" collection, providing information about each product.

  **2) db.products.find({$and:[{'product_price':{$gt:400}},{'product_price':{$lt:800}}]});** <br>
   This query retrieves products with prices between 400 and 800.

  **3) db.products.find({$or:[{'product_price': {$lt:400}},{'product_price':{$gt:600}}]});** <br>
    This query retrieves products with prices not between 400 to 600.

  **4)db.products.find({'product_price':{$gte:500}});** <br>
    This query retrieves four products with prices greater than 500.

  **5)db.products.find({},{'product_name':1,'product_material':1});** <br>
     This query retrieves the product name and product material of each product.
     
  **6) db.products.find({'id':'10'});** <br>
     This query retrieves the product with a row id of 10.

 **7)db.products.find({},{'product_name':1,'product_material':1,'_id':0});** <br>
     This query retrieves only the product name and product material of each product.
     
**8) db.products.find({'product_material':'Soft'});** <br>
     This query retrieves all products containing the value "soft" in the product material field, regardless of case.
     
**9) db.products.find({$or:[{'product_color':'indigo'},{'product_price':492.00}]});** <br>
     This query retrieves products containing either the product color "indigo" or the product price 492.00.
     
**10) db.products.deleteMany({'product_price':{$eq:28}});** <br>
    This query deletes all products with a product price value of 28.00.

-  How to reach me: **6369303696**

<h3 align="left">📫 Connect with me: nishanthmohan2k15@gmailcom</h3>
<p align="left">
</p>
