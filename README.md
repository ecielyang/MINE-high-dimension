# Estimating mutual information on high dimensional data using MINE
**Motivation**: when testing MINE on my own data, I found that MINE gives totally different results (both in value and relative value) resulting from different lr and different hidden size of NN. Since there is no discussion on how to select hyperparameters on the paper, this notebook aim to work on following questions: 

1. Generate synthetic data with different dim
2. Run different MINE to compare their results with true MI to test whether the relative relationship holds 
3. On different dim, select lr and hidden state
4. How big is dim so that MINE does not work on relative relationships?
5. Does MINE works on entropy calculation?

**Take aways**
1. 
