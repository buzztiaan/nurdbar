# Nurdbar Manual

## Right Colom Actions:  
Press [ Tab ] till you see a cursor on the right side.

Enter your username or scan your barcode to [ login ].

If the bar changed to your name you are in.

After login you have 10 seconds to use one of the following functions:

### Casual
`````bash
# show balance
> balance

# deposit 10 euro
> deposit 10

# buy a product
> [scan the barcode of the product]

# buy another product
> [scan the barcode of the other product]
`````

### Advanced
`````bash
# add a user
> useradd foo

# withdraw 10 euro
> take 10

# add a product to the product-database
# yes, you have to type out the barcode
> productadd 0123456789 Name of the product

# sell 20 bottles of mate to the bar for 1.50 per piece
# yes, you have to type out the barcode
> sell 012345789 20 1.50
`````
