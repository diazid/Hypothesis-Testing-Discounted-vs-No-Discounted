# Hypothesis Testing: Discount vs No Discount

by Israel Diaz

---

## Description

The purpose of this project is Northwind Traders, Inc. to process and analyze their internal API data on customer sales. The specific tasks will be: 

1. Convert their internal API results into a MySQL Database and 
2. Formally answer the following question using hypothesis testing: 

    Do discounted products sell in higher quantities than non-discounted products?

They have provided a .json with the raw data.

---
 
## EDA

![png](img/quantity_vs_is_discounted.png)

It is clear that the means are different

I performed the T-test to determine if this difference is statistically significant.

---

## Hypothesis Testing

I set the following hypothesis.

Null Hypothesis: **There is no significant difference in the sell quantity between the products with or without discount.**

Alternate Hypothesis: **There is a significant difference in the sell quantities between products with and without discount.**

The Test resulted in this statistical outcome:

* p-value=0.0015422405
* Significant: True

Because the p-value is lower than the alpha value (0.05), then we **Reject** the Null Hypothesis of **There is no significant difference in the sell quantity between the products with or without discount.**, Then ***There is a significant difference in the sell quantities between products with and without discount.***

---

## Summary

As we have some intuitive certainty about that there would be significant difference in the quantity of product that are sold with a sort of discount and those that not, in this case, for this specific data (population), that difference is significant according to the Test performed in this project.

That is, product with discount are sold more (statistically speaking) that those that don't have any discount.

---

Updated 04/27/2023
