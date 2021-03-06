# Spark-MLP-Higgs
The notebook provides using multilayer perceptron for analayzing Higgs Dataset via Spark. The notebook could be executed on IBM Watson. 
Higgs dataset is used as a benchmark to test Machine Learning algorithms performance on the task of identifying nuclear collisions that produce the HIGGS boson versus background process.

The data set consists of 11 Million Monte Carlo simulations of nuclear collisions. Signal collisions correspond to collisions where a Higgs boson was created. Background collisions correspond to collisions that have the same end product particles but where a Higgs boson was not created. Each collision has 28 attributes. 

We have used startified Sampling for create groups of data and reduce computation time.

Data set location: [https://archive.ics.uci.edu/ml/datasets/HIGGS]


Relevant Paper: Baldi, P., P. Sadowski, and D. Whiteson. “Searching for Exotic Particles in High-energy Physics with Deep Learning.” Nature Communications 5 (July 2, 2014)
