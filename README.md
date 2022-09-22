# Shopping-System
An online shopping system developed with Python, Flask, Jinja2 &amp; JavaScript, that integrates Machine Learning, Google Maps, GeoLocation &amp; MPESA.
All users are required to sign up and once they have an account they can sign in into the system.
The system require location access of the user which is then used as a center to find the circle on earth with a radius of 250m surrounding the user.
The purpose of this circle is to find all merchant shops within. These shops are considered to be near the shopper/customer. The customer can order items from any of these shops. When a customer picks any item  from a particular shop, the customer receives the best recommended items from the same shop just next to the selected item. Items are recommended based on Market Basket Analysis using Apriori algorithm, which finds the strongest association rules and the items that are recommended are the ones which are most likely to be bought together with the ones that the customer has already added in the cart.
Any user can become a merchant by creating a shop whereby his/her current coordinates are set to be the fixed coordinates of the shop. The owners of the shops have full priviledge over their shops. They can edit their shop detail like the name, shop avatar etc. They can also add or remove items plus managing item details such as item description, price, and quantity.
The shopkeepers can accept or reject the orders that were placed by the customers. If they accept, the customer will be allowed to pay for the items through 'Lipa na Mpesa' to the respective shopkeepers' business/till numbers. After payment, the customers can proceed to pick their items using MPESA transaction message or simply their username.
A customer may want to confirm the details of the shops he/she is shopping with. This is where Google Maps comes in. The customer can see the particular shop in the google map marked with markers showing the positions of both the shop and customer's. Additionally the customer can see the information of a particular shop including the name of the shopkeeper, distance in metres on how the shop is far from the customer, the business/till number, the phone number of the shopkeeper, the business number etc.
See below screenshots:
## 1. Login
![Login](https://github.com/SimonDouglas-bit/Shopping-System/blob/main/images/Screenshot%20from%202022-09-21%2012-03-56.png)
## 2. Or Register
![Register](https://github.com/SimonDouglas-bit/Shopping-System/blob/main/images/Screenshot%20from%202022-09-21%2012-10-44.png)
## 3. Home
![Home](https://github.com/SimonDouglas-bit/Shopping-System/blob/main/images/Screenshot%20from%202022-09-21%2012-04-59.png)
## 4. Switch Shop
![Switch shop](https://github.com/SimonDouglas-bit/Shopping-System/blob/main/images/change%20shop.png)
## 5. Logged in user
![Loggedin](https://github.com/SimonDouglas-bit/Shopping-System/blob/main/images/loggedin.png)
## 6. Items of a shop
![Items](https://github.com/SimonDouglas-bit/Shopping-System/blob/main/images/items.png)
## 7. Recommendations
![Recommendations](https://github.com/SimonDouglas-bit/Shopping-System/blob/main/images/recommendations.png)
## 8. See the cart (To see the cart a user clicks where shown)
![See cart](https://github.com/SimonDouglas-bit/Shopping-System/blob/main/images/cart.png)
## 9. Cart items (Items that a users has added to his cart)
![Cart items](https://github.com/SimonDouglas-bit/Shopping-System/blob/main/images/Screenshot%20from%202022-09-21%2012-09-25.png)
## 10. Orders (To see the orders placed, a user clicks where shown)
![Orders](https://github.com/SimonDouglas-bit/Shopping-System/blob/main/images/orders.png)
## 11. Placed orders (The orders that a user placed)
![Placed orders](https://github.com/SimonDouglas-bit/Shopping-System/blob/main/images/Screenshot%20from%202022-09-21%2012-07-45.png)
## 12. Pay for the cart (A customer can pay for the cart once it has been approved by the shopkeeper)
![Pay for cart](https://github.com/SimonDouglas-bit/Shopping-System/blob/main/images/orderpay.png)
## 13. In placed orders, a user can also pay for the cart
![Pay from orders](https://github.com/SimonDouglas-bit/Shopping-System/blob/main/images/mpesa.png)
## 14. Confirm delivery
### If the customer already picked for the cart, he/she can confirm he picked to avoid conflicting self
![Confirm delivery](https://github.com/SimonDouglas-bit/Shopping-System/blob/main/images/confirmdelivered.png)
