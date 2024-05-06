# mica-water

Data and DP models for simulating muscovite mica-water interfaces

This repository contains the training data and input files needed to train a DP interatomic potential for the muscovite mica-water interface. The DP was constucted using the Deep Potential method, as implemented in the DeepMD-kit package. Energies and forces were evaluated using the SCAN functional within the plane-wave pseudopotential scheme implemented in the Quatum-Espresso package. For more information on the DP training and the Deep potential molecular dynamics simulations (DPMD) please see the reference cited at the end of this document. 

Within this repository you will find:

raw: The raw data files used to train the DP model;

train: The input files for DeepMD-kit;

DP_models: The frozen DP models that can be used to run DPMD simulations.

If you use this training data, please read and cite: Abhinav S. Raman and Annabella Selloni, Submitted, 2024
