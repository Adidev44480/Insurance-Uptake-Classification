# Insurance-Uptake-Classification

The objective is to effectively predict interested customers in purchasing vehicle insurance from the already existing customer base of Health insurance, so that targeted marketing strategies could be implemented. The dataset has 1,00,000+ rows with features like age, gender, previous insurance, annual premium, etc.

During EDA, I found class imbalance where only a small percentage of customers were actually interested in insurance. I handled outliers and duplicate observations to improve model stability.

To handle class imbalance, I used SMOTE / class weights and trained models like Logistic Regression, Naive Bayes, Random Forest and XG-Boost. While evaluation I focused on the recall of the positive class, which also happened to be the minority class, because maximizing detection of interested customers is more important than overall accuracy.

The best performance was achieved with the Logistic Regression with a recall of 87% while attaining accuracy score of 79%. The model is significantly helpful in identifying potential buyers, reducing marketing cost and improving conversion rates.
