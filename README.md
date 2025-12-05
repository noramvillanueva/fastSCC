# fastSCC: Efficient and Scalable Clustering of Survival Curves

**fastSCC** is a new method based on log-rank test to efficiently identify and cluster survival curves. This method eliminates the need for computationally expensive resampling, sifnificantly reducing processing time while maintaining statistical reliability. By systematically evaluating survival curves and determining opti-
mal clusters, the proposed method ensures a practical and scalable alternative
for large-scale survival data analysis.

## R code for illustrative examples 

```r
library(clustcurv)
library(survival)
```

You can find the scripts with the illustrative examples in the app folder

## Citation

If you use fastSCC in your research, please cite the following papers

> Villanueva, N.M., Sestelo, M., Meira-Machado, L.: Efficient and scalable clustering of survival curves. arXiv (2025)

> Villanueva, N.M., Sestelo, M., Meira-Machado, L., Roca-Pardiñas, J.: clustcurv: An r package for determining groups in multiple curves. The R Journal 13, 164 (2021)

> Villanueva, N. M., & Sestelo, M. (2025). clustcurv: Determining groups in multiple curves (Version 3.0.0) [R package]. https://CRAN.R-project.org/package=clustcurv

```bibtex
@article{fastSCCvillanueva,
author = {Villanueva, Nora M. and Sestelo, Marta and Meira-Machado, Luis},
doi = {},
issn = {},
journal = {arXiv},
number = {},
pages = {},
title = {{Efficient and scalable clustering of survival curves}},
url = {},
volume = {},
year = {2025}
}
```
