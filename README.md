# AlphabetSoup

### Challenge Overview
Use machine learning and neural networks to create binary classifiers that can predict if an applicant will be successful if funded by Alphabet Soup.

### Objectives
- Import, analyze, clean, and preprocess a “real-world” classification dataset.
- Select, design, and train a binary classification model of your choosing.
- Optimize model training and input data to achieve desired model performance.

### Analysis

In this analysis I used two hidden layers with 86 nodes in the first layer and 14 nodes in the second layer. I picked these values by multiplying the number of neurons by 2 and then for the second layer using the number of categories in our model. After this I began editing the number of nodes and adding additional layers. Through many rounds of trial and error I was able to get the model from an accurancy score of .23 to .53. While I'm not sure why I couldnt get it to the goal of 75% accuracy, I manipulated both the bucketing of categories, the nodes in layers and the total amount of layers, but still was never able to get it above 0.53 and a loss under 0.69. 

If I was able to implement a different model to solve this classification problem I would use SVM. I would use Support Vector Machine because of its ability to be less likely to overfit models as well as its ability to deal with binary classification issues. 
