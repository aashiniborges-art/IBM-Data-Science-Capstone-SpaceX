# IBM Data Science Capstone: SpaceX Falcon 9 Landing Prediction

## Project Overview
This project predicts whether the Falcon 9 first stage will land successfully. SpaceX advertises Falcon 9 rocket launches on its website with a cost of 62 million dollars; other providers cost upward of 165 million dollars each. Much of the savings is because SpaceX can reuse the first stage. By predicting a successful landing, we can determine the cost of a launch.

## Methodology
1. **Data Collection:** Scraped Wikipedia launch data using BeautifulSoup and retrieved core payload details via the SpaceX API.
2. **Data Wrangling:** Filtered records, handled missing values, and engineered a binary classification label (1 = success, 0 = failure).
3. **EDA & SQL:** Explored data patterns using Python visualization libraries (Seaborn/Matplotlib) and ran SQL queries to gain baseline insights.
4. **Interactive Analytics:** Built a geographic layout of launch sites using Folium maps and created an interactive operational dashboard using Plotly Dash.
5. **Machine Learning:** Trained and tuned Logistic Regression, SVM, Decision Tree, and KNN models using GridSearchCV to find the highest-accuracy predictor.

## Key Results
* **Best Model:** Support Vector Machine (SVM) with a `linear` kernel yielded the best validation results.
* **Accuracy:** Reached an overall classification accuracy of XX% on the test subset.