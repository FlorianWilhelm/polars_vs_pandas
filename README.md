# Polars vs Pandas

Comparing [Polars] to [Pandas] and a small introduction.

# Installation

In order to set up the necessary environment:

1. review and uncomment what you need in `environment.yml` and create an environment `polars` with the help of [conda]:
   ```
   conda env create -f environment.yml
   ```
2. activate the new environment with:
   ```
   conda activate polars
   ```
3. call `jupyter lab` to start the [Jupyter] environment and open the [pl_vs_pd notebook](pl_vs_pd.ipynb).

[conda]: https://docs.conda.io/
[Jupyter]: https://jupyter.org/
[Polars]: https://pola-rs.github.io/polars-book/user-guide/index.html
[Pandas]: https://pandas.pydata.org/
