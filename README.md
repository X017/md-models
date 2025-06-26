


### core models

Province
- Name 

City 
- @Province 
- Name

Job
- Name
  
platform/Status
### accounts 
User

- mobile 
- name 
- uid
- province@core
- city@core
- @job
- created_at 
- updated_at 

### 
Cards
- user  
- type  
- color  
- text
- designs 
- links
- image gallery
- active features
- uid
- is_active 
- expiry_date 
- expire_date 


Shopping-cart
- @user
- @products 
- amount
- created_at
- updated_at 

Webpage 
- reference-card@card
- theme 
- links
- addresses
- debit-card-number for payments
- tiktime-links

Orders 
- @user
- @product
- uid
- payment_id
- price
- discount 

Log
- @user 
- @orders
- uid
- created_at 


Discount-codes
- @product or cart
- percent 
- usage
- uid
- log
- created_at
- updated_at

Social link
- @card 
- label 
- core@platform -- status
- url 
- location 

Site config 
- @card 
- @user 
- page name 
- color 
- theme mode 
- images 
- banner
- @social link


