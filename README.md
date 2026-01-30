## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size
- See hover states for all interactive elements on the page
- Open a lightbox gallery by clicking on the large product image
- Switch the large product image by clicking on the small thumbnail images
- Add items to the cart
- View the cart and remove items from it


## Preview

![Project preview](https://github.com/tayobillz/E-commerce-product-page/blob/main/my%20screenshot2.png)
![Project preview](https://github.com/tayobillz/E-commerce-product-page/blob/main/my%20screenshot.png)


---

## My process
I started by breaking the design into clear sections and building the layout with semantic HTML. I focused on getting the desktop layout right first before worrying about responsiveness.

Next, I styled the page using CSS Flexbox and Grid to closely match the provided design, paying attention to spacing, typography, and colors. I reused consistent class names to keep the styles easy to manage.

For interactivity, I used vanilla JavaScript. I implemented the image gallery, cart quantity controls, and checkout popup by selecting DOM elements and attaching click event listeners. I made sure the cart logic updated dynamically based on user actions and prevented invalid states like checking out with zero items.

Finally, I tested the UI interactions manually and fixed issues related to event handling and class name mismatches to ensure everything worked as expected.

## Features

- Responsive navigation (desktop and mobile)
- Product image gallery with thumbnails
- Lightbox image preview
- Quantity increment and decrement
- Add to cart functionality
- Cart dropdown with item count
- Checkout popup modal with total calculation

---
### What I learned

I learned how to add responsiveness to a website so it fits and works well on different screen sizes. This included using flexible layouts, media queries, and responsive images to ensure the design adapts properly across mobile, tablet, and desktop screens. I also improved my JavaScript skills by working with the DOM, using querySelector, and handling user interactions with event listeners.


## Built With

- HTML5
- CSS3
- JavaScript (Vanilla)

---


