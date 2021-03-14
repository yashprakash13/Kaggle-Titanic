# Kaggle Titanic Competition
This is the dev branch of the repo aimed at modelling and making submissions for the [Kaggle Titanic Competition](https://www.kaggle.com/c/titanic) with the code from Juputer Notebooks. This repo will be updated as I try better models to improve and get a higher score. 

### To get started:
1. Clone this repo on your local machine
2. At the terminal, run:
```bash
pipenv shell
```
3. Then install the requirements:
```bash
$ pipenv install -r requirements.txt
```
4. Finally, open the jupyter lab environment:
```bash
pipenv run jupyter lab
```

### The notebooks
1. First submission- **titanic-pred-raw.ipynb**, uses linear SVM model to predict survivors aboard the Titanic. 
Accuracies gotten:
* validation: 83.8%
* test(submitted): 77.2%
