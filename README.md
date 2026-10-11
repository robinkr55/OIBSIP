# OIBSIP

**Oasis Infobyte Internship · Data Science Track**
**Author:** Robin Kumar

This repository holds my task submissions for the internship. Each task has its own folder with a Jupyter Notebook, a README, the dataset (where one is needed) and the plots.

## Tasks

| Task | Project | Folder | Best model | Key result |
|---|---|---|---|---|
| 1 | Iris Flower Classification | [Task1_Iris_Flower_Classification](Task1_Iris_Flower_Classification) | Decision Tree | 96.67% test accuracy (29 of 30 flowers correct) |
| 4 | Email Spam Detection | [Task4_Email_Spam_Detection](Task4_Email_Spam_Detection) | Support Vector Machine | 98.16% accuracy, 87.79% recall |
| 5 | Sales Prediction | [Task5_Sales_Prediction](Task5_Sales_Prediction) | Random Forest Regressor | R² score of 0.981, MAE of 0.620 |

## Task 1 · Iris Flower Classification

Classifies iris flowers into Setosa, Versicolor or Virginica from four measurements. Covers EDA, visualisations, feature selection discussion, three classifiers and their evaluation.

- Notebook: [Iris_Flower_Classification.ipynb](Task1_Iris_Flower_Classification/Iris_Flower_Classification.ipynb)
- Details: [Task 1 README](Task1_Iris_Flower_Classification/README.md)

## Task 4 · Email Spam Detection

Classifies text messages as spam or ham using text preprocessing, TF-IDF features and two classifiers. Includes WordClouds and a discussion of why recall matters for spam detection.

- Notebook: [Spam_Detection.ipynb](Task4_Email_Spam_Detection/Spam_Detection.ipynb)
- Details: [Task 4 README](Task4_Email_Spam_Detection/README.md)

## Task 5 · Sales Prediction

Predicts product sales from advertising spend on TV, Radio and Newspaper. Covers EDA, scatter plots, a correlation heatmap, two regression models, a residual plot and an analysis of which channel has the highest impact on sales.

- Notebook: [Sales_Prediction.ipynb](Task5_Sales_Prediction/Sales_Prediction.ipynb)
- Details: [Task 5 README](Task5_Sales_Prediction/README.md)

## Tech stack

Python · pandas · NumPy · scikit-learn · NLTK · WordCloud · matplotlib · seaborn · Jupyter Notebook

## How to run

Each task folder has its own `requirements.txt` and its own run instructions. In short:

1. Open the notebook from the task folder in Google Colab or Jupyter.
2. For Task 4 and Task 5, put the dataset file from the same folder next to the notebook.
3. Run all cells.

## Repository structure

```
OIBSIP/
├── README.md
├── Task1_Iris_Flower_Classification/
│   ├── Iris_Flower_Classification.ipynb
│   ├── README.md
│   ├── requirements.txt
│   └── images/
├── Task4_Email_Spam_Detection/
│   ├── Spam_Detection.ipynb
│   ├── sms_spam_collection.tsv
│   ├── README.md
│   ├── requirements.txt
│   └── images/
└── Task5_Sales_Prediction/
    ├── Sales_Prediction.ipynb
    ├── Advertising.csv
    ├── README.md
    ├── requirements.txt
    └── images/
```

## Acknowledgements

- Datasets: Iris (scikit-learn), SMS Spam Collection (UCI Machine Learning Repository), Advertising dataset (An Introduction to Statistical Learning).
- An AI assistant was used for guidance while building these notebooks.
