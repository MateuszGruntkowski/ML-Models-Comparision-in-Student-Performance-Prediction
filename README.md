# Comparison of Machine Learning Models in Predicting Student Grades  

## Project Overview  
This project evaluates the performance of various machine learning models in predicting student grades based on synthetic data. The dataset includes key factors such as study habits, sleep patterns, socioeconomic background, and class attendance, which are used as predictors for student performance (grades).  

The project is divided into the following sections:  
1. **Imports**: Loading necessary libraries and dependencies.  
2. **Exploratory Data Analysis (EDA)**: Analyzing and visualizing the dataset to understand key trends and relationships.  
3. **Functions for Visualization/Model Evaluation**: Custom functions for plotting and comparing model performance.  
4. **Training Machine Learning Models**: Training and evaluating multiple machine learning models.  
5. **Training Neural Networks**: Building and training a simple neural network.  
6. **Summary**: Consolidating insights from the model performance comparison.  

---

## Dataset Overview  
The dataset is a synthetic representation of student performance, designed to simulate real-world scenarios.  

### Key Features  
- **Study Hours**: Average daily hours spent studying.  
- **Sleep Hours**: Average daily hours spent sleeping.  
- **Socioeconomic Score**: A normalized score (0-1) indicating the student's socioeconomic background.  
- **Attendance (%)**: Percentage of classes attended by the student.  
- **Grades (TARGET)**: The final performance score of the student (dependent variable).  

---

## Machine Learning Models  
The following models were trained and evaluated:  
1. **Linear Regression**  
2. **Ridge Regression**  
3. **K-Nearest Neighbors (KNN)**  
4. **Random Forest Regressor**  
5. **Decision Tree Regressor**  
6. **Support Vector Regressor (SVR)**  
7. **Gradient Boosting Regressor**  
8. **Neural Network**  

---

## Metrics Used for Evaluation  
The models were compared using:  
- **R² (Coefficient of Determination)**: Measures how well the model explains the variance in the data.  
- **Mean Squared Error (MSE)**: Indicates the average squared difference between predicted and actual values.  

---

## Summary of Results  
The project concludes with a comparison of all models, highlighting their performance on the dataset. Key insights and recommendations are provided based on the results of R² and MSE metrics.  

---

## How to Run the Project  
1. Clone this repository or download the notebook file.  
2. Install the required dependencies:  
   ```bash  
   pip install -r requirements.txt  
