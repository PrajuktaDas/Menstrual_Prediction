# Period Pain Level Prediction using Linear Regression

## Project Overview
This project predicts the average pain level during menstrual cycles based on two key features:
- Cycle Length (in days)
- Number of Bleeding Days

The model is trained using a Linear Regression algorithm implemented in Python with the help of pandas, matplotlib, seaborn, and scikit-learn.  
The purpose of this project is to demonstrate how simple machine learning techniques can be applied to health and wellness data for meaningful insights.

---

## Objective
To build a regression model that can predict the pain intensity level (on a scale of 1–10) based on menstrual cycle characteristics.

---

## Dataset Description
The dataset contains 150 data points with the following columns:

| Column Name | Description |
|--------------|-------------|
| CycleLength | Duration of the menstrual cycle (in days) |
| BleedingDays | Number of days of bleeding |
| AvgPainLevel | Average pain level experienced (1–10 scale) |

Dataset file: `period_data_extended.csv`

---

## Technologies Used
- Python  
- Pandas  
- NumPy  
- Matplotlib  
- Seaborn  
- Scikit-learn  

---

## Steps Involved
1. **Data Loading and Exploration**  
   - Load the dataset using Pandas  
   - Visualize relationships between features using scatter plots and pairplots  

2. **Correlation Analysis**  
   - Generate a correlation heatmap to study dependencies between variables  

3. **Model Training**  
   - Split the dataset into training and testing sets (80/20 split)  
   - Train a Linear Regression model using scikit-learn  

4. **Model Evaluation**  
   - Evaluate performance using MAE, MSE, and R² Score  

5. **Visualization**  
   - Plot the regression line and data distribution for better understanding  

6. **Prediction**  
   - Predict pain level for new cycle data inputs  

---

## Example Prediction
```python
new_pain_level = model.predict([[30, 6]])
print(new_pain_level)
```
Owner- Prajukta Das[http://linkedin.com/in/prajukta-das-a60790309]
