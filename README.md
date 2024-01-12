# WBS-Project6-HousePrices-Classification
## Classifying houses using various models and parameters

In this project we worked for a consultancy specialising in real estate that wants to use housing data to be able to answer the question if the “true value” of a property is above or below the price set by the appraisal. Our task was to create a model that predicts if a house is "epensive" or "not expensive" based on its characteristics. The dataset contained historical data of houses in Ames including the category "expensive/notexpensive" as well as around 80 different features, such as the area, the state of the property, whether it has a backyard or not, etc.

We used the models:
- DecisionTreeClassifier
- KNeighborsClassifier
- LogisticRegression
- SupportVectorMachine
- RandomForestClassifier
- XGBClassifier

We also tried different scaling- and imputing methods and used GridSearch Cross Validation to finetune the parameters. I reached the highest accuracy scores with the XGBoost model. The model can be found in the notebook attached.





