We implement Algorithm 5 from https://arxiv.org/pdf/2403.04630v1.pdf

* Running the code in `full_alg.ipynb` will generate the "zoomed in" plots (i.e., $50{,}000$ time steps) for $D = 300$ that were presented in the rebuttal.
 * In the code right before "Generate Stream", setting `block = True` and `deg_bd = 15_000` will make the block models described in the rebuttal.
 * Setting `deg_bd = 1_000` will make the plots for $D = 1{,}000$ shown in the rebuttal.
* We use $\varepsilon = 1$, $\delta = 10^{-10}$, $T = 10^6$, $\beta = 0.05$. 
 * These values can be changed immediately after the "Run Algorithm" header.