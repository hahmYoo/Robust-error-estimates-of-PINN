This GitHub repository supports the results presented in the paper "Robust error estimates for PINN in one-dimensional boundary value problems of linear elliptic equations".
In the paper, we have proven that the error in PINN for linear elliptic equations can be bounded by the loss multiplied by a certain coefficient. The coefficient in the inequality becomes smaller as k and c increases. From the numerical experiments, it was observed not only that this was true, but also that the inequality is sharp.
Due to this ratio-decreasing effect, even though the coefficients increase in the linear elliptic equation, the final error when PINN is applied remains stable once the coefficients reach a ceratin value, which is contrary to intuition.

Each file represents a numerical experiment described in this paper, and it is possible to replicate the experiments by running the code in order.
