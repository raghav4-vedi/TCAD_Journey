In this Repo I learn semiconductor device simulation using DEVSIM (TCAD).

1) `pn_junction.ipynb` solves the equilibrium Poisson equation for a 1D silicon p–n junction and plots the potential, electric field, charge density and carrier concentrations.

## Run

Tested with Python 3.11 on Linux. From this folder:

```bash
python3 -m venv .venv
source .venv/bin/activate
python -m pip install -r requirements.txt
python -m notebook pn_junction.ipynb
```

Select the Python 3 kernel and run the cells from the top. The virtual environment is local and is excluded from Git.
