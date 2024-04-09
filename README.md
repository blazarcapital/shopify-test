Shopify test
============

This is the job test if you wish to be a front-end developer. We strive to always deliver pixel-perfect design. What we are looking for are passionate developers, who can take the designed wireframe from idea to result.


Contents
--------

When you have completed this test you will have demonstrated skills/knowledge in
- git
- html
- css
- javascript
- liquid
- and most importantly: being able to understand a number of requirements that all add up to a seamless customer experience.


Requirements
--------
When building the different elements make sure to apply responsivness, so the page looks good on the following media queries:

- Mobile - 375px
- Tablet/Desktop - 768px


Hero banner:
- Show `Breadcrumbs`
- Show `Collection title`
- Show `Collection image`
- File located in `theme/snippets/collection-collection-hero.liquid`


Product list:
- Iterate over the products in the collection.
 - Use `product-card` snippet to render product and prevent repetitive code.
- File located in `theme/snippets/collection-product-list.liquid`


Product card:
- Show `Product title`
- Show `Product size`. Only included in the product title.
  - Find a smart way to show them display them separately.
- The `Product price`.
- The `Product description`.
- The 'Add to cart' button should only show on hover for desktop and always be visible for mobile.
- When hovering the product card on mobile, the image and 'Add to cart' button should have a smooth transition effect - Be creative, but keep it simple.
- On load the size of the product images should be portait format (3:4), even before they load to avoid the the layout shifting.
- File located in `theme/snippets/product-card.liquid`


Add to cart button:
- Use a click event to add the product to the cart. 
  - A product id and quantity is required when adding an item to the cart.
  - Show an alert when successful

Stylesheets
- Located in `theme/assets/theme.scss.liquid`

Scripts:
- Located in `theme/assets/theme.js.liquid`

Instructions
------------
To complete this test.
1. Fork this repository
2. Create a website based on the Figma file
3. Create a pull request to this repository

Note: Both products and collection have already been created in Shopify and available through Liquid. So there's no need to upload any assets.

Prerequisites
--------

[ThemeKit by Shopify](https://shopify.github.io/themekit/#installation)

ThemeKit allows you sync your local theme files to your Shopify store. You will be provided with
- A `config.yml` file to connect to your store to be placed in your root of your `theme` directory.
- A preview link to view your changes.

How to use:
- Navigate to your `theme` directory and run `theme watch -a` to start the sync between your local theme files and the store.

Instructions
------------
To complete this test.
1. Fork this repository
2. Create a website based on the supplied design files in the `design` directory (All images and icons are already in theme or available from Shopify)
3. Create a pull request to this repository


Helpful links
--------
[Liquid documentation](https://shopify.dev/docs/themes/liquid/reference)

[Liquid cheatsheet by Shopify](https://www.shopify.com/partners/shopify-cheat-sheet)
