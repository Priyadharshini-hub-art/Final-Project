Customer Behavior Analysis in E-Commerce using Structured Dataset
In this project, I analyzed an eCommerce dataset to build a Logistic Regression model that predicts whether a discount should be offered to a customer. By exploring user behavior, session data, and product-related features, I trained the model to classify discount decisions. The model achieved an accuracy of around 87%, with a precision of 90%, recall of 76%, and F1-score of 82%, showing strong performance in identifying situations where discounts are likely to influence purchases.

Data Overview:
The dataset includes information about user sessions on an eCommerce platform.
Columns like Page Value, Bounce Rates, Exit Rates, Administrative Duration, and Product Related Duration are explored.
The target variable used is Discount, which appears to be binary (e.g., 0 for no discount, 1 for discount).

Missing Values & Duplicates:
The data was checked for missing values and duplicates, and they were handled appropriately to ensure clean input for the model.

Correlation Analysis:
A heatmap was used to visualize the correlations between numeric features.
Features like Page Value and Exit Rates showed stronger correlations with the target (Discount), which helps identify influential variables for the model.

Class Distribution:
A countplot was used to check the balance between discount and no-discount classes.
This is important to understand if the dataset is imbalanced, which could affect model performance.

Visualizations:
Various plots (histograms, pairplots) were likely used to see distributions and relationships among features.
These visualizations help determine which features might be useful for predicting discount usage.

Feature Selection:
Features with high correlation or business relevance were selected for the logistic regression model.
Irrelevant or weakly related features might have been dropped to improve model efficiency.

Logistic Regression Model Summary
Target Variable: Discount (whether a customer gets a discount)

Model Used: Logistic Regression
 Prediction and Evaluation Metrics
 Accuracy: 87%
→ This means the model correctly predicted discount vs. no discount in 87 out of 100 cases.

Precision: 90%
→ Out of all customers predicted to receive a discount, 90% actually did.

Recall: 76%
→ Out of all customers who truly should receive a discount, the model caught 76%.

⚖ F1 Score: 82%
→ This combines precision and recall into a single balanced score.
True Positives (TP): Customers correctly predicted to get a discount

True Negatives (TN): Customers correctly predicted not to get a discount

False Positives (FP): Customers incorrectly predicted to get a discount

False Negatives (FN): Customers who should get a discount but the model missed

