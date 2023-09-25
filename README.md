# The game 2048 is created on pure JavaScript.

  - [DEMO LINK](https://Maks-Tsarenko.github.io/react_phone_catalog/)

Phone Catalog - A comprehensive and functional e-commerce website, where you can explore various phone models, choose your favorite phones, add them to your favorites or cart, and much more! This site is effective and adapted to both the web version and mobile phones.

This catalog consists of 9 pages: Home, Phones, Accessories, Tablets, Favorites, Cart, Contacts, Page Not Found, Review Selected Phone.

Technologies used: **HTML**, **SCSS**, **React**, **JS**, **TypeScript with React**, **React-Routes**, **API**, **ClassNames**, **Local Storage**, and others


**Homepage**

1. **Navigation Bar**: At the top of the page is a navigation bar that allows visitors to easily navigate to any other page on our site, providing convenient and quick access to all sections.

2. **Banner**:  On the main page, the assortment is presented with the help of a banner that illustrates the different categories of products available on the site. This helps visitors quickly find their way around  assortment.

3. **“Hot Prices”**: Part of the main page is the “Hot Prices” block, which displays phones with current discounts. In this block, the phones received from the backend are filtered to display only those with the biggest discounts so visitors can easily find great deals.

4. **Shop by Category**: The Shop by Category section provides links to different product categories such as phones, tablets and accessories. This block not only makes navigation easier, but also indicates the number of models available in each category.

5. **" Brand New models"**: a block where you can find the newest models, automatically filtered when received by the server.

6. **Footer**: The footer contains links to other pages on the site. There is also a button here that allows you to easily return to the very top of the page.


**Phones page**

1. **Navigation Path**: There is a navigation path at the top of the page that allows users to easily return to the home page when needed.

2. **Search** This page features a search tool that allows us to find any phone. The search tool is intelligent, so you can enter the phone name, memory, and color in the order you prefer. Phones that match the criteria will be instantly displayed on the page, while those that don't meet the criteria won't be shown. If the search yields no results, you'll be redirected to the "Nothing Found".

3. **Custom DropDowns**: The page implements custom DropDowns, which give users the opportunity to sort phones by various parameters and the number of products on the page. Users can customize the sorting according to their needs.

4. **List of Phones**: After applying filters, users are shown a list of phones that match their criteria. Each phone is accompanied by a photo, name, short description and price. This helps visitors easily find and compare different models. Also, the user can immediately add any phone to favorites or immediately to the basket using the appropriate buttons.

5. **Pagination**: At the end of the phone list, users find a section with pagination. This feature makes it easy to manage your list of pages and switch between them to view more products without overloading the page.


**Pages of tablets and accessories**

These pages are currently (supposedly) under development as the backend for these pages is unavailable and naturally there are no products to display. But the logic of these pages is written so that after these products are on the server, they will be displayed in the same way as the products on the "Phones" page.


**Review page**

1. **Overview Phone Information**: After clicking on the phone card, users are taken to the overview page where they can find a complete description of the phone including its specifications, features and features.

2. **Choose color and memory capacity**: On this page, users can choose the desired phone color and memory capacity. They can select one or more options they are interested in and choose the number of gigabytes for each color.

3. **Add to Favorites and Cart**: There are "Add to Favorites" and "Add to Cart" buttons on the phone overview page. Users can use these buttons to save the phone for later review or select it for purchase. If the user changes his mind, he can remove the product from the list by pressing the corresponding button again.

4. **Block "You may also like"**: In addition to the phone description, users will also find a section at the bottom of the page where the store owner recommends other phones that customers may be interested in. This feature helps users learn about other options they can consider when choosing.


**Page Not Found**

**Error message**: When entering an invalid URL, users are taken to a "Not Found" page. Here they see a message informing them that the page was not found.

**Link to the main page**: This page always contains a link to the main page of the site, allowing users to return to the main page and continue browsing the site.


**Favorites Page**

1. **Empty "Favorites" page**: On first visit, this page is empty and users see a message recommending to add selected products.

2. **Favorite Counter**: The Favorites page also displays a counter that shows the number of phones that have been added to the Favorites list by the user. It helps users track the quantity of their favorite products.

3. **Favorite Badge**: When a user adds a phone to their Favorites list, it is displayed with a red heart instead of a white one. This mark indicates that the product is part of the "Favorites" list and the user can easily distinguish his favorite items.


**Cart page**

1. **Counter of products in the cart**: The "Cart" page displays a counter that shows the number of phones added to the cart. This helps users track the quantity of their selected items.

2. **Phone Cards**: The page features rectangular phone cards, each with an image of a product. Users can click on a card to go to the review page for that particular phone.

3. **Manage products in the cart**: Each phone card has buttons for managing the products in the cart. Users can increase or decrease the quantity of a specific product, and also remove a model from the cart entirely by clicking on the "cross" icon.

4. **Total number and purchase amount**: To the right of the list of products, the counter displays the total number of phones added to the cart and the total purchase amount of all products. This helps users check how much they have in their cart and what the total cost of the purchase will be.

5. **Return to previous page**: There is a button that allows users to return to the previous page if they decide to add more items to the cart or continue shopping.

6. **Checkout Button**: Although this store is for personal use only and no actual transactions will occur, there is a button that allows you to simulate a checkout for demo purposes.


**Contacts**

1. **Methods of Contact**: The Contact page provides various ways to contact you. This can be your email, phone number, social media accounts or other convenient means of communication.


**Regarding the phone cards:**

Each card comprises several aspects:

Phone image: Clicking on it leads to the Review Page.
Phone name.
Price: The current discounted price, with the original price struck through.
Phone description based on aspects such as Screen, Capacity, and RAM.


**Additionally, there are two buttons**:

1. **"Add to Cart" button**: Clicking it adds the item to the cart. Upon clicking, the button style changes and the label becomes "Added to Cart." Clicking again reverts the button to its default state.
2. **Heart button**: Clicking it adds the phone to favorites, allowing for more detailed exploration. Upon clicking, the heart icon turns red until clicked again to remove it from favorites.
