---
title: Analysis of Variance
weight: 15
chapter: true
---
# Analysis of Variance

To begin our foray into statistics in R, we will start with the most basic and useful analysis, **Analysis of Variance (ANOVA)**. An ANOVA is used to test the effect of 1 or more categorical explanatory variables (X) on a continuous response variable (Y). The ANOVA tests the difference between the factors variance (distance from the grand mean) compared to the error variance. The variance for each point is squared and added together to generate the sum of squares, which is then used to generate the F ratio. The F ratio is then compared to a critical value from a table of values (based of degrees of freedom) to determine the level of significance, or P value.   

In these tutorials, we will be using a variety of datasets to test each analysis. These will be specified within a "instruction" block before the requisite code chunk.  

### Content:
{{%children description="true"   %}}