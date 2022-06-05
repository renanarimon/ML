# Machine Learning
### data science & AI

## -------------------------------------------------------------------------------------
## NOTE: if the Jupiter Notebook Not Rendering,</br> click here: https://nbviewer.org/ and enter the URL there
## -------------------------------------------------------------------------------------

* clean data
* vizualization
* Classification models<br>

## notebooks:
### fashion Mnist
One of the most famous datasets is Mnist-Fashion which contains about 1000,70 black and white images the size of
28 * 28 or 784 pixels.<br> 
A deep learning network convolution can get an accuracy of over 99% in this data but it is very complex to get high accuracies in other methods.<br>
![image](https://user-images.githubusercontent.com/77155986/147161958-08175281-bcc5-4cb3-93f0-d66cfcf293cc.png)

### cats vs dogs
a dataset containing 25,000 images<br>
Of dogs and cats, classify dog/cat by image.<br>
![image](https://user-images.githubusercontent.com/77155986/147162331-0eb961a9-f172-4730-9cd7-1e3ca45fcc2b.png)
![image](https://user-images.githubusercontent.com/77155986/147162340-ec9b8ae8-e90a-4862-920e-c48d9bf83878.png)

### hand movements
The purpose of the work is to classify three different situations in the way people communicate with each other. 
* Spontaneous (autonomous) situation in which two people move their hands freely in front of each other.
* synchronous movement in which the two people move their hands together.<br>
* movement in position Own. Where only one side moves the hands.<br>
![image](https://user-images.githubusercontent.com/77155986/147162440-e0118248-b7b0-4d58-a2b0-7bca17976d39.png)

### Heart disease
Improving a project from a previous semester by using better models<br>
![image](https://user-images.githubusercontent.com/77155986/147162564-31df8fd3-c013-4a2a-b6a4-7a32f3af11fc.png)<br>



In this project, the main methods I have used is:
1.	**Scale**: standardize the dataset by standard-scaler.
2.	**PCA**: dimensionality reduction.<br>
            my goal was to reach the best accuracy with lowest number of components, so I have tried to get the best balance between both.
3.	**GridSearch**: find best parameters in each model (using cross-validation).
4.	**pipeline**: scaling, pca, and fit model.
5.	**Ensamble learning models**: <br>
*	Logistic regression
*	KNN 
*	Random forest
*	XGBoost
*	Gradient Boost
*	Voting
*	Stacking<br>

Models I used but didn’t perform well, so isn’t in the notebooks:
*	Ada Boost
*	K-means<br>

### NOTE: Neuron networks should not be implemented in this project
