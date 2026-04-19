# itchyshin r-universe

This repository tells [r-universe.dev](https://r-universe.dev) which R
packages to include in the [itchyshin.r-universe.dev](https://itchyshin.r-universe.dev) universe.

## Current packages

- [**pigauto**](https://github.com/itchyshin/pigauto) — phylogenetic
  trait imputation via a gated ensemble of BM + GNN.

## How to use

Install from r-universe:

```r
install.packages("pigauto",
                 repos = c("https://itchyshin.r-universe.dev",
                           "https://cran.r-project.org"))
```

Documentation site: <https://itchyshin.r-universe.dev/pigauto>.

## Adding more packages

Edit `packages.json` and open a PR. r-universe picks up changes
within ~30 minutes of merge.
