This github file is made to support the results made in the paper "Robust error estimates for PINN in one-dimensional boundary value problems of linear elliptic equations".
In the paper, we have proven the error in PINN for linear elliptic equations can be bounded by the loss multiplied with a certain coefficient. The coefficient in the inequality is defined to get smaller as k and c increases. Doing numerical experiments, it was observed not only that this was true but also that the inequality is sharp.
By this ratio decreasing effect, even though the coefficients increase in the linear elliptic equation, the final error when PINN is applied stays stable after the coefficients reach a ceratin value which is different from intuition.

Each of the files represent one numerical experiment in the paper and it is possible to replicate the experiment by running the code in order.
