# TITANIC SURVIVAL PREDICTION

# The code aims to predict passenger survival on the Titanic based on their characteristics and provides evaluation metrics to assess the model's performance. It also allows for the display of random passenger information to see how the model's predictions align with the actual data.

# 1. Data Loading: Load the Titanic dataset from a CSV file, which contains information about passengers, including features like age, gender, class, fare, and whether they survived or not.

# 2. Data Preprocessing:
  #  - Drop irrelevant columns: Remove columns that are not needed for the analysis (e.g., "Ticket," "Cabin," "PassengerId").
  # - Handle missing values: Fill in missing values for "Age" with the mean age, "Fare" with the mean fare, and "Embarked" with the most common port of embarkation.

# 3. Data Encoding:
  # - Encode categorical variables: Convert categorical variables like "Sex" and "Embarked" into numerical values using label encoding.

# 4. Data Splitting:
 #  - Split the dataset into training and testing sets to train and evaluate the machine learning model.

# 5. Model Selection and Training:
  # - Use a Random Forest Classifier for predicting passenger survival based on their features, such as age, gender, class, and more.
 #  - Train the model on the training data.

# 6. Model Evaluation:
 #  - Calculate the accuracy of the model on the testing data to assess its performance.
  # - Compute additional evaluation metrics like precision, recall, and the F1-score.
 #  - Display the confusion matrix to visualize true positive, true negative, false positive, and false negative predictions.

# 7. Display Passenger Information:
 #  - Randomly select a subset of passengers from the testing set.
 #  - Display their "Name," "Age," "Sex," and their survival status ("Survived" or "Died") based on the model's predictions.
