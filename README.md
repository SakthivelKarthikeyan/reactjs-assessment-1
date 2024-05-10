# Simple Counter App
This tiny application is like adding, removing, deleting, resetting products which reflects in the total number of products into our shopping cart.

## Meta
- This project is created by https://create-react-app.dev (as shown in the previous session).
- The counter app code copied from https://github.com/arnab-datta/counter-app (just to save time).
- For icons and styling we use font-awesome(https://fontawesome.com) and bootstrap(https://getbootstrap.com).

## Known behaviour of the app
- Able to see the total number of items in the cart on the top.
- By clicking the refresh icon(green one) we can able to **reset the individual item counts**. And it is **disabled** when there are **no items in the cart**.
- By clicking the recycle icon(blue one) we can able to **reset the app**. And it will only be **enabled** when there are **no items in the cart**.
- Every individual item has these elements.
    - First element - **Individual item count** and it shows the text 'Zero' when it has the value '0'. It turns blue when the value not equal to '0'.
    - Second element - It is a button used to **increment** the individual item count.
    - Third element - It is a button used to **decrement** the individual item count.
    - Fourth element - It is a button used to **delete** the individual item.

## Challenges
1. Now the app consist of 4 items in the cart statically and we can only delete the items. We should add the functionality to **add the items** upto **Maximum of 5**. For that we need to consider,
    - We need to **add the new element**(button) in the reset and recyle section.
    - The button should be in **round shape** and the text should be **'Add'**.
    - On clicking the button we should add the item in the **end of the cart**.
    - This button should be hidden when the **total number of items in the cart = 5**.
    - On resetting the app we should have atleast **one item** in the cart.
2. Add the input box next to fourth element of the individual item to hold the **item name**.
3. The text on the top 'Items' should be formatted as,
    - **'Item'** when there is **1** item in the cart. Otherwise it should be 'Items'.
4. The cart icon in the top to be shown as,
    - The icon(https://fontawesome.com/v4/icon/cart-arrow-down) to be shown if the **item count > 0**. Otherwise the default icon is used.
5. Hide the decrement button when the **individual item count = 'Zero'**. Otherwise it should be shown.

## To start
1. Run **npm install** to install dependencies.
2. Run **npm start** to start dev server.
