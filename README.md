# Product_Rest_Api
Simple Rest Api that manages a list of products, made it with Python and Flask as the main framework.

### With a list of products previously created we can use the main rest Api functions(GET, POST, PUT, DELETE) to manage it and modifying as you needed.

Using Postman you can create your requests, these are some examples:

(Programmed to be used in the **port '4000'**)

### Example using the request: GET localhost:4000/products
Gives you the whole list of products

![getproducts](https://user-images.githubusercontent.com/74435367/186738087-50d21110-9fc5-4b8c-bdb1-957bad3c8747.png)

### Example using the request: POST localhost:4000/products
Writing in raw form and text type JSON

![postproducts](https://user-images.githubusercontent.com/74435367/186738117-a07b907a-5d71-4bde-a510-15963dc3a131.png)

### Example using the request: PUT localhost:4000/products/{PRODUCT_NAME}
Makes you able to edit a certain attribute of the product or the entire product

![putproducts](https://user-images.githubusercontent.com/74435367/186738131-f4835832-2caa-4834-914b-480cc3b61a23.png)

### Example using the request: DELETE localhost:4000/products/{PRODUCT_NAME}
Makes you able to delete a product by name

![deleteProducts](https://user-images.githubusercontent.com/74435367/186738149-55029ea7-c8ac-4ead-880a-750af0ea528f.png)
