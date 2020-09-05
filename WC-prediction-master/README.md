# ICC 2019 WC prediction

## Goals

- Use Machine Learning to predict the winner of ICC 2019 Cricket World Cup.

- Predict the outcome of individual matches for the entire competition.

- Run simulation of the next matches i.e semi finals and finals.

These goals present a unique real-world Machine Learning prediction problem and involve solving various Machine Learning tasks: data wrangling, feature extraction and outcome prediction.

## Data

I used data sets from Kaggle - Results of the matches since 1975 and 2017. 

## Environment and tools

1. Jupyter Notebook
2. Numpy
3. Pandas
4. Seaborn
5. Matplotlib
6. Scikit-learn

I used the ICC ranking as of MAY 2019 dataset and a dataset containing the fixture of the group stages of the tournament. I compared Support Vector Machines, Logistic Regression, Random Forest and K-Nearest Neighbours model.
        
Random Forest was the winner with a training accuracy of 70 % and test accuracy of 67.5%.

## Installation

`pip install -r requirements.txt`

`jupyter notebook`

## References

1. https://towardsdatascience.com/using-machine-learning-to-simulate-world-cup-matches-959e24d0731