# Distance

## Outline (toc)

 * from Earl Becker 28/5/2014 -- model selection Buckland et al. (Intro. to Distance sampling, 2001) p68-71 Model Selection. See Burham and Anderson Book 1998
    1. Criteria for Robust Estimation (in ORDER of IMPORTANCE):
      a. Model Robustness - true for key + series expansion models (robust models will not have few P(y) < 0.20  Marques and Buckland)
      b. Pooling robustness - true for MCDS models when p(y=y')=1 for some y'  (usually y'=0)
      c. Shape Criteria - Detection function model should have a shoulder
      d. Estimator Efficiency - estimators with poor statistical efficiency (large varaince) should be ruled out, not at expense of a,b,c above.
    2. Likes AIC provides an adequate trade-off between bias and variance. (as model complexity increases: bias decreases and VAR increases). Burham and Anderson Book 1998 state the above result and restate as: tradeoff between overfitting and underfitting the data (p80)
      a. Prefers AIC over AICc (Program distance uses AICc)
      b. AICc is NOT necessarily better than AIC when the data are NOT Normally distributed
      c. May CONSIDER (p70 top) AICc when n < 20*q  (q=number of model parameters)
      d. real DS datasets: Laake Stake data - lowest AIC did well selecting a good model http://www4.ncsu.edu/~pollock/pdfs/ST506%20L4-08.pdf
      e. real DS dataaset: matchstick data lowest AIC did GREAT;     http://www.nscb.gov.ph/ncs/9thncs/papers/computing_Distance.pdf
      f. Golf Tee data = Lowest AIC w/ PI did well see p155 Adv. Distance Sampling
    3. Likelihood Ratio Test
      a. can only be used for nested models
      b. AIC == Likelihiid Ratio Test of size 15.7%
    4. Marques and Buckland 2003 paper on MCDS
      a. Uses estimated inclusion probabilities for Horvitz-THompson estimator
      b. p934 BIAS in the "H-T like Estimator" can be substatital when many of the inclusion probabilities are small
      c. a reasonable guide is that should be FEW inclision probabilities below 0.2 (p 934)
      d. in light of c) above, number or % observations with HT Prob < 0.2 is also a model criteria
      e. Marques Buckland Chapter 3 in Advanced Distance Sampling Refine this rule (p47) < 5% HT pi < 0.20, and NONE < 0.1
    5.  Goodness of Fit 
      a. Buckland et al. 2001 p. 71, it is fit around distance = 0 (for convential DS or MCDS model - EB) that is most Important
      b. Poor GOF model MAY not be reason for great concern - fit about aApex is Important (EB interpretation)

 

 

