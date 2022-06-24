[PCA - Relative Value Trading](https://github.com/uditgt/Projects/blob/main/PCA%20-%20Relative%20Value%20Trading/PCA%20-%20Relative%20Value%20Trading.ipynb)
* This is a PCA driven (unsupervised) model, which uses PCA to derive latent/state variables signifying structural movements to the interest rates at various term points along the yield curve. By using the top 3 PCA, we are in essense able to separate Noise from Signal. This can be used to build a relative value trading strategy - which is market neutral and earns alpha solely from the mispricing implied by mean-reverting noise. Or determine opportunate entry point in the market.
* Relative value changing over time for the 10yr term point
<p align="center">
  <img width="600" height="300" src="https://github.com/uditgt/Projects/blob/main/PCA%20-%20Relative%20Value%20Trading/rv_10yrterm.png">
</p>

* Relative value across term structure to build market-neutral portfolio, while taking advantage of mispricings
<p align="center">
  <img width="600" height="300" src="https://github.com/uditgt/Projects/blob/main/PCA%20-%20Relative%20Value%20Trading/rv_across_term_points.png">
</p>
