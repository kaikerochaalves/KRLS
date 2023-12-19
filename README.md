# KRLS (kernel recursive least squares)

The kernel recursive least squares (KRLS) is a model proposed by Engel et al. [1] based on the recursive least squares (RLS) algorithm, that implements the Gaussian kernel to cope with linearities in the data.

- [KRLS](https://github.com/kaikerochaalves/KRLS/blob/93e415b9f336b2d524809fd1d1e9a72a28b7ea94/Model/KRLS.py) is the KRLS model.

- [GridSearch_AllDatasets](https://github.com/kaikerochaalves/KRLS/blob/93e415b9f336b2d524809fd1d1e9a72a28b7ea94/GridSearch_AllDatasets.py) is the file to perform a grid search for all datasets and store the best hyper-parameters.

- [Runtime_AllDatasets](https://github.com/kaikerochaalves/KRLS/blob/93e415b9f336b2d524809fd1d1e9a72a28b7ea94/Runtime_AllDatasets.py) perform 30 simulations for each dataset and compute the mean runtime and the standard deviation.

- [MackeyGlass](https://github.com/kaikerochaalves/KRLS/blob/93e415b9f336b2d524809fd1d1e9a72a28b7ea94/MackeyGlass.py) is the script to prepare the Mackey-Glass time series, perform simulations, compute the results and plot the graphics. 

- [Nonlinear](https://github.com/kaikerochaalves/KRLS/blob/93e415b9f336b2d524809fd1d1e9a72a28b7ea94/Nonlinear.py) is the script to prepare the nonlinear dynamic system identification time series, perform simulations, compute the results and plot the graphics. 

- [LorenzAttractor](https://github.com/kaikerochaalves/KRLS/blob/93e415b9f336b2d524809fd1d1e9a72a28b7ea94/LorenzAttractor.py) is the script to prepare the Lorenz Attractor time series, perform simulations, compute the results and plot the graphics. 

[1] Engel, S. Mannor, R. Meir, The kernel recursive least-squares algorithm, IEEE Transactions on Signal Processing 52 (8) (2004) 2275–2285. 
https://doi.org/10.1109/tsp.2004.830985
