---
layout: post
title:  "How to value a startup: Part-1"

---


Hi there 👋🏽

As I was reading about different ways to value a startup, I thought why not write about the same!

Part-1: Valuation based on EBITDA, Revenue, and growth.

Part-2: Convertible Notes and SAFE.

So let us get started!

---

Valuing companies (or be it anything) might seem difficult. Simply put, a startup is worth the present value of its future free cash flows.

Now, accurately forecasting the growth rate, operating margin, etc. over many years can be incredibly challenging (refer to the post “Numbers and Narratives” if you want to read more about this), hence many often rely on valuation multiples as a proxy for determining what a startup is worth. 

A **multiple** is a company value divided by a metric. 

Two common multiples for the public companies are **earnings multiple (P/E) and EBITDA multiples (Enterprise Value/EBITDA)**.

EBITDA stands for earnings before interest, taxes, depreciation, and amortization, is a measure of a company's overall financial performance and is used as an alternative to net income in some circumstances.

In the early stage startups, we usually use valuation based on revenue and growth, because the startups use most of the cash to grow revenue with less or no profit, which brings in revenue multiple.

(Just to add a quick relation, if you have 25x EBITDA and 40% margin, its equivalent to 25x*40% = 10x revenue)

Under this approach, we estimate/calculate the revenue of the startup and multiply it with a multiple. High growth and EBITDA margin can increase the value of this multiple (will cover this later).

Multiples are also used in DCF when we use multiple to estimate the terminal value after a couple of years.

For investors, one of the important metrics is the exit value, and a common value is usually 4x exit value considering around 5 years or 10x exit value considering around 8-10 years. (at 30% IRR)

To get these numbers, use X*(1+0.3)^N = 10X

The ends (like the possible exit values) can justify the means (a seemingly higher present-day valuation).

## Forward-looking
Let’s say the current revenue of the company is 5M$. Considering a multiple of 10x the valuation should be 50M$. However, if it’s a high-growth company with revenues estimated to be 10M$ in two years, then we might use a current multiple of 20x so that two-year forward-looking revenue multiple becomes 10x. Thus it would look like -

Valuation - $100M

Current(2021) - Revenue: $5M, Multiple: 20

After two years(2023) - Revenue: $10M, Multiple: 10

After five years(2025) - Revenue: $20M, Multiple: 5

In this case, we should note that there is no appreciation in value for the first two years, however might be recovered later.

## How growth rate pictures in?
Let us say that company A grows at 50% for the first two years while company B grows at 100% for the first two years. Both companies have $20M revenue in the current year and will trade at ~10x revenue upon exit.

In this case, company A would be worth $450M (10 * 45) and company B would be worth $800M (10 * 80) at the exit. Thus considering a 30% IRR, company A should be valued at ~13x ($260M) and company B should be valued at ~24x ($480M).

## How do margins picture in?
Eventually, the growth rate slows down and hence EBITDA comes in. Let us take the case of two companies again. Both companies have $20M revenue in the current year and will grow at the same rate (100% for the first two years) and trade at ~25x EBITDA upon exit.

However, company A has an EBITDA margin of 20% as compared to 40% for company B (for simplicity the number is the same for both years).

In this case, company B would have a higher valuation and thus a higher revenue multiple at entry.

## Growth-adjusted multiples (PEG)
If Company A (20% growth rate expected this year) trades at 8x forward revenue and company B (80% growth rate expected this year) trades at 24x then the growth adjusted multiple would make company A more expensive (PEG as 0.4x) as compared to company B (PEG as 0.3x).

## Rule of 40
The Rule of 40 states that a software company’s combined growth rate and profit margin should exceed 40% to balance the trade-off.

![image](https://user-images.githubusercontent.com/10815402/139591131-e5c213d8-4bdd-47f8-bd50-b6ec00f02700.png)

[Source](https://www.bain.com/insights/rule-of-40-infographic/)

## Mixed Methods
One of the common mixed approaches is to use DCF along with multiple for terminal value as mentioned above. This is also called The First Chicago Method or Venture Capital Method and consists of three cases - Best case scenario, base case, and the worst case. If the market is the winner takes it all, the worst-case might be a complete loss of capital.

The first step is to estimate cash flows considering revenues, margins, expenses, etc. for each case up to the assumed [divestment](https://en.wikipedia.org/wiki/Divestment#Divestment_for_financial_goals).

Next, to determine the terminal value at the exit, use the multiples discussed above, depending on the industry, etc.

Lastly, the cash flows and exit price are then discounted using the required return, and the probability-weighted average of the three cases gives us the valuation.
