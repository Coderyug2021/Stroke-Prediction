# Stroke-Prediction
Stroke are very common nowadays, this dataset contains information about it, So used EDA and 10 algorithms for classification.

Steps involved :

1. Data : Collected dataset from Kagle.

2. Preprocessing : 
Categorical Data : Mapping can solve this issue. Thus, used Skearn's LabelEncoder.
Null Values : There were 201(approx) null values in the "bmi" column of the dataset, so I used a SimpleImputer with strategy="mean".
Feature Importance : I wanted to know which feature contribute more to the Model. By using RFC(Random Forest Classifier) I switched out the meaningful features.
Visualization : Using the EDA technique I plotted the correlation graph between data features.

 3. Model : I used 10 plus models, in order to find out the best model I used evaluation techniques like confusion matrix, F1 score and accuracy obviously and find it out that various models perform good at accuracy rate but the F1 score is extremely bad.

EDA : A visualization techniques used to understand the correlation amongs data features.
