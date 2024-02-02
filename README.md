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
First, I cleaned up the data by ensuring that the title names are consistent with each other. 
In cases where values are not given or indicated by the "-" sign, I filled them in with a zero, as 
the problem is a regression problem.

Secondly, I divided my dataset into testing, validation, and training batches. 
Using only the training batch, which comprises 60% of the data, I converted them into a pandas
dataframe. Furthermore, I inspected the dataset for inconsistencies, and I found long tails 
(as seen in the first image) that can cause confusion for the model. I made the necessary 
corrections to handle long tails by applying the log function to provide more detail into the 
dataset (as represented in image 2). This correction enhances the data so that elements unseen in 
the former data representation could now be uncovered and explored. I utilized the linear
regression algorithm to train the model on the training data and obtained weights to pass as 
weights for the test and validation sets.

Finally, to evaluate the model, I implemented the RMSE to give me the confidence level in the model, 
as opposed to relying on plotting diagrams each time.

Note: The training, testing, and validation were all done in isolation from each other.

## Conclusion
I was a able to achieve 80 percent accuracy in predicting price targets(image 3). With more feature engineer the prediction accuracy can
produce and increase in the accuracy of the model.

## Resources
[Kaggle](https://www.kaggle.com/datasets/CooperUnion/cardataset)

## Image References
image 1 ![long-tail](images/Longtail.png)
image 2 ![log_tail](images/Log_tail.png)
image 3 ![target](images/target.png)

## Author
[Burmau Garba](https://github.com/BURMAUG)

