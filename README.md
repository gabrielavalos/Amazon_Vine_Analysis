# Amazon_Vine_Analysis
# Overview:
The following report analyzes Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

This project uses the Amazon pet products dataset to evaluate bias toward favorable reviews from Vine members.

Tools:

PySpark 3.1.1
pgAdmin 4.29 and PostgreSQL
Amazon RDS (AWS Console)
Amazon pet products dataset

# Results:
There were 1457 paid reviews and 94563 non-paid reviews
<br>
![](https://github.com/gabrielavalos/Amazon_Vine_Analysis/blob/main/images/five_star_reviews.png)

There were 647 paid reviews with 5-star rating and 44461 unpaid reviews with 5-star rating
![](https://github.com/gabrielavalos/Amazon_Vine_Analysis/blob/main/images/five_star_reviews.png)

44% of paid reviews had a 5-star rating; 47% of unpaid reviews had a 5-star rating
![](https://github.com/gabrielavalos/Amazon_Vine_Analysis/blob/main/images/percentage.png)

# Summary: 
There is no positivity bias for reviews in the Vine program, as non-paid reviews received more 5-star ratings. 
