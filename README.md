# Market-Analytics

Using Supervised and Unsupervised Machine Learning Methods to leverage strategic decision making. A case study of a supermarket.
Python, Machine Learning, Clustering, Forecasting-Models, Probability based ROI calculations

<img width="603" alt="Screenshot 2024-02-07 at 12 53 17" src="https://github.com/MarcJerschov/Market-Analytics/assets/50746332/a9e9d215-8ab0-4602-881c-9f839e9849b3">

After the data was cleaned using a combination of critical thinking, the z-score method, and the IQR-Distance method, a systematic exploration process was proceeded with. By adhering to the Crisp-DM framework, feature engineering was engaged in, the data was standardized, and derived variables, ratios, and percentiles were generated. Subsequently, the data was analyzed to determine the optimal number of clusters. To achieve this, hierarchical clustering was employed with various methods and distance concepts, while the Elbow method and silhouette method were also explored for guidance. K-means clustering was further conducted, exclusively utilizing customer-based variables. To account for the categorical variables not utilized in the Cluster Analysis, Correspondence Analysis was conducted, mapping the Clusters against these variables. Additionally, a second-order clustering analysis was performed using product-based variables, examining the combination of clusters. In the end, three distinct and Ill-defined clusters were successfully identified.

In the second phase of the project, the focus was shifted towards developing a classification model to predict the number of customers to target for a new marketing campaign. To facilitate this, a newly derived variable called “monetary” was introduced. Two sets of models were then created: one incorporating the derived variable and another without it. A range of different models, including KNN, SVM, Neural Networks, Logistic Regression, XGBoost, Random Forest, and Balanced Random Forest, was explored. By comparing the performance of these models against each other and the second set of models, the aim was to identify the most effective approach. Hyperparameter tuning was conducted using Grid-search techniques to optimize model performance.

The XGBoost model outperformed other models. Using the Validation set, we determined the optimal cut-off point for contacting customers based on ROI. We contacted the top 15% as per the sorted predictions.

<img width="1170" alt="Screenshot 2024-02-07 at 12 53 36" src="https://github.com/MarcJerschov/Market-Analytics/assets/50746332/6e67a56d-6bf3-4c49-b43b-8e532753815d">
