# ECE 143 Final Project Group 2
ECE 143 Winter 2023 Final Project Group 2 - Heart Disease Analysis and Prediction


## File Overview
---
### dataset2_processing.ipynb
-   Note that we didn't end up processing the first data set we were considering. This file processes the dataset [Heart Disease Health Indicators Dataset](https://www.kaggle.com/datasets/alexteboul/heart-disease-health-indicators-dataset/code) and shows various plots such as correlation between each feature in the dataset and boxplots.
---
### dataset3_processing.ipynb
- This file processes the data set [COVID-19 in USA](https://www.kaggle.com/datasets/sudalairajkumar/covid19-in-usa?resource=download]) and show various plots such as correlation between each feature in the dataset, we ended up not using this dataset much for analysis.
---
### model_training.ipynb
- This file trains our Machine Learning model using sklearn and can estimate the chance that an individual is at risk for heart disease depending on several key metrics such as cholesterol level, blood pressure, general health, age, and gender. This file also has various plots such as the bar and pie charts showing up feature importance which we used in our analysis.
---
### Presentation_ Heart Disease Analysis and Prediction.pdf:
- This file contains our presentation slides.

---
## How to run the code
1. Run the file model_training.ipynb to see the graphs of feature importance and check out our machine learning model. 
2. Run the data processing files to see how each of the features are coorelated to each other and other useful figures like boxplots.

#### Third party modules we used:
- pandas 
- numpy 
- matplotlib
- seaborn 
- sklearn

Include a readme file that explains your file structure, how to run your code, and name all third-party modules you are using. 