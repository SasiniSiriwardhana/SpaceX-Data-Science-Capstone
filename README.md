# SpaceX Falcon 9 First Stage Landing Prediction
**Author:** Sasini Siriwardhana

## Project Overview
In this project, I took on the challenge of predicting whether a SpaceX Falcon 9 rocket will successfully land its first stage. This is a critical problem because being able to reuse rockets is what allows SpaceX to offer much lower launch prices than its competitors.

## Methodology & Tools
I followed a complete data science workflow using various professional tools and libraries:
* **Data Collection:** Official SpaceX API and Web Scraping using BeautifulSoup.
* **Data Wrangling:** Pandas for data cleaning and feature engineering.
* **Exploratory Data Analysis (EDA):** SQL for data querying and Seaborn/Matplotlib for visualization.
* **Interactive Analytics:** Folium for launch site proximity analysis.
* **Machine Learning:** Logistic Regression, SVM, Decision Tree, and KNN using Scikit-learn and GridSearchCV.

## Results & Conclusion
After tuning the models, **Logistic Regression** was the most reliable for this dataset. My final model achieved:
* **Training Accuracy:** 96.6%
* **Test Accuracy:** 94%

### Model Performance (Confusion Matrix):
<img width="1167" height="645" alt="Confusion Matrix and Classification Repor" src="https://github.com/user-attachments/assets/3227496a-5f23-4397-946e-2a24b0e6281a">
