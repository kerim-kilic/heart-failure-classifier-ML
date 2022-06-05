# HR attrition classifier

The R and R Markdown code in this respository covers several supervised machine learning algorithms as well as a neural network to predict if an patiernt is likely to suffer from heart failure based on several clinical features in the dataset. It includes a logistic regression model, a random forest model, and a neural network.

## Requirements

The R script requires the following packages and their requirements:

```r
library(tidymodels)
library(janitor)
```

## Results

The table below shows the results of the performance of the different models proposed in this repository:

| Engine        | Model                         | Accuracy            | Sensitivity | Specificity | Precision | Recall | F Measure |
| ------------- | ----------------------------- | ------------------- | ----------- | ----------- | --------- | ------ | --------- |
| ranger        | random forest                 | 0.8                 | 0.7         | 0.9         | 0.8       | 0.8    | 0.7       |
| glm           | Logistic regression           | 0.8                 | 0.7         | 0.9         | 0.8       | 0.8    | 0.7       |
| keras         | Neural Network                | 0.7                 | 0.6         | 0.8         | 0.6       | 0.6    | 0.6       |
