# Group_00

| Name                | Email                      |
| ------------------- | -------------------------- |
| Marcel Jar          | marcel.jar@senecapolytechnic.ca |
| Tony Stark          | tony.stark.@avengers.com    |
| Bruce Banner        | bruce.banner@avengers.ca      |


### Credit Card Fraud Detection

Credit card fraud can have a significant impact on banks. Beyond immediate financial losses, which can result from unauthorized transactions and the reimbursement of defrauded customers, banks face reputational damage as well. Instances of fraud erode customer trust and confidence in the security of financial services. Moreover, the costs associated with investigating and resolving fraudulent activities, implementing enhanced security measures, and potential legal actions add further strain to a bank's resources.

We propose to develop a machine learning system for detecting fraud in credit card usage. We will begin by collecting a comprehensive dataset containing historical credit card transactions, including both legitimate and fraudulent examples. We will preprocess the data to handle missing values, normalize features, and address any imbalances between normal and fraudulent transactions. Next, we will employ supervised machine learning algorithms such as logistic regression and decision trees. Train the model on a subset of the data and evaluate its performance. Fine-tune the model parameters to optimize its predictive capabilities. Implementing anomaly detection techniques, like isolation forests or one-class SVM, can also enhance fraud detection. Finally, we will integrate the trained model into a real-time system where incoming credit card transactions are evaluated for potential fraud based on learned patterns.

We will use Python libraries such as pandas, scikit-learn, and TensorFlow in this project. Pre-processing of large datasets will be performed using Spark.
