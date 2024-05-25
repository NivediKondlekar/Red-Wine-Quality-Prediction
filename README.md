# Red-Wine-Quality-Prediction

This project aims to predict the quality of red wine based on various physicochemical properties using different machine learning algorithms. The dataset used in this project is the "Wine Quality" dataset from the UCI Machine Learning Repository.

## Dataset

The dataset contains 1,599 instances of red wine samples with 12 attributes:

- Fixed acidity
- Volatile acidity
- Citric acid
- Residual sugar
- Chlorides
- Free sulfur dioxide
- Total sulfur dioxide
- Density
- pH
- Sulphates
- Alcohol
- Quality (score between 0 and 10)

## Exploratory Data Analysis

The project starts with loading the dataset and performing exploratory data analysis (EDA). It includes:

- Checking the dimensions of the dataset
- Displaying the first few rows
- Gathering information about each attribute
- Checking for missing values
- Calculating statistical measures
- Visualizing the distribution of continuous variables using histograms
- Plotting the count of each quality score
- Visualizing the relationship between volatile acidity, citric acid, and quality using bar plots
- Computing the correlation between features and creating a heatmap

## Data Preprocessing

The dataset is preprocessed by:

- Dropping the 'quality' column from the features
- Binarizing the 'quality' column into 'goodquality' (1 if quality >= 7, 0 otherwise)
- Splitting the data into training and testing sets

## Machine Learning Models

The following machine learning models are trained and evaluated on the dataset:

1. **Decision Tree Classifier**
2. **Random Forest Classifier**
3. **AdaBoost Classifier**
4. **Gradient Boosting Classifier**

The models are trained on the training data, and their performance is evaluated on the test data using classification reports.

## Predictive System

The project also includes a predictive system that takes input data (physicochemical properties) and predicts the quality of the wine using the trained Random Forest Classifier model.

## Usage

To run this project, you'll need to have Python and the following libraries installed:

- NumPy
- Pandas
- Matplotlib
- Seaborn
- Scikit-learn

Simply run the code, and it will load the dataset, perform EDA, preprocess the data, train the machine learning models, evaluate their performance, and demonstrate the predictive system.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.
