README File:
This is a group project. Group size is 5.
Server: APACHE TOMCAT 7.0.34
JDK: jdk version 6 or 7
Database Server: MongoDB
“Database file” for the list of all collections.

Features:
Name of the database for Project: ItalianBistro
Instructions to run the “ItalianBistro” restaurant web application
1. The homepage (index.jsp) contains the menu items for food served in our restaurant and also they be purchased online.
2. At the top, under the logo  “Italian Bistro”, there are 4 links
* MY ORDERS- This link will list the orders placed in that session and also if a user is already logged in, it will show that specific user’s order history.
* SHOPPING CART- To see the items added to the cart by the user in that session
* SIGNUP-To create new user accounts.
* LOGIN-For existing users to login into the website using their UserId and Password.  Once the user logs in, he/she can logout by clicking the LOGOUT option in the Home page.
3. The Food Search text box allows users to search for any specific food. It’s an auto-complete search box i.e. if the user types in “g” in the search box, all the items starting with “g” will be listed.
4. The user can select any one of the items listed below to go to that particular item rather than doing extensive navigation.
5. The left navigation contains some of the menu categories like Appetizers, Soups, Salad, Pizza, Pasta, Strudels, Desserts and Beverages. Every item contains their description and price.
6. Clicking on these links gives you their respective pages where in the user can buy these items by clicking “Add To Cart”.
7. Also, the left navigation contains Reviews, wherein the user can read reviews written by other users and write reviews wherein the user can write their own reviews by choosing the item for which they need to write the review.
8. There are options above the main content section like
* Home-Link to the home page
* Online-order-This page helps in placing the online order for pick-up and delivery
* About-Us-A short description of our restaurant Italian Bistro and the various services provided.
* Track Order-This page prompts the user to enter the confirmation number of the order placed and enables him/her to check the status of their order.
* View Location-To locate the restaurant and helps the user in locating the restaurant using Google Maps.
* Dine-In: 
* Make a Reservation-This functionality lets the user select a table from the available tables and lets the user enter their expected  dine-in time (in “HH:mm” 24-hour format and date in “dd-mm-yyyy” format) and reserve a table. It is not possible to book an already reserved table on the same day and same time.
* Cancel Reservation-To cancel reservation the user must enter the required fields. The user will be able to cancel the reservation up to 10 minutes before the actual table reserved time.
* View Reservation-This lets the user to view the reservation they have made including the history of their reservations.
9. The main content contains the 
* “Christmas Special” – To view the seasonal special menus that can be purchased online.
* Gift cards- Gift cards of $10,$25,$50,$100 can be purchased online by the users
* Favorites- Lists the favorite items based on the average reviews obtained for each food item. This is linked with the MongoDB collection “myReviews”. So only if there are entries in “myReviews” collection, Favorites link will function properly.
* Promotions –This page contains promo code that can be applied to the online order for some discounts on the items purchased. 
10. The items added in the cart can be purchased by the user either if he is logged in or as a guest (without logging in).
11. Once the user adds item to the cart, immediately the cart, along with the items in it will be displayed to the user.
12. The cart will have options to remove an item, update the quantity of an item and the price for each items added in the cart will be displayed.
13.  Below the cart the user will have options to either checkout or continue shopping.
14. Once the user clicks on the “Checkout” button he will be prompted to “Buy.java” which will list the items in the cart. Here the cart cannot be modified.
15. This page contains the “PromoCode” option where the user can enter a promo code (12345) from the” promotions.html” page to get the discount of $1 on each item.
16. Then the user will be asked to enter few details in-order to purchase the items in the cart.
17. The user must enter the time in HH:mm format (24-hr format) and can choose for either “Pick-up” or “Home-delivery” options.
18. “Home-delivery” is available for any addresses within 25 miles from the restaurant location for that order to be placed. 
19. Online orders (except Pick-up) can be cancelled up to 1 hour before the expected delivery time.

20. Store Manager Login Page: 
   Username: “Store” ; Password: “ Manager”
21. The store manager page displays the feedback (if any in the mongo DB) for the website given by the customers.
22. The store manager will be able to add new food and view catalog for menu items, add table details and view table reservation details in “View Tables”.
23. In the homepage of store manager, there is a “Customers” tab at the top, which is used for creating customer accounts, placing new orders for customers, updating the existing customer orders, making a new table reservation and view the existing table reservations.
24. The footer part of the website contains links for the following:
* About Us- A short description of our restaurant Italian Bistro and the various services provided.
* FAQ (Frequently Asked Questions)- Some questions and answers that will help the customers to know about the restaurant and its services.
* Contact Us- Contact Information for ItalianBistro with address and phone number
* Feedback-A form where customers can give suggestions on improving the website.
* Site Map-This link contains the direct links to all the menus and sub-menus in the website.
Use google chrome to see the full functionalities.










