<!-- AUTO-GENERATED-CONTENT:START (STARTER) -->
<h1 align="center">
  <img alt="Gatsby" src="resources/shopify+gatsby.png" height="60px" />
  <br/>
  Gatsby Shopify starter
</h1>
#🐱‍🐉
#MY Gatsby Shopify Starter Clone

##I made some modifications to this one: https://github.com/AlexanderProd/gatsby-shopify-starter


1. **Create a Gatsby Shopify site**

   ```sh
    # create a new Gatsby site using this starter
    gatsby new my-shopify-store https://github.com/I-keep-trying/gatsby-shopify
    ```

2. **Some security notes**

  API keys should never be pulished on your repo. So, I made a few notes about the way tokens should be handled, and how to do it specifically FOR GATSBY - Gatsby does't exactly spell it out step by step anywhere - it took a few tries for me so HERE YOU GO! 


**Already done in this repo. Invoke dotenv at the top of `gatsby-config.js` with this:**

   ```
   require('dotenv').config({
   path: `.env.${process.env.NODE_ENV}`
   })
   ```

3. **Be sure to prefix your variables in your `.env` files with `GATSBY_` or they will not be readable.**

   ```
   GATSBY_SHOP_NAME=graphql
   GATSBY_SHOPIFY_ACCESS_TOKEN=fakedd4d4dc14654not2breala7763305d71d1b3d38token
   ```

4. **Don't forget to add your `.env*` files to `.gitignore` before initial commit.**