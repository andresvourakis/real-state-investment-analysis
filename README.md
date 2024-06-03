Gmaug Real State Investment Opportunity Analysis
======

## Objective
Help Gmaug figure out **where to invest** in this booming market by **identifying "undervalued" properties** that he can buy, spruce up and sell for a profit.

## Approach
After performing EDA and learning more about the data and which features could be useful in determining similarities between houses, the following techniques were applied with the goal of identifying "undervalued" properties:
1. Heuristic (First Iteration Complete)
2. K-prototype (WIP)
3. K-mean (WIP)
4. Regression (WIP)

The Heuristic approach provided the first set of meaningful results. The idea was to use this as a baseline and find other methods that could provide more accurate results but due to time constraints, the other approaches weren't able to be explored fully.

## Key Findings

Through the Heuristic approach, I was able to find 8,280 houses that are considered undervalued (their selling price was about 40% of the average price of similar houses sold in the current market).

These houses were selected as undervalued because if bought for their "old" sale price and sold for their "new" sale price, the ROI would be at least 150% (more than double the investment). This means that even accounting for remodeling costs (and other expenses), there is still enough room to make a profit.

**Where to invest?** Roughly 20% of the undervalued houses can be found in the area "Gap of Rohan", therefore it is recommended as a good start where one can start investing.

## Next Steps

1. Current evaluation of results was done manually, therefore it would be recommended to define a more robust/scalable evaluation method.
2. Find a way to calculate the margin of error of the current model.
3. Continue optimizing the clustering and regression models and then compare their results to heuristic approach. These approaches are considered more scalable.
