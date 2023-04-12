# Shopify-Recommended-Products-on-Cart

![image](https://user-images.githubusercontent.com/1571083/231435900-9757355e-e5f3-4c60-b2be-b7e8bb2f47fe.png)
![image](https://user-images.githubusercontent.com/1571083/231435940-da39a4e4-fea9-4bd7-81e5-529179561b68.png)

# Step 1. 
- Add Owl Carousel to your theme.liquid file

Include the necessary OwlCarousel CSS and JS files in your theme. Add the following lines to your theme.liquid file within the <head> section:
> <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/assets/owl.carousel.min.css" />
> <link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/assets/owl.theme.default.min.css" />

And add the following line just before the closing </body> tag:
> <script src="https://cdnjs.cloudflare.com/ajax/libs/OwlCarousel2/2.3.4/owl.carousel.min.js"></script>

If your theme does not already have jQuery, make sure to add it BEFORE the owl carousel JS file
> <script src="https://cdnjs.cloudflare.com/ajax/libs/jquery/3.6.4/jquery.min.js" integrity="sha512-pumBsjNRGGqkPzKHndZMaAG+bir374sORyzM3uulLV14lN5LyykqNk8eEeUlUkB3U0M4FApyaHraT65ihJhDpQ==" crossorigin="anonymous" referrerpolicy="no-referrer"></script>

# Step 2. 
- Add the product recommendations code to your cart page - see the file cart-code.liquid 
- I added it under cart items container, feel free to add it anywhere. Wherever you add it, you must add the cart-script before the schema tag in that file.
