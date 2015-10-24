---
title       : corrStock
subtitle    : The only stock correlator you need
author      : rasnes
job         : 
framework   : io2012        # {io2012, html5slides, shower, dzslides, ...}
highlighter : highlight.js  # {highlight.js, prettify, highlight}
hitheme     : tomorrow      # 
widgets     : []            # {mathjax, quiz, bootstrap}
mode        : selfcontained # {standalone, draft}
knit        : slidify::knit2slides
github:
    user: rasnes
    repo: corrStock_pres
---

## What is corrStock?

corrStock is a simple, intuitive and straight forward app for calculating the correlation between *any* stocks or ETFs in the US stock market.

Example corrStock calculation:

The correlation between SPY and QQQ, for the last 100 trading days, is


```
## [1] 0.931469
```

---

## Correlation - why should we care?

- For most private long term investors a diversified portfolio is the aim, as it mitigates risk (both systemic and individual).
- Correlation is a simple, yet powerful tool for analyzing the systemic risk of your portfolio.
    - A high correlation (close to 1) between stocks indicates that if one of those stocks rise/fall, the other one is likely to also rise/fall over the same time period.
    - A low correlation (close to 0) indicates that the movements of one of the stocks does not necessarily say anything about the movements of the other stocks (which might be a good thing, at least if the investor is risk averse).
    - A negative correlation (less than zero) indicates that the stocks move in the opposite direction, i.e. if one goes up, the other is likely to go down, and vice versa. This might be the case for bonds and stocks, e.g. SPY and TLT.

**CONCLUSION:** any long term investor that cares about risks should check out and be conscient about the correlation between the stocks in his/her portfolio, to evaluate whether the portfolio is likely to be within his/her desired systemic risk level.

---

## Why corrStock?


Because

- corrStock is simple and elegant
- corrStock is fast
- corrStock has an intuitive and graphical UI
- Last, but not least: corrStock will help you on your way to create the perfect portfolio!

---

## Contact and information

Contact me on github if you are interested in partnering up or continue developing the corrStock app (please fork me!), or investing som of that beautiful angel money you have in this very promising app.

Thank you for your interest!




