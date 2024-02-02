# Car Price Prediction
## Tech Stack
* Python
* Numpy
* Seaborn
* Pandas
* Jupyter Notebook
## Introduction 
This problem is a prominent problem from Kaggle. Kaggle provided a dataset that is dirty or unsuitable.
Problem solvers are to clean the data and from various inferences make a predictions of what a car price would be 
in the market.
## My Methods
First, I cleaned the data up by making sure the title names are consistent with each other. Then in cases where values are 
not given or values are indicated by the "-" sign I filled it in with a zero as the problem is a Regression problem.

Secondly, I divided my dataset into testing, validation and training batches. Using only the training batch which has 60% 
of the data I converted them in to a pandas dataframe. Furthermore, I inspected the dataset for inconsistencies to which I found 
long tails that can cause the model confusion. I made the need correction to handle long tails. 
## Conclusion

## Resources
* Kaggle