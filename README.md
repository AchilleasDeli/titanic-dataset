# titanic-dataset
This is a data set regarding the sinking of the titanic ship.The target is to pre process the data set and create classifiers to predict if a passenger survived or not

Titanic Survival Prediction
This project involves building classifiers to predict whether a passenger survived the Titanic disaster. The classifiers are based on a Neural Network and a Decision Tree model, trained on the Titanic dataset.
Dataset Overview
The dataset contains information about Titanic passengers, including demographics, ticket details, and survival status. The key features used for prediction are:
survival: Survival status (0 = No, 1 = Yes)
pclass: Ticket class (1st, 2nd, 3rd)
sex: Gender of the passenger
Age: Age in years
sibsp: Number of siblings/spouses aboard
parch: Number of parents/children aboard
ticket: Ticket number
fare: Passenger fare
cabin: Cabin number
embarked: Port of Embarkation (C = Cherbourg, Q = Queenstown, S = Southampton)
Methodology
Preprocessing:
Handled missing values in features like Age and Cabin.
Encoded categorical features such as sex and embarked into numeric formats.
Modeling:
Neural Network: Built and trained a neural network model to capture complex patterns in the data.
Decision Tree: Constructed a decision tree classifier to provide a simple, interpretable model for comparison.
Evaluation:
Split the dataset into training and testing sets.
Evaluated both models using metrics like accuracy, precision, recall, and F1-score.
Results
The trained models demonstrated the ability to predict passenger survival based on the given features. The neural network captured nuanced patterns, while the decision tree offered interpretable decision rules.
Future Work
Further improvements could include trying additional models like Random Forests or Gradient Boosted Trees.

