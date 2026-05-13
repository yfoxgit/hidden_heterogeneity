# hidden_heterogeneity
This project analyses the potential for Causal Forests to reveal hidden heterogeneity.

Code is stored the Jupyter notebook 'analysis.ipynb'.

Motivation and results can be found in 'hidden_heterogeneity_report.pdf'.

(NB: This work was originally submitted as part of an assessment for the MPhil module D300.)

## Set-Up
To set up the repo, run the following commands.

Note these commands are for a Linux setup, assuming you have ```uv``` installed. Adjustments may be required for MacOS or Windows setups or different package managers.

1. Navigate to desired working directory
```shell
cd /path/to/wkd
```
2. Clone the repository from GitHub
```shell
git clone link-copied-from-GitHub
```
3. Navigate to the repository
```shell
cd /path/to/repo
```
4. Create the environment and install dependencies
```shell
uv sync
```
5. Activate the environment (hidden_heterogeneity)
```shell
source .venv/bin/activate
```
6. Open and run the notebook
Open the Jupyter notebook and run all cells.
7. Deactivate the environment
```shell
deactivate
```

## References
Below are the references relevant to the code analysis. A full list of references can be found in the project report.

- Chernozhukov, V., Hansen, C., Kallus, N., Spindler, M., and Syrgkanis, V. Applied Causal Inference Powered by ML and AI. Authors for Online Distribution, 2022. URL https://causalml-book.org. Version 0.1.2 22/03/2026. Accessed on 27/03/2026

- Cook, P. J. and Ludwig, J. The social costs of gun ownership. Journal of Public Economics, 90(1):379–391, 2006.
