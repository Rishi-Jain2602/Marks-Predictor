# Marks-Predictor
This project focuses on predicting students' math scores based on various features available in the dataset. Leveraging machine learning techniques, the project encompasses data exploration, feature engineering, model selection, hyperparameter optimization, and final predictions using regression algorithms.
***

## Requirements
- Python 3.x
- Jupyter Notebook
- Python Libraries - Numpy, sklearn, tensorflow , pandas, seaborn, matplotlib, scipy

***

 ## Installation
1. Clone the Repository
``` bash
git clone https://github.com/Rishi-Jain2602/Marks-Predictor.git
```
2. Install the Project dependencies
```bash
pip install -r requirements.txt
```
****

## Model Training
### Data Source 
Dataset: The dataset used for this project, named "StudentPerformance.csv", contains information about students' performance in exams, including scores in different subjects, demographic details, and parental education levels.

### Tools
- Vs code , Codelab

### Key Steps:

#### 1. Notebook Setup

This section includes importing necessary libraries, loading the dataset, and performing basic data examination to understand its structure.

#### 2. Feature Engineering 

New features such as 'Percentage' and 'Grade' are derived from existing score columns to enhance the predictive power of the model.

#### 3. Exploratory Data Analysis (EDA)

Visualizations and correlation analysis are employed to explore relationships between different variables, including gender, parental education, race/ethnicity, and exam scores.

#### 4. Transformation Pipeline 

A transformation pipeline is created to handle numerical, ordinal, and categorical features efficiently, including the implementation of a custom ordinal encoder.

#### 5. Model Development
The data is split into training and testing sets, and an initial model is trained and evaluated using cross-validation techniques. Performance metrics such as Root Mean Squared Error (RMSE) and R-squared are calculated.

#### 6. Hyperparameter Tuning

GridSearchCV and RandomizedSearchCV techniques are utilized to optimize hyperparameters and improve the model's performance.

#### 7. Final Predictions

The best-performing model selected from the optimization techniques is used to make final predictions. Visualizations such as scatter plots of actual vs. predicted values and error distributions are presented to assess model performance.

****
### Result

![image](https://github.com/Rishi-Jain2602/Marks-Predictor/assets/118871883/dbe94b8b-1cc9-433a-b15c-4a2bf604037b)


### Note

1. Make sure you have Python 3.x installed
2. It is recommended to use a virtual environment to avoid conflict with other projects.
3. If you encounter any issue during installation or usage please contact rishijainai262003@gmail.com or rj1016743@gmail.com

