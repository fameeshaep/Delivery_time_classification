\#Delivery Time Prediction



\##Overview

This project predicts \*\*delivery time\*\* based on factors like vehicle type, weather, traffic level, distance, preparation time and distance

It is a \*\*regression problem\*\* aimed at improving delivery efficiency



\##Dataset

\-Source: Kaggle 

\-Rows: 1000

\-Columns: 9



\###Input Features:

\-Vehicle type

\-Weather

\-Preparation time(minute)

\-Distance(km)

\-Time of day

\-Traffic level



\###Target:

\-Delivery Time(minutes)



\###Technologies Used

\-Python

\-Scikit-learn

\-Pandas

\-Matplotlib

\-Seaborn



\##Exploratory Data Analysis(EDA)

\-Histogram(distribution check)

\-Boxplot(outlier detection)

\-Scatterplot(relationship analysis)

\-Heatmap(correlation analysis)



\###Key Insights:

\-\*\*Distance\*\* is highly correlated with delivery time

\-outliers found in distance

\-skewness= 0.5



\##Data Preprocessing

\-Used \*\*RobustScaler\*\* to handle outliers

\-Encoding: 

&#x20;-One-hot encoding: vehicle type, Weather, Time of day

&#x20;-ordinal encoding: Traffic level

\-Train-Test Split:

&#x20;-80% Training

&#x20;-20% Testing



\##Models Used \& Performance



\### Logistic Regression

\###Training performance
\-Accuracy:1.00
 
       Class      Precision  Recall   F1-Score    Support
       Fast       1.00      1.00      1.00        17
      Medium       1.00      1.00      1.00       173
        Slow       1.00      1.00      1.00       61

\###Test performance
\-Accuracy:0.88

    
       Class      Precision  Recall   F1-Score    Support
       Fast       1.00      0.50      0.67        6
      Medium       0.85      0.67      0.75      51
        Slow       0.89      0.98      0.93       143
    
\###DecisionTree Classifier
\###Training performance
\-Accuracy:
\-precision:
\-Recall:
\-F1-Score:

\###Test performance
\-Accuracy:
\-precision:
\-Recall:
\-F1-Score:

\###RandomForest Classifier
\###Training performance
\-Accuracy:
\-precision:
\-Recall:
\-F1-Score:

\###Test performance
\-Accuracy:
\-precision:
\-Recall:
\-F1-Score:



       Class      Precision  Recall   F1-Score    Support
       Fast       1.00      1.00      1.00        17
      Medium       1.00      1.00      1.00       173
        Slow       1.00      1.00      1.00       610

    accuracy                           1.00       800
   macro avg       1.00      1.00      1.00       800
weighted avg       1.00      1.00      1.00       800
