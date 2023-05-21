# Optimizing-E-commerce-Sales-Price-Recommendation-using-Machine-Learning-Techniques

Mercari wants us to build an algorithm that automatically suggests the right product prices from the user-inputted text descriptions of their products, including details like product category name, brand name, item condition, etc.

Business objectives and constraints

• The goal is to solve the problem of suggesting the appropriate price of products to online sellers.

• No latency constraints, because we would like to suggest a highly accurate price to the seller, even if it takes a reasonable amount of time.

The files consist of a list of product listings. These files are tab-delimited.

• train_id or test_id - the id of the listing

• name - the title of the listing.

• item_condition_id - the condition of the items provided by the seller

• category_name - category of the listing

• brand_name

• price - the price that the item was sold for. This is the target variable that you will predict. The unit is USD. This column doesn't exist in test.tsv since that is what you will predict.

• shipping - 1 if shipping fee is paid by buyer and 0 by seller

• item_description - the full description of the item.

Dataset Link :- https://www.kaggle.com/c/mercari-price-suggestion-challenge
