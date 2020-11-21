*Amazon_Vine_Analysis*

**Overview of the Analysis**

The purpose of our analysis was to import data about Amazon product reviews and to analyze the varability in customer reviews between Amazon's subscription service users and those who were not members. This analysis looked at a dataset of power tools from American Amazon users. 

After uploading the review to an RDS server I then extracted dataframes, constructing parallel dataframes for paid and unpaid customers using the .loc method like so: 



![screenshot](https://github.com/jamesdemott/Amazon_Vine_Analysis/blob/main/Challenge/Screen%20Shot%202020-11-21%20at%201.46.32%20PM.png)



**Results of the Analysis** 
______________________Total Review Counts______________________
The total number of paid reviews was 2,866
The total number of unpaid reviews was 506,459
____________________Total Five Star Reviews____________________
The total number of 5 star review for paid products was 1,475
The total number of 5 star review for unpaid products was 270,040
____________________Ratio of 5 Star Reviews_____________________
For paid product, the total percentage of 5 star reviews was 51.5%
For unpaid product, the total percentage of 5 star reviews was 53.3%

**Summary**
In summary there appears to be a slight bias from paid users to positively review products. 53.5% of paid reviews were five stars as opposed to 51.5% of five star reviews given by unpaid users. Obviously there are substantive bias problems. Including user selection (i.e. users are more likely to leave a 5 star review when they are thrilled with a product) as well as ease-of-use bias (i.e. paid users are more likely to leave 5 star reviews as these users are likely to be more familiar with the platform/more regular users). Further analysis should investigate negative reviews and whether any of these results are meaningfully significant or could inform further business development. 
