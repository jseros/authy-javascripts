# Authy integration javascripts

This javascripts are optional but help you quickly add authy to your
site and look great.

There are core functionalities: 

1. Token input. The javascript adds the authy logo to the field.
2. Authy help toggle. A simple javascript toggle that you can add
   anywere to explain what authy is.
3. Client-sice cellphone  verifier.
4. Country code dropdown with flags and autocomplete.



## Installation

  git clone git://github.com/authy/authy-javascripts.git

## Usage

open example.html in chrome, safari or internet explorer.  

This example shows how to use it.   
Add form.authy.min.js, form.authy.css and images to your site.  

Use the #id to add the functionality to the fields you want.  

`id="authy-token"`: For the token input during login  
`id="authy-help"`: A help tooltip you can use on login or register  
`id="authy-cellphone"`: When asking for user cellphone during  
registreation/  
`id="authy-countries"`: Optional country dropdown during registration  


### More…

You can fine the full API documentation in the [official documentation](https://docs.authy.com) page.



