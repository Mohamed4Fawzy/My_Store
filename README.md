# My_Store

This is the capstone project of Udacity Angular Development Cross Skilling Nanodegree.
It showcases basic Angular usage in the example of a web-store. 

It features following functionality:

- Product list page, which displays the available products for the user to choose and add to their cart (in various quantities)
- Product details page, which displays more information about any particular product
- Shopping cart, which includes the products that the user has added to their cart
- Checkout form, which collects information about the user (e.g., name, address, payment details, etc.)
- Order confirmation page, which shows the outcome after the user completes the checkout process (i.e., submits the checkout form)


# Prerequisites

- Node.js
- AngularJS

# Instructions

1. Download the files in this repository
2. cd into the directory
3. ```npm install```
4. ```ng serve```
5. The project will be served on default on ```localhost:4200```


# Instructions

1. cd into the My_Store directory and ```npm install```
2. In the My_Store project look into ```src/environments/environment.ts``` and check if the ``àpi_host`` is one same port/url the API server is running (default: localhost:3000)
3. Build the project with ```ng build```
4. In the .env from the API also fill in the variable ```PROJECT_PATH``` which should be a string of the absolute path to the created dist directory for the app ```"<your path>/dist/my-store"```
5. Run ```ng serve --port 3000``` 
8. Go to ```localhost:3000```and enjoy the project!

