# ecommerce store challenge frontend

In this challenge you are going to create a single page application of a e-commerce shopping store
to help users browse products, add to cart and go to the product cart details.
In this challenge you are going to create 3 pages
- product list
- product details page
- cart page

## Stories to implement

You can refer to the mockup for each story to implement

### 1 - project setup
- Setup the git repository
- create the project files
- Add a readme explaining how to install and start the frontend application
- Add routes to the 3 pages home (product listing page), product and cart details page.

In these steps you can use a frontend framework of your choice and a ui library of your choice if you want.

### 2 - product listing page
In this step you are going to use the fake api store as a backend api from https://fakestoreapi.com/ 

- create a product listing page that consumes the api, the product listing page should display all the products
- add a basic layout to the page, here we are displaying 3 products per column (refer to the mockup)
- once the user click on a product, he should be redirected to the product details page

### 3 - product details page
- create a product details page using the endpoint `get single product` from the fake api store
- display two columns (image and product details)
- product details should have title and description
- add a component `add to cart` below the description and title to allow users to add product to the cart

### 4 - cart details page
- Add a cart details page that should list all the products added to the cart.
- when the cart is empty display a friendly message to the user, add a link to the home page
- Add a button next to each product to allow users to remove product from the cart

## 5 Bonus

- Implement change quantity component to allow users change quantity
