# PATS Bar and Grill - Restaurant app

https://project-2-group-1.herokuapp.com

This restaurant app is  a consolidated version where you can order food/ scroll through the menu, reserve table, read reviews about the restaurant favorite items, post your review about an item on the menu

Technologies used
* Node
* Express
* Sequelize
* Handlebars
* JQuery
* Slick.js
* Leaflet
* Google fonts

### How it works

This app has two main pages
* Dine-in page- This page allows the user to see if there are tables available to reserve a table. Also enables the user to reserve a table. Based on the availability of tables, user will be seated or will be put on a waitlist
* Carry-out page- This lists the menu and allow the user to order online/edit their order 
* Also there is a main page that has all the details about the grill-location,hours,team managing the grill


### Dine-in Page

When the user chooses to dine-in, he/she can check the app to see if there are tables available for reservation or can be added to waitlist

![Screenshot](/public/styles/dineinpage.png)

To make a reservation the user should fill in a form with all details to reserve a table

![Screenshot](/public/styles/reservetable.png)

Once the user submits the form, the user can go check the dinein page to see if the table is reserved or whether the user is waitlisted

![Screenshot](/public/styles/tablereservation.png)

### Carry out page

If the user decides to take out, this page has the menu to scroll through

![Screenshot](/public/styles/menu.png)

The user can click the "bag" icon to add to cart.

![Screenshot](/public/styles/cart.png)

 Also to know moreabout the item , user can click the arrow button before the name of the item. That opens the details about the item

![Screenshot](/public/styles/itemdetail.png)

The user can edit items in the cart by clicking the edit button in the order summary modal!

![Screenshot](/public/styles/editorder.png)

Once the user finalises the order, credit card details should be entered along with the phone number.

![Screenshot](/public/styles/creditcard.png)

After hitting confirm, the user is notified that the order has been placed and will be notified soon when the order is ready!

![Screenshot](/public/styles/orderconfirmation.png)

Also there is a section in this page where the user can read reviews about the customers favorite items on the menu

![Screenshot](/public/styles/review.png)

If the user wishes to post a review about one of the items on the menu, write a review button click will open up a form to submit review

![Screenshot](/public/styles/postareview.png)

#### Future enhancements will be
* Credit card/form validation
    - Adding a package/reuse code snippets to create better rules for validation

* User login 
    - Saving customer data and allow them to add favorites for future ordering

* Sending texts-notifying customers
    - Adding a package to send sms real time to the customer who orders food


* Admin portal
    - Managing menu,editing reserved tables/waitlist for tables will be available for authenticated users
