# email_marketing_system
<br>
An online retailer, “Universal Plus”, requested us to pitch to win a major contract with them to develop and deploy an e-mail marketing system.
Universal Plus aims to use direct e-mail marketing to reach out to their customers and increase sales.
Marketing decisions are critical to their success. Currently, their decisions about who to mail the
marketing promotions are mostly done through rules of thumb or randomly selecting their customers.
However, targeting uninterested customers costs to the company. In the past, some of their e-mail
marketing campaigns were not successful. Universal Plus would like to implement a direct marketing
system to identify their target group for the marketing campaign. With this system, they want to
predict which customers will visit the shop as a result of a direct e-mail campaign. This way, they can
target the right customers. Several other consultancy companies have been approached as well, and
the final decision on who will get the contract will largely depend on the outcome of a demonstration
of the approach to this problem based on a dataset that Universal Plus provided.
<br>
<br>
The dataset1
contains 64,000 customer records collected after an email marketing campaign. Please
check below for the description of the dataset.
<br>

## Data Dictionary
Universal Plus has randomly sent an e-mail marketing campaign to some of their customers. 
Some of their customers received a campaign on women's products, some received a campaign on men's products, and some did not receive an email campaign at all. 
They collected data for all of their customers (including the ones who have not received the campaign) during a period of two weeks following the e-mail campaign. 

The details for the dataset provided below.

2. Number of Instances: 64000 

3. Number of Attributes: 20

4. Attribute information:
	
  1) Customer_ID: Customer identification number
  2) recency: Months since last purhcase before the marketing campaign
  3) purchase_segment: Categorisation for the purhase amount in the past year before the marketing campaign
     Categories: 1) 0 - 100 : the purchase amount is between 0 and £100
                 2) 100 - 200: the purchase amount is between £100 and £200 
                 3) 200 - 350; 4) 350 - 500; 5) 500 - 750 6) 750 - 1,000 7) 1,000+
  
  4) purchase: Actual purchase in the past year before the marketing campaign
  5) mens: whether the customer purchased men's merchandise in the past year before the marketing campaign (1 = purchased, 0 = not)
  6) womens: whether the customer purchased women's merchandise in the past year before the marketing campaign (1= purchased, 0 = not)
  7) zip_area: categorisation of zip code as Urban, Suburban, or Rural
  8) new_customer: whether the customer is new in the past year or s/he is an existing customer (1 = new customer, 0 = existing customer)
  9) channel: categorisation of the channels the customer purchased from in the past year.
     The categories are Phone, Web and Multichannel 
  10) email_segment: e-mail campaign the customer received
     The categories are:
     Mens E-mail: The customer received an email marketing campaign for men's products
     Womens E-mail: The customer received an email marketing campaign for women's products
     No E-mail: The customer did not receive an email
  
  11) age: age of the customer in years
  12) dependent: whether the customer has a dependent or not (1 = yes; 0 = no)
  13) account: whether the customer has an account or not (1 = yes; 0 = no)
  14) employed: whether the customer has a permenant job (1 = yes; 0 = no)
  15) phone: whether the customer registered his/her phone or not (1 = yes; 0 = no)
  16) delivery: categorisation for the delivery address (1 = home; 2 = work; 3 = multiple)
  17) marriage: marital status (1=married, 2=single, 0 = others)
  18) payment_card: whether the customer registered a credit card for payment in the past year (1 = yes; 0 = no)
  19) spend: total amount spent in the following two weeks period

  20) visit: 1: the customer visited the shop in the following two weeks period; 0: the customer did not visit the shop in the following two weeks period.
