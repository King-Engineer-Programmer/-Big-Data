# Big-Data
Amazon Video Game Reviews
For this assignment, you’ll use your knowledge of Spark and of how to write functions to determine the total number of video game reviews from each customer. You'll then filter the original Spark DataFrame to determine the number of 1-, 2-, 3-, 4-, and 5-star video game reviews from each customer.


Rename the Amazon_Video_Game_Reviews_starter_code.ipynb file to Amazon_Video_Game_Reviews_Assignment.ipynb.


Read the https://s3.amazonaws.com/amazon-reviews-pds/tsv/amazon_reviews_us_Video_Games_v1_00.tsv.gz file into a Spark DataFrame by using the provided code.


Import the necessary PySpark SQL functions.


Write a function, named customer_counts(), that creates a Spark DataFrame and that returns the number of video game reviews from each customer (customer_id), in descending order. The function must do the following:

Create a column that contains the number of reviews from each "customer_id".
Rename the "count" column to "customer_counts".
Sort the "customer_counts" column in descending order.



Pass the original DataFrame to the customer_counts() function.


Filter the original DataFrame to create five new DataFrames, one for each star rating.


Get the number of video game reviews from each customer for each filtered DataFrame by passing the filtered DataFrame to the customer_counts() function.


Download your Amazon_Video_Game_Reviews_Assignment.ipynb file and upload into your "Amazon_Video_Game_Reviews" GitHub repository.
