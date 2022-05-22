# Machine Learning Project: How to predict the houses sales prices in Melbourne?  
---
### The project uses a dataset with information on home sales prices in Melbourne.  
### The objective of the project is to predict the selling price using the information obtained through the resources.   
---
#### The following treatment was done in the dataset:  
1. Dataset examples with missing values were discarded and examples that had a value of 0 in the Landsize column were suppressed.
2. As destination "y", the Price column was chosen, which is what you want to predict.
3. The columns chosen in the dataset as "X" features were: ['Rooms', 'Bathroom', 'Landsize', 'Lattitude', 'Longtitude'].
4. The dataset was divided into 4 parts for training and testing: X, X_test, y , y_test
5. The method chosen for the model was DecisionTreeRegressor, as it obtained the best result.
6. The other methods tested that obtained inferior results were the regressions: Linear, Ridge and Lasso  
---
### **Conclusion:**  
1. During the tests, I noticed that it was inconsistent that there are houses in Melbourne with bathrooms and bedrooms, but with a value of 0 in the Landsize column. For this reason I suppressed the examples that had this peculiarity.
2. This suppression brought a more satisfactory result for my first Machine Learning model.