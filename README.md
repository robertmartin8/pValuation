<p align="center">
    <img width=80% src="https://github.com/robertmartin8/pValuation/blob/master/media/logo_v0.png">
</p>

<p align="center">
    <a href="https://www.python.org/">
        <img src="https://img.shields.io/badge/python-v3-brightgreen.svg"
            alt="python"></a> &nbsp;
    <a href="https://opensource.org/licenses/MIT">
        <img src="https://img.shields.io/badge/license-MIT-brightgreen.svg"
            alt="MIT license"></a> &nbsp;
</p>

<!-- content -->

pValuation represents my research into the area of "quantamental" finance – applying python and data science to augment traditional financial analysis.

In statistics, the *p*-value is often used to decide whether to accept or reject hypotheses, after conducting a statistical analysis. On the other hand, valuation is widely considered to be in the realm of "discretionary" analysis. This is because, despite valuation tools like DCFs being quantitative in nature, it is often much more of an art than a science when it comes to specifying the inputs. pValuation is my attempt to reconcile the two areas.

Some of my particular interests include:

- Financial model explainability
- Probabilistic programming to ensure that model output includes an uncertainty that reflects the uncertainty of the inputs
- The general use of data-driven techniques to estimate model inputs

## Currently implemented

- Option-implied price distributions
  - using the pricing of butterfl spreads to infer the probabilities of particular price movements
  - accompanying [blog post](https://reasonabledeviations.com/2020/10/01/option-implied-pdfs/)
- Market-implied expectations of COVID-19 using valuation surfaces
  - visualising the growth rates implied by the current S&P500 price
  - accompanying [blog post](https://reasonabledeviations.com/2020/03/25/coronavirus-equity-expectations/)
- Revenue forecasting models of DHT Holdings, an oil tanker company:
  - version 1 is a standard excel model, using the futures curve to estimate an upper bound on charter rates. See the [blog post](https://reasonabledeviations.com/2020/04/24/oil-storage/)
  - version 2 pulls charter data from the TankersInternational twitter feed

## What this project is not

This project is *not* meant to be a library of software that other people will find useful. To that end, I am not placing much emphasis on documentation and best-practices. This is a space for me to rapidly iterate and do some research into a pretty niche area. By all means, [reach out](https://reasonabledeviations.com/about/) to me if you have a question about it or want to discuss.
