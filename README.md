# Shopping-System
An online shopping system developed with Python, Flask, Jinja2 &amp; JavaScript, that integrates Machine Learning, Google Maps, GeoLocation &amp; MPESA.
All users are required to sign up and once they have an account they can sign in into the system.
The system require location access of the user which is then used as a center to find the circle on earth with a radius of 250m surrounding the user.
The purpose of this circle is to find all merchant shops within. These shops are considered to be near the shopper/customer. The customer can order items from any of these shops. When a customer picks any item  from a particular shop, the customer receives the best recommended items just next to the selected item. Items are recommended based on Market Basket Analysis using Apriori algorithm, which finds the strongest association rules and the items that are recommended are the ones which are most likely to be bought together with the ones that the customer has already added in the cart.
Any user can become a merchant by creating a shop whereby the current coordinates are set to be the fixed coordinates of the shop.
