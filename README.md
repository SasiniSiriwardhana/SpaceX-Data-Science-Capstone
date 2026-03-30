Project Name: SpaceX Falcon 9 First Stage Landing Prediction 
Author: Sasini Siriwardhana
In this project, I took on the challenge of predicting whether a SpaceX Falcon 9 rocket will successfully land its first stage. This is a critical problem because being able to reuse rockets is what allows SpaceX to offer much lower launch prices than its competitors. If we can predict the landing success, we can better estimate the overall cost of a mission.
Methodology & Tools:
To make this happen, I followed a complete data science workflow using various professional tools and libraries:
•	Data Collection: I gathered data from two different sources the official SpaceX API and historical launch data scraped from Wikipedia using BeautifulSoup.
•	Data Wrangling: I used Pandas for cleaning the raw data, handling missing values, and performing feature engineering to prepare the dataset for machine learning.
•	Exploratory Data Analysis (EDA): I used SQL to query the data and find hidden insights. For visual exploration, I used Seaborn and Matplotlib to identify patterns in payload mass and orbit types.
•	Interactive Analytics: I built interactive maps using Folium to analyze the proximity of launch sites to coasts, railways, and highways.
•	Machine Learning: I implemented and compared four classification models: Logistic Regression, SVM, Decision Tree, and KNN. I used Scikit-learn and GridSearchCV for hyperparameter tuning.
Results & Conclusion:
I found some really interesting patterns, like how the success rate improved over the years and how the payload's weight and the specific orbit affect the landing.
After tuning the models, I found that Logistic Regression was the most reliable for this dataset. My final model achieved an impressive training accuracy of 96.6% and a test accuracy of 94%, showing it is very effective at predicting these high-stakes landings.

Below is the Confusion Matrix and Classification Report for the Logistic Regression model, which was our best-performing algorithm:

![SpaceX Prediction Results](<img width="1167" height="645" alt="Screenshot 2026-03-30 094152" src="https://github.com/user-attachments/assets/ca34feef-197b-40d4-9122-0381fb9ca597" />
)
