# Best-techniques-and-metrics-for-Imbalanced-Datasets

Imbalanced data refers to a situation, primarily in classification machine learning, where one target class represents a significant proportion of observations. Imbalanced datasets are those where there is a severe skew in the class distribution, such as 1:100 or 1:1000 examples in the minority class to the majority class.

Class Imbalance appear in many domains, including:

- Fraud detection (the vast majority of the transactions will be in the "Not-Fraud” class)
- Disease screening (the vast majority will be healthy)
- Subscription churn (the vast majority of customers stay with the service - the “No-Churn” class)
- Ad Serving (click prediction datasets don’t have a high clickthrough rate)

There are several approaches to solving class imbalance problem before starting classification, such as:

- More samples from the minority class(es) should be acquired from the knowledge domain.

- Changing the loss function to give the failing minority class a higher cost.

- Oversampling the minority class.

- Undersampling the majority class.

- Any combination of previous approaches.

Oversampling methods duplicate or create new synthetic examples in the minority class, whereas undersampling methods delete or merge examples in the majority class. Oversampling is the most often used approach (but not necessarily the best).
