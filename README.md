

### Admin
### django default
------------------


### core models 

Province
- Name 

City 
- @Province 
- Name

  
platform/Status

### user
mobile
name 
uid
province@core
city@core
job
created_at 
updated_at 


### shopping-cart
@user
@products 
amount
created_at
updated_at 

### webpage 
reference-card@card
theme 
links
addresses
debit-card-number for payments
tiktime-links


### cards
@user  
type  
color  
text
designs 
links
image gallery
active features 
is_active 
expiry_date 
expire_date 





###  orders 
@user
@product 
payment_id
price
discount 

### log
@user 
@orders
created_at 


### discount-codes
@product or cart
percent 
usage 
log
created_at
updated_at


### social link
@card 
label 
core@platform -- status
url 
location 



### site config 
@card 
@user 
page name 
color 
theme mode 
images 
banner
@social link


