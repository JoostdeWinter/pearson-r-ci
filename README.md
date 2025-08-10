# Pearson r — Confidence Intervals

[**Live tool**](https://joostdewinter.github.io/pearson-r-ci/)  
![views](https://hits.sh/joostdewinter.github.io/pearson-r-ci.svg?label=views)

Interactive tool to compute two-sided confidence intervals for Pearson’s *r*.

- **Primary method:** numerically inverts the sampling distribution of *R* with a plug-in ρ = r (Gauss–Legendre quadrature), following the exact sampling distribution described by **Hotelling (1953)**.  
- **Secondary:** Fisher z approximation (shown smaller, for comparison).

## Usage
Open the live page, enter **r**, **N**, and the **confidence level**, then click **Compute**.  
Example: `r = 0.42`, `N = 80`, `95%` → CI ≈ **[0.2232, 0.5875]**.

## Notes
- The visible counter above shows total page views (hits.sh, free).  
- No cookies, no server; runs entirely client-side.

## How to cite this tool
De Winter, J. C. F. (2025). Pearson r — confidence intervals [Web application]. https://joostdewinter.github.io/pearson-r-ci/

## Contact
Joost de Winter, j.c.f.dewinter@tudelft.nl

## References
Hotelling, H. (1953). New light on the correlation coefficient and its transforms. Journal of the Royal Statistical Society. Series B (Methodological), 15(2), 193-232.

De Winter, J. C. F., Gosling, S. D., & Potter, J. (2016). Comparing the Pearson and Spearman correlation coefficients across distributions and sample sizes: A tutorial using simulations and empirical data. Psychological Methods, 21, 273–290. https://doi.org/10.1037/met0000079
