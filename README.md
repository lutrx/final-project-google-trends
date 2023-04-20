# Analyzing emerging trends in Google Trends data  | Final Project

**Lisa-Maria Bieker**
**Ironhack Data Analysis**

## Project Description

The aim of the project was to analyze the popularity levels of different search queries from Google Searches and create a model to predict the change in popularity level for the next month.
This could be useful in various business cases, e.g. for creating user-relevant social media content.

The presentation of the project has been done with Google slides:  [link](https://docs.google.com/presentation/d/1VVg_uXdgNgWt--azqbAJ9DXfTO9EoCVyKNcGy3vbKOs/edit?usp=sharing)

## The following tools/skills were used:

  * Jupyter Notebook
  * Python: Pandas, Numpy, Seaborn, Matplotlib
  * API: pytrends Pseudo API for Google Trends [link](https://pypi.org/project/pytrends/)
  * Statistical analysis
  * machine learning: Classifier Models

  ## Dataset

  * Dataset for collecting a diverse set of search queries was found at Kaggle: [link](https://www.kaggle.com/datasets/dhruvildave/google-trends-dataset)
  * Monthly Popularity levels per search query from 2004-2023 were collected by using pytrends API

  ## Data Preparation & Analysis & Visualization

  * 232 popularity level datapoints per search query were available
  * change in popularity level between two months was calculated for each month since datapoint 31
  * datapoints per search query were splitted in junks of 29 datapoints as features to train a classifier model:
                * target: classification
                            1: change in popularity level to next month will be equal or greater than 5
                            0: change in popularity level to next month will be lower than 5
  * used models: Logistic Regression, DecisionTreeClassifier, RandomForestClassifier, KNeighborsClassifier, MLPClassifier (Neural network)
  * Exploratory data analysis: visualizations of data were made with matplotlib and seaborn

  ## Conclusion:

  






