
This is Vehicle Insurance Model in which predicts whether a customer would be interested in Vehicle Insurance to optimise its business model and revenue.

Now, in order to predict, whether the customer would be interested in Vehicle insurance, 
you have information about: 
                          demographics (gender, age, region code type), 
                           Vehicles (Vehicle Age, Damage), Policy (Premium, sourcing channel) etc.


We have two datasets: train and test datasets.

Few Steps performed are:

Converting all string columns to numeric columns and categorical columns
Data Visualization
We need to fit the test dataset as well as per the cleaned train dataset


The dataset has 12 columns:  [fixed_acidity,volatile_acidity,citric_acid,residual_sugar,chlorides,free_sulfur_dioxide,
                                  total_sulfur_dioxide,density,pH,sulphates,alcohol]



├── README.md          <- The top-level README for developers using this project.
├── data
│   ├── external       <- Data from third party sources, downloaded from codingrade LMS  "train.csv" and "test.csv"
│
│
├── models             <- Trained and serialized models, "EDA.pkl", "Model.pkl" file [EDA files and tain/tested and saved on disk.]
│
├── notebooks          <- Jupyter notebooks. "EDA.ipynb", "Train.ipynb", "Test.ipynb"
│
│
├── requirements.txt   <- The requirements file for reproducing the analysis environment, e.g.
│                         generated with `pip freeze > requirements.txt`
│
├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
│   │
│   └──
└──
