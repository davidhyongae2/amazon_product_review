## Overview of the analysis
Using a relational database and AWS S3 data to extract, convert, and filter into a downloadable format for analysis. <br>
Python3, PySpark3, and Pandas to create an AWS relational database.  <br> 

## Resources
- Program language: Python, PyStarks, RDS, EC2, S3



## Results 
#### Deliverable 1, a simple table illustrating customer IDs and counts using Amazon RDS.
<br> ![Figure 1a](https://github.com/davidhyongae2/Amazon_product_review/blob/main/Figure1a.png) <br>

1. A simple table illustrating product IDs and titles using Amazon RDS.
<br> ![Figure 1b](https://github.com/davidhyongae2/Amazon_product_review/blob/main/Figure1b.png) <br>

2. A simple table illustrating review IDs and customer IDs, product IDs, and product parents, using Amazon RDS.
<br> ![Figure 1c](https://github.com/davidhyongae2/Amazon_product_review/blob/main/Figure1c.png) <br>

3. A simple table illustrating vine IDs and review IDs, star ratings, helpful votes, total votes, vine, and verified purchases, using Amazon RDS.
<br> ![Figure 1d](https://github.com/davidhyongae2/Amazon_product_review/blob/main/Figure1d.png) <br>

4. Connection to the RDS through the sqlworkbench/j
<br> ![Figure 1e](https://github.com/davidhyongae2/Amazon_product_review/blob/main/connected1.png) <br>

<br> ![Figure 1f](https://github.com/davidhyongae2/Amazon_product_review/blob/main/1f.png) <br>




#### Deliverable 2, using PySpark to perform vine analysis 
<br> ![Figure 2a](https://github.com/davidhyongae2/Amazon_product_review/blob/main/Figure2a.png) <br>

<br> ![Figure 2b](https://github.com/davidhyongae2/Amazon_product_review/blob/main/Figure2b.png) <br>

#### Deliverable 3, using PySpark to perform vine analysis <br> 
How many Vine reviews and non-Vine reviews were there?
<br> 4781 vine reviews, 332395 non-vine reviews <br>
How many Vine reviews were five stars? How many non-Vine reviews were five stars?
<br> 1604 are five stars of 4781, 168800 are five stars of 332395 <br>
What percentage of Vine reviews were five stars? What percentage of non-vine reviews were five stars?
<br> 33.5% vine reviews, 51% non-vine reviews <br>

<br> ![Figure 3](https://github.com/davidhyongae2/Amazon_product_review/blob/main/Figure3.png) <br>


## Summary
1. A bias was identified within the non-Vine group, indicating a positive tendency toward individuals who do not participate in the Vine program.
2. There may be a limited understanding or engagement with the program among these individuals.

## Reference 
UC Berkeley Coding Bootcamp (2022). Amazon Vine analysis example [Courseware]. Codingbootcamp.berkeley.edu
