# Online Linearized LASSO
###About our algorithm
Sparse regression has been a popular approach to perform variable selection and enhance the prediction accuracy and interpretability of the resulting statistical model. Existing approaches focus on offline regularized regression, while the online scenario has rarely been studied. We propose a novel online sparse linear regression framework for analyzing streaming data when data points arrive sequentially. Our proposed method is memory efficient and requires less stringent restricted strong convexity assumptions. \\
Theoretically,  we show that with a properly chosen regularization parameter, the $\ell_2$-error of our estimator decays to zero at the optimal order of $\widetilde O({\sqrt{s/t}})$,where $s$ is the sparsity level, $t$ is the streaming sample size, and $\widetilde O(\cdot)$ hides  logarithmic terms. Numerical experiments demonstrate the practical efficiency of our algorithm.

###About our code
We post three experiment files in this github repository. Independent.ipynb and Topelitz.ipynb are the experiments in independent settings and corelated settings, respectively. initial_batch.ipynb shows the experiment results when initial batch size is extremely samll. We also upload two experiment data record, which can be used  to plot the results directly.
