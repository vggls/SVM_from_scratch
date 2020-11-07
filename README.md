# Support_Vector_Machines_-under_construction-
- In "summary.pdf" we consider the case of overlapping data and give a short math summary of the steps that lead to the computation of the "optimal margin linear boundary" 
  and the "optimal margin kernelized boundary".
- In "smo_class.ipynb" we build a class which reproduces the Sequential Minimal Optimization algorithm and computes the support vectors for optimal margin boundaries.
  Based on the arguments we pass we either get the support vectors of a hyperplane (for a "penalty" hyperparameter C of our choice) or the support vectors of a kernelized 
  boundary (for kernel hyperparameters of our choice) by making use of the Kernel Trick.
- In "classifiers.ipynb" we compare the support vector classifiers based on a real dataset.
