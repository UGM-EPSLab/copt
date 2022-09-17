# Capacity Outage Probability Table (COPT) Maker

Fast Capacity Outage Probability Table (COPT) generator powered by `NumPy`.

## App in Binder

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/yasirroni/copt/HEAD?urlpath=voila%2Frender%2Fnotebooks%2Fapp.ipynb)

## Notebook in Colab

[![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/yasirroni/copt/blob/main/notebooks/app.ipynb)

## Feature

1. Calculate Loss of Load Probability (LOLP).

1. Calculate Expected Energy Not Served (EENS).

1. Calculate Load Shedding Cost.

## Contributing

1. We use [`nb-clean`](https://github.com/srstevenson/nb-clean) to clean notebooks metadata.

    ```shell
    pip install nb-clean
    nb-clean add-filter --preserve-cell-outputs
    ```
