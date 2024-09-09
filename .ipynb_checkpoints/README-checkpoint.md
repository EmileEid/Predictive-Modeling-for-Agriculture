# Sowing Success: How Machine Learning Helps Farmers Select the Best Crops

## Introduction
Measuring essential soil metrics such as nitrogen, phosphorous, potassium levels, and pH value is an important aspect of assessing soil condition. However, it can be an expensive and time-consuming process, which can cause farmers to prioritize which metrics to measure based on their budget constraints.

Farmers have various options when it comes to deciding which crop to plant each season. Their primary objective is to maximize the yield of their crops, taking into account different factors. One crucial factor that affects crop growth is the condition of the soil in the field, which can be assessed by measuring basic elements such as nitrogen and potassium levels. Each crop has an ideal soil condition that ensures optimal growth and maximum yield.

A farmer reached out to you as a machine learning expert for assistance in selecting the best crop for his field. They've provided you with a dataset called `soil_measures.csv`, which contains:
- "N": Nitrogen content ratio in the soil
- "P": Phosphorous content ratio in the soil
- "K": Potassium content ratio in the soil
- "pH": value of the soil
- "crop": categorical values that contain various crops (target variable).

Each row in this dataset represents various measures of the soil in a particular field. Based on these measurements, the crop specified in the "crop" column is the optimal choice for that field.

## Dependencies
- matplotlib
- pandas
- sklearn

## Results
The model achieves an F1-score of 0.91 on the test set. This means that the model is able to correctly predict the type of crop with 91% accuracy.

The following features were used to train the model:
- Nitrogen content ratio in the soil (N)
- Potassium content ratio in the soil (K)
- pH value of the soil (ph)

The model was able to avoid multicollinearity by selecting features that were not highly correlated.

## Conclusion
In this project, you built a machine learning model to predict the type of crop that a farmer should plant based on the soil conditions in their field. The model achieved an F1-score of 0.91 on the test set, which indicates that it is able to correctly predict the type of crop with 91% accuracy. The model was able to avoid multicollinearity by selecting features that were not highly correlated.

This model can be used by farmers to make more informed decisions about which crops to plant. By selecting the right crops for their soil conditions, farmers can maximize their crop yields and improve their profitability.
