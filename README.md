The Spam Email detection

prepare.ipynb 
- explore the dataset i.e. emails, their length, most frequently occurred words
- preprocess the dataset
- split the data into train, validation and test sets
- save them in .csv files

train.ipynb
- vectroize the emails using TF-IDF Vectorization
- train the models on the training set
    - Multinomial Naive Bayes
    - Logistic Regression
    - Decision Tree Classifier
    - Random forest Classifier
    - Support Vector Classifier
- score and evaluate these models on validation set
- The 3 benchmark models on validation set are
    - Logistic Regression
    - Random Forest Classifer
    - Support Vector Classifier
- Train these benchmark models on train and validation combined
- Score and evaluate them on test set
