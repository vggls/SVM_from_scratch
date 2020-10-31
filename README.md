# Support_Vector_Machines_-under_construction-
- In "summary.pdf" we consider the case of overlapping data and give a short math summary of the steps that lead to the computation of the "optimal margin linear boundary" 
  and the "optimal margin kernelized boundary".
- In "svm.ipynb" we build a the "smo" function which reproduces the Sequential Minimal Optimization algorithm and computes the support vectors for optimal margin boundaries.
  Based on the arguments we pass we either get the support vectors of a hyperplane (for a "penalty" hyperparameter C of our choice) or the support vectors of a kernelized 
  boundary (for kernel hyperparameters of our choice) by making use of the Kernel Trick.
  The file also contains the "boundary" function which is the resulting boundary.
- In "classifiers.ipynb" we compare the support vector classifiers based on a real dataset.
