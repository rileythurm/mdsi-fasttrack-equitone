# mdsi-fasttrack-equitone
Riley Thurm, 2022.

This JavaScript was written to handle the client's (Metal Design Systems, Inc.) ordering interface for Equitone facades.
View functionality at https://www.mdsi.co/fasttrack-equitone.

I worked with a web designer to add special calculations and page behavior for the ordering process of Equitone sheets, a special type of building facade. The script handles all the calculations for sheet count and necessary accessories, as well as much of the webpage animation.





Below are the html field ids that I added to the web designer's page to connect my JavaScript.

Constant product detail ids:
linea-price
linea-thickness
linea-height
linea-width
tectiva-price
cf-horiz-rail-price
cf-clip-price
alum-zee-ext-price
alum-hat-ext-price
tuf-s-concealed-fastener-price

Input ids:
sqft-${finish}-${tab}
width-${finish}-${tab}
height-${finish}-${tab}
perim-edges-${finish}-${tab}
toggle-horizontal-${finish}-${tab}
toggle-vertical-${finish}-${tab}

Output ids:
panels-per-sheet-${finish}-${tab}
sheets-recc-${finish}-${tab}
yieldloss-${finish}-${tab}
price-${finish}-${tab} specific panel profile price
price-${finish} total price for this finish
sheets-input-${finish}
cf-horiz-rail-qty
cf-horiz-rail-total
cf-clip-qty
cf-clip-total
alum-zee-ext-qty
alum-zee-ext-total
alum-hat-ext-qty
alum-hat-ext-total
cmr-${finish}-qty // cmr = color matching rivets
cms-${finish}-total // cms = color matching screws
tuf-s-concealed-fastener-qty
tuf-s-concealed-fastener-total
red-stop-sleeve-qty, total, price
foamstrip-roll-qty, total, price
luko-sealant-qty...
screw-sleeves-qty...
linea-milling-tool-qty, price, display-name, total

error-insufficient-material-FINISH

grand-total
grand-total-form-input

checkout-pane-1 (through 4)
checkout-label-1 (through 4)

