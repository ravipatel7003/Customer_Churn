# Customer Churn Prediction Model

During a certain time when a customer stopped using the services or products is called customer churn and the percentage of these customers during a specific time is called customer churn rate. The time frame could be days, months, quarters or years. The higher the customer churn rate, the more revenue the company losses. So, no doubt companies want to keep it as low as possible. Many companies have retention/loyalty teams to retain their customers from leaving the company. However, it is not enough for companies to rely on them. They want to identify risky customers as early as possible. So the companies can retain their customers before they go window shopping.

# Dataset

The dataset used in the project is taken from Kaggle. The dataset contains over 100 features and 100,000 instances. The instances are taken between 31 and 60 days after the observation period(No information on the observation period but from the data it looks like it was around 6 months). The features contain information about the telecom customers in categorical and continuous values. The data in the dataset is approximately balanced.

# Training and Testing

The dataset was divided into 80% training and 20% testing datasets. Then, all the analysis and training happened on the training dataset; the test dataset was used only in the end for the evaluation. During the model training, the training set was again split into two datasets, training and validation. This training dataset was used with cross-validation to tune the model parameters.

# Contributing

Pull requests are welcome.
