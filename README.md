# Amazon_Vine_Analysis

# Overview of the analysis: Explain the purpose of this analysis.
Since your work with Jennifer on the SellBy project was so successful, you’ve been tasked with another, larger project: analyzing Amazon reviews written by members of the paid Amazon Vine program. The Amazon Vine program is a service that allows manufacturers and publishers to receive reviews for their products. Companies like SellBy pay a small fee to Amazon and provide products to Amazon Vine members, who are then required to publish a review.

In this project, we have access to approximately 50 datasets. Each one contains reviews of a specific product, from clothing apparel to wireless products. We chose wireless products and use PySpark to perform the ETL process to extract the dataset, transform the data, connect to an AWS RDS instance, and load the transformed data into pgAdmin. Next, we use PySpark, Pandas, or SQL to determine if there is any bias toward favorable reviews from Vine members in your datasetT.

# Results:

Total reviews 65581

![image](https://user-images.githubusercontent.com/83035801/135769579-fde32c06-45a8-448a-955a-53c9e7fe7057.png)

Vine reviews 613
non-Vine reviews 64968
![image](https://user-images.githubusercontent.com/83035801/135770352-ca6d1457-e055-424d-9a6f-0669f5f8a57c.png)


# Summary: In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement.

I dont believe there is any bias for reviews, seeing how paid and unpaid reviews were both fairly close to each other. Also showing how many vine reviews verses nonvine reviews. 
