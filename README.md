[![DOI](https://zenodo.org/badge/813064699.svg)](https://zenodo.org/doi/10.5281/zenodo.11549707)

# Identifying the threshold to sustainable ridepooling

This contains supplementary data to reproduce the figures in the article **Identifying the threshold to sustainable ridepooling** by Charlotte Lotze, Philip Marszal, and Felix Jung, Debsankha Manik, Marc Timme, and Malte Schröder.

The data points are kept in CSV format in the [`data`](./data/) directory, in files named `fig_<figure number><panel id>.csv`.
To read them, use for example [Python](https://www.python.org/) in conjunction with the [pandas](https://pandas.pydata.org/) library:

```python
import pandas as pd

pd.read_csv("data/fig_2a.csv")
```

or any text editor.

If you have any questions, contact Felix Jung at [felix.jung@tu-dresden.de](mailto:felix.jung@tu-dresden.de).
