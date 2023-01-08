# Meta-Learning-Assignment-2023

In this assignment, perform the following:

a) in-depth exploratory data analysis:

Analysis of the features (are the features Categorical, Ordinal or Continous?) 
    
    1) The features are continuous as each datapoint represents a ECG signal wave
    
Finding any relations or trends considering multiple features
     Adding any new features or removing redundant features
    Converting features into suitable form for modelling 
    
    2) For finding relations and trends PCA analysis was perforned on the data, details of which are present in the notebook
       Features were scaled using StandardScaler from sklearn library

b) Based on the observations in (a) implment a model to predict if a person is suffering from an arrhythmia using ECG signals. You can implement different classifiers on the data and compare the accuracy score for each.

    3) Deep learning model was employed for the classification task
    
c) Consider metric scores used to evaluate performance on test data and suggest and use the one best fitted for this situation.

    4) As the dataset contained imbalanced classes, confusion matrix was used for determining the performance of the model 
    
d) How can you improve the performance of this pipeline? Implement one such technique specific dataset preprocessing and one on the classifier.

    5) Inorder to handle the imbalance, majority and the minority classes were upsampled to an equal amount. Upsampling was achieved by ampliyfying and 
       stretching the ecg signals to generate new datapoints 
       
[Hint: Look at the frequency of each class] 
