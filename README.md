This is an example e-commerce site with good ol' HTML, CSS and Snipcart.  Though there are better alternatives for developers or the less cost-conscious, the simplicity of this package is still relevant.  Following the steps provided, for many development sites the annual costs will only be for your domain ($15+/yr) paid to your DNS provider.

To download - click on the "CODE" button above, then "DOWNLOAD ZIP"

OR

Create a GitHub account (it is suggested for many deployments) then "FORK" this repository.  You can make all your edits within GitHub by clicking the pencil icon that will appear.

## To customize this package:

### Files to Edit

1) /css/default.css - font and colour values
2) /img - place your logo in PNG format here - save as logo.png
3) /products/index.html - the "shop" page with Snipcart integration
4) blank.html - a blank template page
5) index.html - the homepage
6) landing-2.html - full screen image example homepage
7) /privacy/index.html - privacy policy blank page

Notes:

* to change the colour of the browser window - edit the "theme-color" meta at the top of each page

* after adding product images in the img folder, change occurances of:

data-item-image="https://dummyimage.com/640x640/fff/aaa"

to:

data-item-image="../img/products/yourimage.jpg"

### Snipcart Setup

To use this template you will need to create a Snipcart account (free).  You do not need to enter your credit card details if only accepting in-person payments.

1) Complete steps 1 & 2 in the Snipcart dashboard (Fill in your business information, configure your domains)
2) Configure the payment gateway (Deferred Payments) by clicking on the account profile icon on the top right
3) At the bottom of the page, turn Deferred Payments to ON, then click 'CONFIGURE' - choose - 'Only allow deferred payments'
4) Click on TAXES in the menu and CREATE NEW TAX - enter your details (e.g HST, CA, ON, 0.13)
5) Click on Domains & URLs - the domain you put here MUST MATCH the location of the products folder - if it doesn't, YOUR CART WILL NOT WORK
6) Go to API KEYS - COPY your PUBLIC TEST API KEY (the test key is all you will ever need if accepting in-person payments).  Look at the index file /products/index.html - at the bottom of the page, over-write the key that is already there by pasting the one you copied.

### Deployment

The simplicity of this site allows for a very wide range of deployments.  For a method that uses GitHub and Netlify, click on the icon under deploy here:

https://majordomo.consulting/training/

