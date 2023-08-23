Welcome to React Toy Shop E-Commerce Website
This is a simple and fun e-commerce website built using React, where you can explore and buy various toys for yourself or your loved ones. The website is designed to provide a user-friendly shopping experience and showcase the basic features of a modern e-commerce platform.

Features
1. Interactive and Responsive Design
Our website is built with React, a popular JavaScript library for building user interfaces. This means the website will adapt and look great on different devices, whether you're using a computer, tablet, or smartphone.

2. Browse Toys
You can easily browse through a wide selection of toys. The toys are categorized to help you find what you're looking for more quickly. From action figures to board games, we've got something for everyone.

3. Product Details
Clicking on a toy will take you to its product page. Here, you can find more information about the toy, including its description, price, and any special features it might have.

4. Add to Cart
Found something you like? Just click the "Add to Cart" button on the product page. This will collect the items you want to buy in your virtual shopping cart.

5. Shopping Cart
In the shopping cart, you can review the items you've added. You can adjust the quantities or remove items if needed. The cart will also show you the total cost of your selections.

6. Easy Checkout
When you're ready to make your purchase, you can proceed to the checkout page. Here, you'll provide your shipping information and choose a payment method. We've kept the process simple and streamlined.

7. Responsive Feedback
Throughout your shopping experience, you'll receive responsive feedback. For example, if you try to add more items to your cart than we have in stock, we'll let you know.

Getting Started
To run this project locally and explore its features:

Clone this repository to your computer.
Navigate to the project's directory in your terminal.
Run npm install to install the required dependencies.
Run npm start to start the development server.
Open your web browser and go to http://localhost:3000 to see the website in action.
Contributing
We welcome contributions to improve and expand this toy shop project. Feel free to fork this repository, make changes, and submit pull requests.

Enjoy your time exploring our React Toy Shop E-Commerce Website! If you have any questions or feedback, don't hesitate to contact us.

Note: This project is for educational and demonstration purposes only. No actual products are being sold on this website.


                                                            :ROUTES :

                                                           FOR CATEGORY:

Route 1: Get All Categories
HTTP Method: GET
Route: /get-all-categories
Function: getAllCategories
Description: This route fetches and returns a list of all toy categories available in the database. It's used to populate the "All Categories" page and allow users to explore different categories.
Route 2: Get Category by ID
HTTP Method: GET
Route: /get-category-by-id
Function: getCategoryByID
Description: This route takes a category ID as a query parameter and retrieves the details of that specific category from the database. It's useful for displaying the details of a particular category.
Route 3: Create Category
HTTP Method: POST
Route: /create-category
Function: createCategory
Description: This route allows administrators to create a new toy category by sending a POST request with the required category information in the request body. After successful creation, the new category is added to the database.
Route 4: Update Category
HTTP Method: PUT
Route: /update-category
Function: updateCategory
Description: Administrators can use this route to update the details of an existing toy category. They need to provide the updated information in the request body along with the category ID. The category details in the database are then modified accordingly.
Route 5: Delete Category
HTTP Method: DELETE
Route: /delete-category
Function: deleteCategory
Description: This route enables administrators to remove a toy category from the database. It requires the category ID to be sent as a query parameter. Once the category is deleted, it will no longer appear in the list of available categories.
These routes and functions provide a way to manage toy categories within your e-commerce website's backend. Make sure to implement these functions and connect them to your database and frontend components to enable smooth category management.

                                                      FOR PRODUCTS:

Route 1: Get All Products
HTTP Method: GET
Route: /get-all-products
Function: getProducts
Description: This route fetches and returns a list of all products available in the database. It's used to populate various parts of the website where users can view and explore different products.
Route 2: Get Product by ID
HTTP Method: GET
Route: /get-product-by-id/:_id
Function: ProductbyId
Description: This route takes a product ID as a URL parameter and retrieves the details of that specific product from the database. It's used to display the detailed information of a particular product.
Route 3: Get Products by Category
HTTP Method: GET
Route: /get-product-by-category/:category
Function: ProductbyCategory
Description: This route takes a category name as a URL parameter and retrieves a list of products that belong to that specific category. It's used to show products categorized under a particular category.
Route 4: Add Products
HTTP Method: POST
Route: /add-products
Function: postProducts
Description: This route allows administrators to add new products to the database. Administrators need to send the product details in the request body to create a new product entry in the database.
These routes and functions provide the necessary API endpoints to manage products within your e-commerce website. Make sure to implement these functions on your server, connect them to your database, and use them in your frontend components to create a seamless shopping experience for your users.

                                                     FOR USERS:

                                                     Route 1: Create Dummy User
HTTP Method: POST
Route: /users
Function: Dummy
Description: This route is used for testing purposes and creates a dummy user. It may not have any significant effect on your actual user management process.
Route 2: User Sign Up
HTTP Method: POST
Route: /signup
Function: SignUp
Description: This route enables users to sign up by sending their registration information (such as name, email, password) in the request body. Upon successful registration, a new user account is created in your system.
Route 3: User Login
HTTP Method: POST
Route: /login
Function: Login
Description: Users can log in using this route by providing their email and password in the request body. If the provided credentials are valid, a successful login response is sent back, often including a user authentication token.
Route 4: Get All Users
HTTP Method: GET
Route: /getallusers
Function: allUsers
Description: This route fetches and returns a list of all users registered in your system. It's typically used for administrative purposes to view the user list.
Route 5: Get User by Email
HTTP Method: GET
Route: /userbyemail/:email
Function: getUserbyEmail
Description: This route takes an email address as a URL parameter and retrieves the details of the user associated with that email.
Route 6: Get User by Email (Alternative)
HTTP Method: GET
Route: /getuserbyemail
Function: userbyEmail
Description: Similar to the previous route, this one also retrieves user details by email. The difference lies in the way the email parameter is provided, likely through query parameters instead of being part of the URL.
These routes and functions facilitate user management within your e-commerce website's backend. Make sure to implement these functions, integrate them with your database, and use them appropriately in your frontend components to provide a smooth and secure user experience.




