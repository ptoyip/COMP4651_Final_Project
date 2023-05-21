# COMP 4651 Final Report

## Idea

By using Spark as data distributed frameworks to analyze publicly available [Kagge Competition](https://www.kaggle.com/competitions/playground-series-s3e14/overview), and [Kaggle Dataset](https://www.kaggle.com/datasets/shashwatwork/wild-blueberry-yield-prediction-dataset)

Data path `data/train.csv` refers to [Kagge Competition](https://www.kaggle.com/competitions/playground-series-s3e14/overview) and `data/WildBlueberryPollinationSimulationData.csv` refers to [Kaggle Dataset](https://www.kaggle.com/datasets/shashwatwork/wild-blueberry-yield-prediction-dataset).

`RDD.ipynb` refers to treating data in RDD format and perform

- Linear Regression with SGD optimization

- Multiple Layer Perceptron with SGD optimization

`DataFrame.ipynb` treat data in dataframe format and analyse data using

- Linear Regression

- Random Forest Classifier

Please see the result inside the nodebook
**For Dataframe, please comment out the unwanted data path, for RDD, it first evalutate Kaggle Dataset, then Kaggle Competition**
