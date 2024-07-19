# Anaemia-Prediction
This project aims to predict anemia based on pixel percentages of RGB values and hemoglobin levels using various machine learning models. The dataset used contains information about individuals' red, green, and blue pixel percentages, hemoglobin levels, and whether they are anemic or not.

### Dataset: 
The dataset contains 500 rows and 7 columns:
* Number: Identifier for the individual
* Sex: Gender of the individual (M for Male, F for Female)
* %Red Pixel: Percentage of red pixels
* %Green Pixel: Percentage of green pixels
* %Blue Pixel: Percentage of blue pixels
* Hb: Hemoglobin level
* Anemic: Whether the individual is anemic (Yes or No)

### Exploratory Data Analysis (EDA)
The following steps were performed during EDA:
- Checked for missing and duplicate values.
- Visualized the distribution of genders.
- Analyzed the number of anemic and non-anemic individuals.
- Examined the correlation between features.
- Used pair plots to visualize the relationship between features and the target variable.

### Model Training and Evaluation
Several machine learning models were trained and evaluated:
- GaussianNB
- MultinomialNB
- BernoulliNB
- Logistic Regression
- Decision Tree
- KNeighborsClassifier
- RandomForestClassifier
- Support Vector Machine (SVM)

### The models were evaluated using the following metrics:
- Accuracy
- Precision
- Recall
- F1 Score

### Conclusion
* The DecisionTree model performed the best with the highest accuracy and recall, making it the most suitable model for deployment.
* RandomForestClassifier also performed well and could be a viable alternative.
* SVM and Logistic Regression models showed similar performance.
