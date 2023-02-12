# Data Analyst Associate Case Study Submission
# Company Background
PetMind is a nationwide pet product retailer in the United States. With inflation hitting 41-year highs, the company is planning to reduce the cost of customer retention by improving brand loyalty. The first strategy is to launch a monthly pet box subscription in three months. The marketing team is preparing a list of popular products for the pet box subscription. The chief marketing officer wants to know whether the list should only include the products being purchased more than once.

# Data Validation
Before I procceded with my analysis, I ensured I perfomed thorough data validation and data wrangling to the dataset that was provided to me, my results are well explained below:

The original data consist of 879 rows and 9 columns, namely; 'product_id','product_category', 'sale', 'price', 'vendor_id', 'pet_size', 'pet_type', 'rating', 'rebuy'.

I checked through the entire columns,
- I observed no null values,neither were there any duplicated rows
- The 'sales' column was already converted into float type from the spreadsheet before importing into Datacamp's workspace, it was then converted to int type.
- The 'price' column was not altered.
- I removed rows that contained 'rabbit' and 'hamster' from the 'pet_type' column, in accordance to the data set description.A total of 46 rows were removed, leaving 833 rows.
- I replaced the values 1 and 0 with 'More than once' and 'Once' respectively in the 're-buy' column for better understanding.

These are the info on the remianing column and rows;

- There are 11 unique product categories.
- Ratings ranged between 1 and 10, all being within the expected range.
- There are a total of 833 distinct vendors' id
- There are 11 unique product categories.
- There are 4 unique pet type.
- There are 5 unique pet size.
- The rebuy option contains 'More than once' and 'Once'.

# Summary
The innovation behind the Pet box subscription is a great one and is highhly commended, however, my recommendation to The chief marketing officer based on the question asked "whether the list should only include the products being purchased more than once.", are as follow:

- Products that were purchased just once should be included in the pet box subscription as they generate more revenue in sales
- The company should also focus on priotizing top selling product categories across all pet type
- Lastly, products that were below the rating of 4 should be carefully reviewed or discontinued, so as to continue to improve customers services
