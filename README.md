# Diabetes Prediction Project

This project aims to predict whether an individual is likely to be diabetic based on various medical features. The dataset used for this project includes information such as pregnancies, glucose levels, blood pressure, skin thickness, insulin levels, BMI, diabetes pedigree function, and age.

## Dataset

The dataset contains the following features:
- **Pregnancies**: Number of times pregnant
- **Glucose**: Plasma glucose concentration
- **BloodPressure**: Diastolic blood pressure (mm Hg)
- **SkinThickness**: Triceps skin fold thickness (mm)
- **Insulin**: 2-Hour serum insulin (mu U/ml)
- **BMI**: Body mass index (weight in kg/(height in m)^2)
- **DiabetesPedigreeFunction**: Diabetes pedigree function
- **Age**: Age (years)
- **Outcome**: Class variable (0 or 1) indicating whether the patient is diabetic or not

## Exploratory Data Analysis (EDA)

To understand the dataset and uncover patterns, the following EDA steps were performed:
- **Descriptive Statistics**: Calculation of mean, median, and standard deviation for each feature.
- **Distribution Plots**: Visualizing the distribution of features using histograms and box plots.
- **Correlation Matrix**: Checking the correlation between different features.
- **Pair Plots**: Scatter plots of feature pairs colored by the outcome to visualize relationships.

## Data Preprocessing

The data preprocessing steps included:
- **Handling Missing Values**: Imputing missing values with appropriate statistics.
- **Feature Scaling**: Standardizing the feature values for algorithms that require scaled input.
- **Creating Age Groups**: Categorizing age into bins to create age groups for better analysis.

## Modeling Techniques

Several machine learning models were used to predict diabetes, including:

1. **Decision Trees**
2. **Random Forests**
3. **K-Nearest Neighbors (KNN)**
4. **Voting Classifier**
5. **Gradient Boosting**
6. **Bagging Classifier**

## Model Evaluation

Each model was evaluated using accuracy as the performance metric. The following observations were made:

- **Decision Trees**: Provided a baseline model with decent accuracy.
- **Random Forests**: Improved accuracy by averaging multiple decision trees.
- **K-Nearest Neighbors (KNN)**: Showed competitive performance but was sensitive to feature scaling.
- **Voting Classifier**: Combined the predictions of multiple models for better accuracy.
- **Gradient Boosting**: Enhanced accuracy by combining weak learners.
- **Bagging Classifier**: Achieved the highest accuracy score among all models tested.

## Conclusion

The Bagging Classifier outperformed all other models in terms of accuracy, making it the best choice for this diabetes prediction task.

## How to Run the Project

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/diabetes-prediction.git
2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
3. Run the Jupyter notebook to see the analysis and model training:
   ```bash
   jupyter notebook diabetes_prediction.ipynb

## Results

The best model, the Bagging Classifier, achieved an accuracy score of 73% on the test dataset.

## Future Work

Further improvements can be made by:

* Exploring more advanced feature engineering techniques.
* Trying out other ensemble methods like Stacking.
* Incorporating deep learning models for better accuracy.

## Author

Maxwell Mogambi - https://github.com/maxwellmogambi

## License

This project is licensed under the MIT License - see the LICENSE file for details.
outlines future work, author information, and the license.


