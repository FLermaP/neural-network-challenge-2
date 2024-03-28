# neural-network-challenge-2
## In this challenge Multi-Branch Neural Networks where used to try to predict in certain company the Attrition by Department ( 2 targets : Attrition and Department ) 
### The tools/Libraries used where :
- [Pandas](https://pandas.pydata.org/)
- [NumPy](https://numpy.org/)
- *From TensorFlow:*
  - [Model](https://www.tensorflow.org/api_docs/python/tf/keras/Model)
  - [Layers](https://www.tensorflow.org/api_docs/python/tf/keras/Layers)
- *From scikit-learn:*
  - [train_test_split](https://scikit-learn.org/stable/modules/generated/sklearn.model_selection.train_test_split.html)
  - [StandardScaler](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.StandardScaler.html)
  - [OnehotEncoder](https://scikit-learn.org/stable/modules/generated/sklearn.preprocessing.OneHotEncoder.html)
- Edx provided csv file

### Process
1. Import Libraries
2. Load csv file
3. Review the data ( data types and values )
4. Create dataframes for target data (y) and for non-target data (X)
5. Split the data in train and test datasets
6. Scale all of the X data
7. Encode the new dataframes
8. Create the Model's core layers (input layer and 2-3 additional layers)
9. Create the branched layers
10. Compile the model
11. Train/Fit the model with the training data
12. Evaluate the model with the test data

### Results
With 2 core shared layers the accuracy achieved was:
- Department Accuracy : 0.573369562625885
- Attrition Accuracy : 0.633152186870575

By adding a 3rd core layer accuracy achieved was:
- Department Accuracy : 0.592391312122345
- Attrition Accuracy : 0.8288043737411499

### Optional
Additional nodes, and/or layers can be added to the core to improve all scores or to a specific branch to improve those scores
