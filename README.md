# Google-Advanced-Data-Analytics-Capstone
This is my completion of the capstone project under the Google Advanced Data Analytics specializaion in Coursera
Activity_ Course 7 Salifort Motors project lab.ipynb is a jupyter notebook containing a variety of visualizations and my approach to the problem (predicting employee churn) with a logistic regression model, random forest model (with hyperparameter tuning), and an XGBoost model (also with hyperparemter tuning). The XGBoost model achieved the best results with a 98% accuracy rate and 95% f1 score. The model results also include their respective classification report, confusion matrix, and ROC Curve

The XGBoost Model Results (the best performing model of the three) including the feature importances by information gain
![Untitled](https://github.com/L29n/Google-Advanced-Data-Analytics-Capstone/assets/114021216/267f379c-3458-41fe-8895-d8d229ee4f5e)

![Untitled](https://github.com/L29n/Google-Advanced-Data-Analytics-Capstone/assets/114021216/256b5b6e-ba1e-49ea-896b-c324911add63)

![Untitled](https://github.com/L29n/Google-Advanced-Data-Analytics-Capstone/assets/114021216/8cab2e1b-dbd8-4f9b-89a8-e707112b42db)

     precision    recall  f1-score   support

           0       0.99      0.99      0.99      2526
           1       0.96      0.93      0.95       472

    accuracy                           0.98      2998
    macro avg      0.98      0.96      0.97      2998
    weighted avg   0.98      0.98      0.98      2998

Above is the classifcation report


