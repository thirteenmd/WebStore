# Template for a web store.
## Page components outline:

### Header
* store logo - aligned on the left side of the page
* Basket & Total - aligned on the right side of the page

### Navigation menu
* a list of links, the first link should have an active style

### Product List
* A list of products containing product image, title, price and Call To Action button (add to basket / remove from basket);
* Add to basket and Remove from basket must have different styles;

### Footer
* A footer, sticked to the bottom of the page;

## Functional Requirements:
1. Basket counter
Basket counter should display the number of items added to the basket;
- In case no items are added, it should read "Basket: empty";
- In case there is one item added, it should read "Basket: 1 item";
- In case there is more than one item added, it should read "Basket: x items" - where x is the number of items;

2. Basket Total
Basket total should be the sum of added to basket product prices;
- In case no items are added, it should read "Total: $0.00";

3. Product - Add to Basket
- Add to basket button, should increase the number of Basket Counter;
- In case the product was added to basket, the "Add to basket" button should change to "Remove from Basket";

4. Product - Remove from Basket
- Remove from basket button should decrease the number of Basket Counter;
- In case the product was removed from basket, the "Remove from Basket" should change back to "Add to basket";

5. Product list
- Hardcoded HTML markup