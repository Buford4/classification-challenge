### Project Summary: Email Spam Detection for ISP Customers

#### Background
As part of an initiative to enhance customer experience, I was tasked with improving the email filtering system to accurately detect and filter out spam emails. Using a dataset with labels indicating 'spam' and 'not spam', we developed two supervised machine learning models: Logistic Regression and Random Forest. The objective was to determine which model more effectively identifies spam emails.

#### Files and Setup
- **Repository**: Created a new repository called `classification-challenge`.
- **Notebook**: Used `spam_detector.ipynb` to implement the project.
- **Data Source**: Spam Data CSV
#### Process
1. **Data Preparation**
   - Loaded the data into a Pandas DataFrame.
   - Created labels (y) from the "spam" column and features (X) from the remaining columns.
   - Checked label balance using `value_counts`.
   - Split the data into training and testing sets.

2. **Feature Scaling**
   - Utilized `StandardScaler` to normalize the features.
   - Scaled both training and testing datasets.

3. **Model Development**
   - **Logistic Regression Model**: Configured and trained using the scaled training data. Predictions were made on the test set, and model accuracy was evaluated.
   - **Random Forest Model**: Similarly developed using the scaled training data, with subsequent predictions and accuracy evaluation.

#### Model Evaluation
- Both models were assessed based on their accuracy scores to determine which was more effective at detecting spam.

#### Findings and Conclusion
- **Performance**: Evaluated the accuracy scores of both models to identify which performed better.
- **Initial Prediction**: Made a prediction about which model was expected to excel before running the tests.

### Requirements Checklist
- **Data Splitting**: Included predictions on expected model performance, created necessary data structures, checked label balance, and split the data appropriately.
- **Feature Scaling**: Successfully implemented and applied `StandardScaler` to the data.
- **Logistic Regression Model**: Configured with a random state, fitted, predictions saved, and accuracy evaluated.
- **Random Forest Model**: Executed similarly to Logistic Regression with all steps from creation to evaluation covered.
- **Model Evaluation**: Addressed questions regarding which model performed better and compared the outcome to initial predictions.