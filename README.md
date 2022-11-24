# Credit-Risk-Modeling-Using-Machine-Learning
Predicting the probability of default of that a potential borrower will default on a prospective loan over the next 12 months. Data mining financial statement data containing more than one million firm years by augmenting macroeconomic variables.

Prerequisite : Kindly install imbalanced-learn
Eg. conda install -c conda-forge imbalanced-learn

To get predictions on a dataset please use the test_harness() function:

Eg. predicted_probabilities = test_harness(test_data, data_path = “/path/to/data”)

The following parameters need to be provided to it:
1. test data
2. data path (where we store the pickled model, preprocessing parameters and the external data).

Return value: probability of default (our model predictions) for each record.



To train the Decision Tree Classifier please use estimator() function: 

The following parameters need to be provided to it:
1. cleaned_data (output of preprocessor)
2. fitting_algo
3. calibrator  (creation shown in notebook)
4. est_params (creation shown in notebook)

Return value: model
