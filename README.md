# **Amazon_Vine_Analysis**

## **Overview of the analysis:**
### **Purpose**
In this project, we need to analyze Amazon reviews which have been written by members of a paid Amazon Vine program. This program is a service which allows manufacturers and publishers to receive reviews of their products. There are many companies, for instance , SellBy, who pay a small fee to Amazon and provides products to Amazon Vine members , who are then required to publish a review . 

Here, we present an analysis of the data set , chosen from 50 available datasets. This data set contains review of furniture products on Amazon.

To perform the analysis , here we used **pySpark** to determine if there is any bias towards favorable reviews from Vine members for the given data set.Here we need to find out if having a paid Vine review impacted the percentage of 5-star reviews in terms of positivity. This means we need to determine whether there are more paid 5 star reviews from Vine members as compared to 5 star reviews from non-Vine members.


## **Results:**

- How many Vine reviews and non-Vine reviews were there?

  ![](https://github.com/kirtibhandari/Amazon_Vine_Analysis/blob/main/Resources/Vine_Non-Vine.png)

  As per the analysis results, there are **136** Vine reviews and **18019** non-Vine reviews.

- How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

  ![](https://github.com/kirtibhandari/Amazon_Vine_Analysis/blob/main/Resources/5-Star_Vine_Non-Vine.png)

  As per the analysis results, there are **74** 5-star Vine reviews and **8482** 5-star non-Vine reviews.

- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars? 
  
  ![](https://github.com/kirtibhandari/Amazon_Vine_Analysis/blob/main/Resources/percentage_5-Star_Vine_Non-Vine.png)

  As per the analysis results, there are **54.41%** Vine reviews and **47.07%** non-Vine reviews.

## **Summary:**
 <!-- In your summary, state if there is any positivity bias for reviews in the Vine program. Use the results of your analysis to support your statement. Then, provide one additional analysis that you could do with the dataset to support your statement. -->

As we clearly see from the screenshots above, under the results section that there are 74 Vine members' 5 star reviews written out of total 136 reviews from Vine members. There are 8482 non-Vine members' 5-Star reviews out of total 18019 non-Vine members' reviews. We see that there is more percentage,  of 5-star rating by Vine members, i.e. 54.41%, as compared to non-Vine members, which is 47.07%.

Also we present an additional analysis to confirm the above statement.

We calculated percentage Star rating for all the Stars such as 1 star, 2 star , 3 star and 4 star. We, then plotted a graph as shown below for the Vine and non Vine members for the percent star rating .

![](https://github.com/kirtibhandari/Amazon_Vine_Analysis/blob/main/Resources/additional_analysis.png)

 The graph clearly depicts that the Vine members were biased towards positive reviews as compared to non-Vine members, where there were not at all 1-Star reviews from Vine members as compared to non-Vine members.
