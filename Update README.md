# Hotel-Booking-Cancellation-Prediction

### Overview
This project aims to predict hotel booking cancellations using machine learning techniques. Hotel cancellations significantly impact revenue and operational planning, making accurate prediction crucial. The dataset used is sourced from Kaggle, containing various features related to bookings like lead time, deposit type, and customer demographics.

### Key Steps and Techniques Used
1. **Data Cleaning**:
   - Handling missing values and dropping features with excessive NaN values.
   - Removing irrelevant features to streamline the dataset.
   
2. **Exploratory Data Analysis (EDA)**:
   - Visualizing data through bar charts, line charts, box plots, and maps to understand booking patterns.
   
3. **Feature Encoding**:
   - Utilizing mean encoding technique for categorical features to prepare data for modeling.
   
4. **Handling Outliers**:
   - Applying log transformation to manage outliers and improve model performance.
   
5. **Feature Selection**:
   - Using correlation analysis and Lasso regularization for feature selection to identify the most impactful features.
   
6. **Model Training and Evaluation**:
   - Employing cross-validation to accurately estimate model performance.
   - Evaluating various algorithms including Logistic Regression, Decision Trees, Random Forest, Naive Bayes, and K-Nearest Neighbors (KNN).
   
7. **Best Performing Model**:
   - Random Forest demonstrated the highest accuracy of 85% in predicting booking cancellations.

### Technologies Used
- **Python**: Pandas, NumPy for data manipulation; Scikit-learn for machine learning algorithms.
- **Jupyter Notebooks**: Interactive exploration, visualization, and modeling.
- **GitHub**: Version control, project documentation, and collaboration.

### Dataset Source
The dataset used is sourced from a public repository, containing detailed information about hotel bookings including reservation status and customer details.

### Results and Impact
This project provides insights into factors influencing hotel booking cancellations, helping hotels optimize revenue and operational efficiency. The Random Forest model with 85% accuracy offers a reliable method for predicting cancellations.
![result](https://github.com/prasadgirdhari11/Hotel-Booking-Cancellation-Prediction/assets/172724690/ec27f54a-3c45-4614-a682-ab2b3ce4851b)


### Future Enhancements
Future steps may involve:
- Fine-tuning the Random Forest model for improved accuracy.
- Incorporating additional data sources or features to enhance prediction capabilities.
- Deploying the model in a production environment for real-time cancellation predictions.

