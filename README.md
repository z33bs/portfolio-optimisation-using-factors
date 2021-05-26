# Portfolio Optimisation Using Factors
*Part of the Udacity nanodegree - AI for Trading*


Workings in jupyter notebook `portfolio_optimisation.ipynb`

Workflow:
* Build statistical risk model using PCA with 20 factor exposures
* Use the risk model to predict portfolio risk on an equal weighted portfolio
* Generate five alpha factors: momentum, overnight sentiment (+smoothed), and mean-reversion (+smoothed)
* Evaluate factors with: factor return, quantiles, turnover analysis and sharpe-ratios
* Combine alphas into a single alpha-vector
* Build three versions of the optimal porfolio using a common set of 5 groups of constraints
  *   Weights that maximise alpha (results in a highly concentrated portfolio)
  *   A regularised version of the above that penalises high turnover (results in more diversification)
  *   One that minimises tracking error from the ideal alpha-maximising porfolio weights (this one resulted in the most diversified porfolio and also had the lowest net-risk-factor exposures)
