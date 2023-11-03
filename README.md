# Smash Ultimate PGU Top Players Skill Estimation using MCMC sampling on Stan Model
Markov Chain Monte Carlo (MCMC) sampling on PyStan Bayesian Inference Engine to determine skill levels of the top PGU Smash Ultimate players.
  
## Recreating Environment
- Install Conda: https://conda.io/projects/conda/en/latest/user-guide/install/index.html
- Create Conda Environment: `conda create --name <env> --file environment.yml`
- Download Smash Database: https://github.com/smashdata/ThePlayerDatabase
- start `jupyter notebook` and run  `smash_ultimate_stanskill_project.ipynb` 
> you can adjust scale, number of iterations, number of chains

## Sources
Smash Database: https://github.com/smashdata/ThePlayerDatabase

Code is adapted from *CS 179: Algorithms for Probabilistic and Deterministic Graphical Models* taught by Professor Alexander Ihler (https://ics.uci.edu/~ihler/index.html)