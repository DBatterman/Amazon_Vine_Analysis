# Amazon_Vine_Analysis

## Overview of Analysis

The purpose of this project is to preform an analysis on Amazon reviews for a fictional company. The company wants to see whether or not there is any favorable bias in the Vine reviews; a paid review service that Amazon hires people for. We will use first use PySpark to perform an ETL on a collection of music reviews from Amazon. Then, we will continue to use PySpark to look at the number or Vine and non-Vine reviews, the number of five star reivews for Vine and non-Vine reviews, and the percentage of five star reviews for Vine and non-Vine reviews.

## Results

###### How many Vine reviews and non-Vine reviews were there?

There were seven Vine reviews and 96798 non-Vine reviews for this particular section of Amazon music reviews.

###### How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

In total there were 0 five star Vine reviews, and 61784 five star non-Vine reviews.

###### What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

For Vine reviews, the percentage of five star reviews is 0%. The non-Vine reviews have a total of roughly 63.83% five star reviews.

## Summary

The DataFrame for the Vine reviews of this section is so small that we can view it in its entirety right here:

![image](https://user-images.githubusercontent.com/98666269/170917404-641861cc-83fd-4da8-ac02-8a8818a0423a.png)

Because there are zero five star reviews, I would be hesitant to call it an overwhelming favorable bias in the Vine reviews. However, all of the reviews are either three stars or four stars. Those are average to good reviews when rating things out of five, so personally I don't feel comfortable with this small sample size saying there is absolutely no possible bias. I would suggest additional analysis on the amount of three and four star reviews to see if bias exists in that range compared to the non-Vine reviews of this particular dataset.
