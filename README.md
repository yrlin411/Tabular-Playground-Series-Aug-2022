## 2022-Fall NYCU Introduction to Machine Learning Final Project
### Introduction
The purpose of the project is to join a real-time Kaggle competition, this particular task available during August 2022 was to train a machine learning model to predict individual product failures of new codes by the results of a large product testing study. The links down below are respectively the overview of the competition and the model I trained to get the final score. 
- Tabular Playground Series Aug 2022 | https://www.kaggle.com/competitions/tabular-playground-series-aug-2022
- Trained model weight | https://drive.google.com/file/d/1gFTlAi2s1r2loJG5coCe7QjdbH3mJLDB/view?usp=share_link
- Private Score: 0.59234 , Public Score: 0.59058


### Reproducing Submission
To reproduce my submission without retraining, do the following steps:
1. Download the trained model weight mentioned above
2. Download the csv file for testing and submission from the competition data
3. Change the path of the csv file for testing and submission in `109550069_Final_inference.ipynb`
4. Represent the environment by installing `requirements.txt` with `pip install -r requirements.txt`
5. Run `109550069_Final_inference.ipynb`
6. Submit the output csv file to the competition mentioned above
