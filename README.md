# Credit-Card-Fraud-Detection
Objective: To Identify fraudulent credit transactions of a credit card company so that customers are not charged for items that they did not purchase.  Dataset: This dataset contains transactions made by credit cards, where we have 180 frauds out of 4700 transactions. The dataset is highly imbalanced, the positive class (frauds) account for 3.83% of all transactions. 

Approach: Understanding the business problem and data, Exploring the dataset, applied various data resampling techniques like under-sampling, oversampling, SMOTE on the imbalanced datasets and used SMOTE technique to build a predictive model(Random Forest Classifier)and used ROC curve to adjust probability threshold to improve the evaluation metric i.e to increase the true positive rate then we will be able to increase the recall for fraudulent transactions. 

Outcome: Computed the AUC curve for the model we developed on SMOTE data. Later, adjusted the probability threshold to 6 %, resulted in an increased true positive rate and recall ( all non-fraudulent labels were correctly classified as non-fraudulent). Finally, Our model correctly predicts transactions that are actually fraudulent as fraudulent transactions.
