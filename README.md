## Flask Application Design for a Website Landing Page for Computer Sales

### HTML Files

1. **index.html**: This will serve as the landing page for the website and will contain the main content and call-to-actions.
2. **product-detail.html**: This will display the details of a specific computer product, including specifications, price, and purchase options.

### Routes

1. **@app.route('/')**: This route will be associated with the `index.html` file and will display the landing page.
2. **@app.route('/product/<product_id>')**: This route will accept a product ID as a parameter and display the details of that product by loading the `product-detail.html` file with the appropriate data.
3. **@app.route('/purchase/<product_id>')**: This route will handle the purchase process for a specific product and will redirect the user to a payment gateway or checkout page.