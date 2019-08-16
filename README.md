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

  API keys should never be pulished on your repo. So, I made a few changes to the way `.env` was handled - Gatsby does't exactly spell it out step by step anywhere so HERE YOU GO! 

   Install dotenv

   `
   npm i dotenv
   `

3. **Already done in this repo. Invoke dotenv at the top of `gatsby-config.js` with this:**

   ```
   require('dotenv').config({
   path: `.env.${process.env.NODE_ENV}`
   })
   ```

4. **Be sure to prefix your variables in your `.env` files with `GATSBY_` or they will not be readable.**

   ```
   GATSBY_SHOP_NAME=graphql
   GATSBY_SHOPIFY_ACCESS_TOKEN=dd4d4dc14654not2breala7763305d71d1b3d38
   ```

5. **Update your `package.json` scripts like this:**

   ```
   "build": "GATSBY_ENV=production gatsby build",
   "develop": "GATSBY_ENV=development gatsby develop",
   ```

6. **Don't forget to add your `.env*` files to `.gitignore` before initial commit.**