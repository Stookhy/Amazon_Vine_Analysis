# Amazon_Vine_Analysis

## Overview of the Analysis

  1.  Define big data and describe the challenges associated with it.
  2.  Define Hadoop and name the main elements of its ecosystem.
  3.  Explain how MapReduce processes data.
  4.  Define Spark and explain how it processes data.
  5.  Describe how NLP collects and analyzes text data.
  6.  Explain how to use AWS Simple Storage Service (S3) and relational databases for basic cloud storage.
  7.  Complete an analysis of an Amazon customer review.

## Results

  How many Vine reviews and non-Vine reviews were there?
  
    There were a total of 145,431 Vine and non-Vine reviews.
  
  ![This is an image](https://github.com/Stookhy/Amazon_Vine_Analysis/blob/main/Resources/Vine%20&%20Non-Vine%20Reviews.png?raw=true)
  
  How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
  
    631 reviews for 5 star unpaid reviews
  
  ![This is an image](https://github.com/Stookhy/Amazon_Vine_Analysis/blob/main/Resources/5%20Star%20Reviews.png?raw=true)
  ![This is an image](https://github.com/Stookhy/Amazon_Vine_Analysis/blob/main/Resources/5%20Star%20Unpaid%20Reviews.png?raw=true)
  
  What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?
  
    37.4% of reviews relate to percentage of 5-star reviews for unpaid Vine program.
  
  ![This is an image](https://github.com/Stookhy/Amazon_Vine_Analysis/blob/main/Resources/5%20Star%20Percentage.png?raw=true)

## Summary

   The positivity bias that was potentially uncovered through the analysis identifies that the unpaid vine reviewers had significantly higher instances of 5-star review for products. In contrast, the paid vine reviewers had very low 5-star percentages.

   Given that the sample size was constricted to a degree that it was impossible to compare paid and unpaid Vine reviews, the analysis is biased towards unpaid Vine reviews. Another indicator of the bias is by comparing 37% of unpaid, 5-star Vine reviews to 0% paid, 5-star Vine reviews.

   The starting criteria of 20 likes or the 50% helpful criteria may have been too high, which made the initial data set too small. Adjustments to these criteria is a first step to reconsidering using this data set.
