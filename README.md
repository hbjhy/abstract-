# abstract-
The purpose of the project was to estimate the Value-at-Risk (VaR) of a portfolio consisting of
four financial instruments based on two GARCH-family models. We first created a portfolio
and checked the basic properties of a time series of this portfolio. Then we focused on finding
the best model from the GARCH family. Finally, we estimated the VaR of the portfolio. We
started by downloading a dataset of daily observations of SP&500, DAX, WIG20 and BTC.
The chosen period was 2009/01/01 – 2022/05/31. We built a portfolio consisting of the above
four instruments. We also calculated the log returns of every instrument as well as the returns
for equally weighted portfolios (EWP). We estimated Value-at-Risk for both the in-sample and
out-of-sample periods for the equally weighted portfolio we had set. The forecasts seem to be
quite good. Apparently, the model AR(1)GARCH(2,1) that we chose was the correct one. The
results we got – the losses of the portfolio higher than VaR at 1,17% in the in-sample period
and 1,36% in the out-of-sample period – confirm that the estimation was accurate. The
conclusion we have reached is that the peaks-over-threshold model that is used for measuring
VaR is not suitable for capturing the volatility clustering that occurs on the Montenegrin stock
market and that it should be improved, despite the fact that it is accurate in terms of correctly
exceeding its thresholds. In this article, we discovered that ARMA(1,2)-TS GARCH(1,1)
model with Student-t residual distribution, ARMA(1,2)-T GARCH(1,1) model with Student-t
residual distribution, and the ARMA(1,2)–EGARCH(1,1) model with a Student-t distribution
of residuals all fit the data better than the other models. Parameterised JSU distribution of
residuals passed the joint Christoffersen test with a 95% confidence level.
