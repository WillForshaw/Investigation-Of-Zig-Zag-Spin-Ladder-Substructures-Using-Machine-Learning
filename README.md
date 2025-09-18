# Investigation-Of-Zig-Zag-Spin-Ladder-Substructures-Using-Machine-Learning
Simulations + ML for frustrated magnetism in zig-zag spin ladders. Python computes m(B) via a 4×4 transfer-matrix Ising model, sweeps J3/J2 and field, exports a phase-diagram dataset (Gridmatrix.csv). An ML module featurises structures and trains a classifier to find zig-zag ladders from crystallographic/topology data (ToposPro/pymatgen + sklearn).
# Zig-Zag Ising Ladder: Magnetisation + ML (WIP)

Python code to compute magnetisation curves via a 4×4 transfer matrix and export `Gridmatrix.csv` for a phase diagram; plus a notebook with an ML classifier on curve features.

Unfortunately my structure files can't be uploaded to github as there are too many, but if you want to use this code, .cif files are avaliable for free on numerous websites, topospro software was used to process all of the structures and return only ones that have a high chance of containing the desired topology. Topospro is also free. 

