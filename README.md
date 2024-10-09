# GD_and_BCGD_optimization
This work was done as homework for an optimization course.

Collaborators: F. Boldrini, C. Colanero, G. Sanguin

We want to analyze different methods to approach semisupervised learning as an optimization problem. That is, we are going to study which one among the Gradient Descent, the Block Coordinates Gradient Descent with randomized rule and the Block Coordinates Gradient Descent with Gauss- Southwell rule is the most efficient in terms of time and accuracy.

We started creating a synthetic dataset for our case study and we then passed to a real world dataset to verify that our methods did function correctly. Our goal is to minimize a specific loss function and classify some unlabeled points with binary classification given a small set of labeled samples.

The repository includes the following files:

a README.md file
a toy_dataset.ipynb file for a test on a toy dataset
a data_banknote_authentication.txt file as a real world dataset
a data_banknote_authentication.ipynb file for the test on the new datase
