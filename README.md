# Module-16-Challenge  Amazon_Vine_Analysis
![Vine_reviews](/Image/download.png)
# Overview of Project #
The purpose of this Project is to analyze Amazon reviews form paid Amazon Vine program to determine if there is any bias favorable reviews from Vine members.The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. We are using PySpark to perform the ETL process to extract the dataset focused on the US reviews for wireless products. 

The analysis consisted of the following:
1. Perform ETL on Amazon Wireless Product Reviews.
2. Determine Bias of Vine Reviews.

# Resources #
Software: JGoogle Colab Notebook, PostgreSQL 11.9, pgAdmin 4, AWS<br>
Data Sources: Amazon Wireless review datasets

# Results #
### How many Vine reviews and non-Vine reviews were there? ###
- Vine Reviews<br>
![Vine_reviews](/Image/Vine_reviews.png)
- Non-Vine Reviews<br>
![Non-Vine_reviews](/Image/Non-Vine_reviews.png)
### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars? ###
- Vine Reviews<br>
![Vine_reviews](/Image/five_star_paid.png)
- Non-Vine Reviews<br>
![Non-Vine_reviews](/Image/five_star_unpaid.png)
### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars? ###
- Vine Reviews<br>
![Vine_reviews](/Image/paid_five_star_percent.png)
- Non-Vine Reviews<br>
![Non-Vine_reviews](/Image/unpaid_five_star_percent.png)

# Summary #
From our analysis, we were able to conclude that the following:
1.After I had come up with my analysis there does not appear to be any sort of positivity bias because the percentages shown above are very similar at 38%. To conclude the analysis the vine program does not show any bias.

