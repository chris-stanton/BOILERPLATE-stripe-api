
# Stripe API Boilerplate

## Description:
###### Node.js/ Express app that uses the Stripe API to process credit card transactions.  Boilerplate is desktop and mobile friendly.


## Technologies Used:
  1. Node.js
  2. Express.js
  3. Body-Parser
  6. Handlebars-forms
  7. Express-handlebars
  8. Stripe API
  9. GIT / GitHub


## Install App:
1. Create stripe account at ``www.stripe.com``
2. Create a config/keys_dev.js file

  ````
  module.exports = {
    stripePublishableKey:'_YOUR_OWN_PUBLISHABLE_KEY_',
    stripeSecretKey:'_YOUR_OWN_SECRET_KEY_'
  }
  ````
3. Run commands:
    - `` npm install `` Installs Node Packages including dependencies from package.json
    - ``` npm start ``` Starts server
    - ``` npm test ``` Starts server using Nodemon
4. Server is listening on port: 5000
5. Credit Card Number: ``4242 4242 4242 4242`` provided by stripe for testing purposes ONLY.  THIS IS NOT A VALID CREDIT CARD


## License
##### Copyright 2017 Christopher J. Stanton

###### Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

###### The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

###### THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.
