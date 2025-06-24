# COSC-Amazon-product-Card-Clone
Solution:
I created a product card layout that looks like an Amazon listing. I used HTML to structure the content and CSS to style it.

Approach:
I used a .product-card div to wrap everything.
The image is placed at the top using an <img> tag with width: 100% and fixed height (400px) so it stays the same size.

I used object-fit: cover to make sure the image fits nicely without stretching.

Product info like title, stars, rating count, price, delivery, and button is placed inside .product-info.

For the button, I gave it a yellow background and made it round to look like the Amazon "Add to cart" button.

I used flex on the body to center the card on the screen.

⚠️ Challenges:
Setting the right image height without messing up the layout was tricky, but object-fit: cover helped.

Making sure the font sizes and spacing matched the original design took a bit of tweaking.

I had to guess some colors like the star rating and delivery text to match Amazon’s look.
