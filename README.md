# ML_Wildfire_Size_Prediction
Predict the wildfire size using description of the causes, intervention conditions and other data.
Basic Machine learning techniques are used.

### Repo contents:
- train.csv has the labeled data for training the model.
- test.csv is the dataset for prediction.
- data_dictionary.pdf contains description of columns available in dataset.

Classify the wildfires into 5 classes based on the final area burned :
'size_class' is the column which need to be predicted

### Code content:
- Data manipulation using Pandas.
- Data preprocess functions (for easy data malipulation).
- Basic model training using scikit-learn.
- Evaluation of models to improve performance (Model cross-validation).
- Hyper parameter tuning (random search, grid search).
- Model comparison (Decision tree, K-Nearest Neighbors Algorithm, Random Forest, XGB classifier).

### Requirements:
- Python and jupyter notebook
Libraries:
- numpy
- pandas
- scikit-learn
- category_encoders
- matplotlib
- math
