---
layout: post
title:  "Numbers and Narratives"
tags: finance

---

Hi there 👋🏽

This post is basically a summary of my recent learnings from the lecture “Numbers and Narratives” by Aswath Damodaran1.

The article uses DCF coupled with a narrative to basically value anything.

> Discounted cash flow (DCF) is a valuation method used to estimate the value of an investment based on its expected future cash flows. DCF analysis attempts to figure out the value of an investment today, based on projections of how much money it will generate in the future.2

So if you are familiar with DCF already, this will help you to add a narrative to your valuation!

---

The article/lecture talks about 6 major steps that are involved to basically value anything -

## Step 1: Understand the landscape/company
This involves understanding what the company does, the market, competitors, etc.

For this post, we will refer to the example of Ferrari (from Aswath’s examples).

## Step 2: Develop a narrative
This narrative will help you assume growth rate, operating margin, etc. for the future years. It is basically a story about the future of the company, for example -

> Ferrari will stay an exclusive auto club, deriving its allure from its scarcity and the fact that only a few own Ferraris. By staying exclusive, the company gets three benefits: 1. It can continue to charge nose bleed prices for its cars and sell them with little or no advertising. 2. It does not need to invest in new assembly plants, since it does not plan to ramp up production. 3. It sells only to the super rich, who are unaffected by overall economic conditions or market crises3

## Step 3: Check the narrative
Check the narrative against history, economic first principles & common sense.

Some of the first principles examples are -

For a mature company, the terminal return on capital would almost be the same as the cost of capital.

The operating margin is likely going to decline considering the increased competition for a mature company again, whereas for a startup the narrative might be that the operating margin will increase as it moves toward profitability.

Similarly, for startups, the growth rate might increase over years as compared to mature companies where the growth rate might remain constant/decrease.
![image](https://user-images.githubusercontent.com/10815402/139591527-88d3f14b-70ab-458a-8cc2-bca4b8a4a7d1.png)

Examples of the common-sense checks -

Terminal revenue or the revenue at the 10/15 years should not exceed the market capitalization of the company.

Compare the terminal revenue with the current revenue of the largest player in the market.

The terminal growth rate of the company cannot be more than the growth rate of the economy

## Step 4: Connect your narrative to key drivers of value
Plugin the numbers for your DCF calculation based on your narrative.
![image](https://user-images.githubusercontent.com/10815402/139591519-2b4690de-be36-4210-89d2-9f4e77a36095.png)


## Step 5: Value the company
Now, this is an important part. Once you have your assumptions ready, you can get your cashflows. Few things to note -

Cost of capital4 can be either calculated as the opportunity cost (so as an investor what are you giving up to invest in the company) or as a weighted average cost of capital (referred to as WACC).

Cost of Capital = Weight of Equity * Cost of Equity + Weight of Debt * After-tax cost of Debt

Since the distribution of equity and debt along with the cost of debt is readily available, the remaining cost of equity is calculated as -

Cost of Equity Capital = Risk-Free Rate + Beta times Equity Risk Premium

In case the cost of debt is not available, the rating given by agencies can be used to estimate the same. If possible, the market value of the debt should be used.

Prof Aswath recommends that the R&D cost should be capitalized and not expensed (thus should be considered as an asset and written off in parts in the future). The same applies to operating leases.

For the terminal value, the Dividend discount model5 can be used.

![image](https://user-images.githubusercontent.com/10815402/139591508-cf8ee46e-87f9-4166-989c-2dd34cc678a8.png)

To get the excel format, [click here](http://pages.stern.nyu.edu/~adamodar/New_Home_Page/spreadsh.htm#ginzumodels)


## Step 6: Keep the feedback loop
As the company goes through new quarters and changes (political, macro-economic) occur, you may want to revisit the narrative and change the numbers if needed.

That’s it for today!

Disclaimer: In no way, this post justifies this video out there, so if you have ~1.5 hours of time, do go and check it out -
<iframe width="728" height="410" src="https://www.youtube.com/embed/MN1RU9i3ngg" title="YouTube video player" frameborder="0" allow="accelerometer; autoplay; clipboard-write; encrypted-media; gyroscope; picture-in-picture" allowfullscreen></iframe>
