/*
*this is a readme file for the PRODUCT STORE API*.
*this API allows you to get Access to our Products.

Type of Request:
GET 

Products Document contain the following fields:
featured,
*rating,
createdAt,
_id,
name,
price,
company*

Functionalities that this API provides:
1. Access to all products
2. Perform filtering such as sorting based on name, featured,company
3. perform comparism such as, say you want to  get access to the products price > 300. /products?price>300.
this will display and sort the document based on those that has price > 300.
4. you can also limit the number of of that you want to be displayed e.g /product?limit=10
this will display the product of the document
5.Pagination was also implemented. you can enter the number of page you to display and specify the limit e.g /product?page=3,limit=10
(note: by default, the product will display)




*/
