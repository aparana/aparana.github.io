---
layout: post
title:  "Day 21: Weighted average anti-dilution"
tags: 100DaysFromStartups

---

In the previous post, we had touched upon Full-ratchet anti-dilution. In this post, we will talk about a strategy that is more friendly to the founders: weighted average adjustment.

In this case, the number of shares issued at the lower price is considered in the calculation of the new price of the funding round.
The formula used is -

NCP = OCP * ( (CSO + CSP) / (CSO + CSAP))

NCP = new conversion price

OCP = old conversion price

CSO = common shares outstanding immediately prior to the new issue

CSP = common share purchased if the round was not a down round

CSAP = common shares actually purchased because the round is down

For comparison, let us take the same example as before (Day 20). The company had 1M shares at a price of $10 per share. Now if you issue a 1M share in series A at a price of $10 representing an investment of $10M, then the investor will hold 50% of the company. Post this round, the company gets a new investor who offers to invest $5,000,000 at $9 per share.

Using the formula above, the new conversion price would be $10*(2M+5M/10)/(2M+5M/9) = $9.78
Thus the series A investor now holds 1,022,222 as compared to 1,111,111 shares calculated using the full-ratchet.

Hence this approach is much more friendly to the founders as compared to the full-ratchet, as it takes into account the number of shares issued in the new round.
