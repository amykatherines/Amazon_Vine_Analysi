# Analysis of Amazon Book Reviews

## Overview

For this analysis, the Amazon reviews for books were imported and analyzed to determine if paid/vine reviews were affecting the overall rating with a lot of 5-star reviews.  To do this, the data was imported into a dataframe on Google Colab using PySpark to manage the large amount of records. The dataset was first whittled down to only reviews that had 20 or more votes that it was a useful review.  From there, we looked at how many of the 5-star reviews were from paid/vine reviewers.  

## Results

Below are observations we made from our querying:

* The original dataset contained over 3 million reviews.  Only 2 of these reviews were vine reviews and 5 were unclassified:

![image_of_vine_vs_non-vine](images/imported_table_counts.PNG)


*  We wanted to look at only useful reviews so we whittled the list down to only those that had 20-or-more votes that it was useful:



*     The breakdown of 


After filtering the list down to only reviews that had 20 or more votes, we were working with about 400,000 records as you can see here:  From this 400k recordset, the following was determined:

![image_of_vine_vs_non-vine](images/total_helpful_reviews.PNG)

*  Within this subset, there were no vine reviews.  There were only 2 total vine reviews in the 3 million records so this was not a surprise:
![image_of_vine_vs_non-vine](images/percent_by_vine_type.PNG)


How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?
What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

