# Aggregate-Modeling-of-Pseudomonas
Repository containing code for an aggregate simulation of pseudomonas that captures both aggregate and cell-level behavior.  My contributions are combined with contributions of Michael J Sweeney and Sarah Sundius.

This project is a simulation written in Julia that models aggregate behavior of P. aeruginosa. Its purpose is to provide data to study aggregate behavior and investigate the relationship between growth rate and aggregate size. It is an IBM that captures cell-level behavior such as cell replication and cell death, as well as aggregate-level behavior such as diffusive aggreagation. It is meant to fill the hole in aggregate modeling left by simulations that only focus on biofilms or planktonic cells, and do not capture multiple levels of behavior.

There are 2 primary files in this project: 2D_AGGREGATES.ipynb contains the main Julia simulation. CONCENTRATION_GRADIENT.py contains a Python class used for simulating a chemical/environmental "layer" in the main simulation. It exists standalone as a diffusion simulation as well.

Dependencies include: Python, Julia, SQLite.
