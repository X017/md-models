


### core models

Province
- Name 

City 
- @Province 
- Name

Job
- Name

Platform 
- Status

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
- @user
- lable 
- type  -- model 
- color  -- model 
- text
- designs 
- links -- slug 
- image gallery -- model 
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


Order 
- @user
- @product
- uid
- payment_id
- price
- discount
- status
- address
- is_paid
- card_number

Discount-codes // Not Implemented Yet
- @product
- percent 
- usage
- uid
- log
- created_at
- updated_at

Card-Features 
- @card 
- label 
- core@platform -- status
- url
- location 


Site config 
- @card 
- @user 
- page name 
- theme mode 
- images 
- banner
- @Card-Features


#####################################
admin 
- User 
- Create - READ - Update - DELETE
-- Cards 
----Webpage 
-- Orders


- Card
- Create - READ - Update - DELETE
-- USER 
-- Design 
-- Links 
-- Active features
-- Images 

- Order 
- Create - READ - Update - DELETE
-- User 
-- Product 
-- Shopping Cart 


- Social Links
-- User 
-- Card 
-- Platform

- Site Config 
-- User 
-- Banner 
-- Image Gallery 
-- Platform Link
-- Theme 


- Discount Codes 
-- CRUD 
-- Products 
-- Carts 
-- Usage 
-- Amount 


ui/ux 
### 
- User 
-- Login 
-- OTP 
-- Profile 

- Card Order 
-> Choose a type of the card
-> Choose the color of the card 
-> Enter your receiver information 
-> Redirect to Payment Website 
-> Show Payment Status its a sucessful/failure payment 
-> redirect to the homepage button 


