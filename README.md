# E-Commerce-API

## start applicationn

npm start

# ABOUT

This is an E-commerce API made using Node.Js & MongoDB.

STEPS TO USE THE API:

1. run "npm init" command on terminal in this projects directory
2. start the server using node app.js
3. Open postman
4. In headers make content-type=application/json
5. Make a GET request on localhost:3000/products
6. All The products should be visible

STEPS TO CREATE A NEW PRODUCT:

1. start the server using node app.js
2. Open postman or Thunder client in VS Code
3. put localhost:3000/products/create as the url.
4. Select Body tab below the url textarea and then select x-www-form-urlencoded
5. Add name & quantity as the keys and set the desired values for the keys.
6. Make a POST request.
7. If you recieve the message saying new product added successfully then you have done everything correct.
8. The product is created. Check it out by making a GET request at localhost:3000/products

STEPS TO DELETE A PRODUCT:

1. copy the object id of the product you want to delete.
2. add the id after localhost:3000/products/
3. In headers make content-type=application/json
4. Make a DELETE request.
5. You will recieve a message saying deleted successfully.

STEPS TO UPDATE THE QUANTITY OF A PRODUCT:

1. Copy the object id of the product whose quantity you want to update
2. Put the id after localhost:3000/products/
3. In headers make content-type=application/json
4. After putting the id add /update_quantity/?number={x} in the url where x is the number by which you want to increase or decrease the quantity.
5. the url should be looking like localhost:3000/products/{id}/update_quantity/?number={x}
6. Make a POST request and you should get a message containing the update product

# TECHSTACK

Node.Js, MongoDB
