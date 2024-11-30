# Depression-Prediction
 Unveiling the Shades of Mind – A Study on Depression Classification

This project focuses on using machine learning to predict and classify depression in individuals based on demographic and lifestyle factors. By leveraging advanced analytical techniques, we aimed to provide a model capable of accurately identifying depression, an increasingly prevalent mental health issue. Here's an overview of the techniques applied and results obtained:
Techniques Applied:

    Exploratory Data Analysis (EDA):
    We began by performing univariate, bivariate, and multivariate analyses using graphical techniques such as histograms, scatter plots, box plots, and heatmaps to identify patterns and relationships between variables. A key observation was the class imbalance, with a majority of the dataset showing individuals not diagnosed with depression.

    Data Preprocessing:
    Data cleaning and preprocessing involved handling missing values, identifying outliers using the Isolation Forest, and addressing class imbalance using SMOTE, upsampling, and downsampling techniques.

    Clustering:
    We applied k-prototypes and KMeans clustering methods to explore potential groupings within the data. However, these approaches showed low silhouette scores, indicating poor clustering performance, which led us to move forward with classification models.

    Classification Models:
    Multiple machine learning models were employed to classify depression, including:
        Logistic Regression
        Support Vector Machine (SVM)
        Decision Tree
        Random Forest
        XGBoost
        k-Nearest Neighbors (kNN)
        AdaBoost
        Gradient Boosting
        MLP (Multi-Layer Perceptron)
        Naive Bayes

    Model Evaluation:
    Models were evaluated using various metrics: accuracy, precision, recall, F1-score, and feature importance. To handle class imbalance, models were trained on datasets augmented with SMOTE, upsampling, and downsampling techniques.

    Outlier Analysis:
    The dataset was split into outliers and regular observations, and models were tested separately on these subsets. The Random Forest model emerged as the best performer in both the original and balanced datasets.

Key Results:

    Best Model:
    The Random Forest model was selected as the optimal model with an impressive accuracy of 85.5%, precision of 80.7%, recall of 85.5%, and F1-score of 80%. This indicates that the model is highly effective in identifying true positives and minimizing false positives.

    Feature Importance:
    The model's feature importance analysis revealed the top 19 variables contributing to its predictions, emphasizing the critical factors influencing depression status.

    Handling Imbalance:
    Techniques like SMOTE and upsampling helped improve the model's performance by balancing the dataset, leading to more reliable predictions, particularly for the depressed class.

Final Output:

We developed a data product – a web-based tool that can be used by healthcare professionals to classify depression status based on individual data, providing timely interventions.
Conclusion:

The project successfully demonstrated the use of machine learning to address the challenge of depression classification, with the Random Forest model proving to be the most effective. The findings highlight the importance of balancing datasets and selecting the right features for improving classification accuracy, offering valuable insights for healthcare workers and researchers.


# Link for the presentation

https://www.canva.com/design/DAGV58GTcpc/DKqXtob1mq7SAJF_O-BALg/edit

# Link for the Data Products

https://drive.google.com/drive/folders/1f1Gg594iui7otgcgIBXGjAo8Aw9ruJa2?usp=sharing

# Reports and Documentations

https://drive.google.com/drive/u/4/folders/1TeD9PNpWINEXZgnwRmfpvMyR_qIZX3F4
