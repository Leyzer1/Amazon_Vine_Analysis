# Amazon_Vine_Analysis

# Overview 

In this anaylysis we are asked to analyze Amazon reviews written by members who pay for Amazon Vine Program. I decided to focus on the Amazon reviews that were related to Automotive. The main tools used for this challenge were Google Colabs, Amazon AWS services, PostgressSQL, and PySpark. With these tools I was able to extract transform and load data to analyze the vine reviews and determine if there is any posivite bias. 

# Results

- How many Vine reviews and non-Vine reviews were there?

There were a total of 24,824 reviews. From those only 82 were Vine reviews, and 24,742 were non-Vine reviews. 

![Vine Review Count](https://user-images.githubusercontent.com/95899763/165024838-6b5a0f3b-4a46-4735-afd6-eac1122d184f.PNG)


- How many Vine reviews were 5 starts? How many non-Vine reviews were 5 stars?

There were a total of 12,840 5-star reviews. From those only 33 were 5-star Vine reviews, and 12,807 were 5 -star non-Vine reviews. 

![5-Star Review count](https://user-images.githubusercontent.com/95899763/165024882-218659c3-422e-471c-980a-3364581cd0d1.PNG)


- What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

40.2% of all paid reviews are 5-star reviews, and 51.8% of all unpaid reviews are 5-star reviews. 

![Percentage of 5-Star Reviews](https://user-images.githubusercontent.com/95899763/165024925-cda8611e-486d-4d91-b788-fa1b923ce6c2.PNG)


# Summary 

From the results above we can say that there is a posite bias for unpaid non-vine reviews. It is interesting to note that the sample size for between Vine review and non-Vine review is significantly large. 
