Gmaug Real State Investment Opportunity Analysis
======

## Summary
A non-technical summary of the entire analysis (including the results and recommendations) can be found [here](https://www.canva.com/design/DAGHEBAGt_4/pafVvY5jN2ot-SeVX_dmJA/view?utm_content=DAGHEBAGt_4&utm_campaign=designshare&utm_medium=link&utm_source=editor)

## Objective
Help Gmaug figure out where to invest in this booming market by **identifying "undervalued" properties** which he can buy, spruce up and sell for a profit.

## Approach
After performing EDA and learning more about the data and which features could be useful in determining similarities between houses, the following techniques were applied with the goal of identifying "undervalued" properties:
1. Heuristic (Finished)
2. K-prototype (WIP)
3. K-mean (WIP)
4. Regression (WIP)

The Heuristic approach provided the first set of meaninful results. The idea was to use this as a baseline and find other methods that could provide more accurate results but due to time constraints the other appraoches werent able to be explored fully.

## Key Findings

Through the Heuristic approach, I was able to find 8,280 houses which are considered undervalued (their selling price was about 40% of the average price of similar house sold in the current market).

These houses were selected as undervalued because if bought for their "old" sale price and sold for their "new" sale price, the ROI would be 150% (more than double the investment). This means that even accounting for remodeling cost (and other expenses), there is still enough room to make a profit.

**Where to invest?** Roughly 20% of the undervalued houses can be found in the area "Gap of Rohan".

## Next Steps

1. Improve regression model and then compare results to heuristic approach
2. Improve evaluation
3. Calculate margnin of error
