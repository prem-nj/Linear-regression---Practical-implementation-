Here’s your updated **README** with a placeholder for the graph:  

---

# Linear Regression Practical Implementation  

This repository contains a practical implementation of Linear Regression using the California Housing dataset.  

## Dataset  

The dataset used is the **California Housing dataset**, which provides housing data from the 1990 U.S. Census.  

- **Features:**  
  - `MedInc`: Median income in block group  
  - `HouseAge`: Median house age  
  - `AveRooms`: Average number of rooms per household  
  - `AveBedrms`: Average number of bedrooms per household  
  - `Population`: Block group population  
  - `AveOccup`: Average number of household members  
  - `Latitude`: Block group latitude  
  - `Longitude`: Block group longitude  
- **Target Variable:**  
  - `MedHouseVal`: Median house value (in $100,000s)  

## Implementation Steps  

1. **Load Dataset**  
   - Used `fetch_california_housing` from `sklearn.datasets`.  
   - Converted it into a Pandas DataFrame.  

2. **Preprocessing**  
   - Standardized the dataset using `StandardScaler`.  

3. **Train-Test Split**  
   - Split the dataset into training (80%) and testing (20%) using `train_test_split`.  

4. **Model Training**  
   - Trained a **Linear Regression** model using `sklearn.linear_model.LinearRegression`.  

5. **Evaluation**  
   - Used **Mean Squared Error (MSE)** with cross-validation.  
   - Computed **R² Score**.  

6. **Prediction & Visualization**  
   - Performed predictions on the test set.  
   - Visualized residual distribution using Seaborn.  

### Residual Distribution Plot  
Below is the residual distribution plot of the model:  
**![image](https://github.com/user-attachments/assets/afa72ada-c987-465c-afc8-7a6bacc83879)


## Results  

- **Mean Squared Error (MSE):** ~0.519  
- **R² Score:** ~0.338  

## Requirements  

To run this project, install the required dependencies:  

```bash
pip install numpy pandas scikit-learn matplotlib seaborn
```  

## Usage  

Run the Jupyter Notebook (`linear_regression_practical.ipynb`) step by step to see the implementation in action.  

---

Make sure to **save your graph** as an image (e.g., `graph.png`) and include it in your repository for proper display. 🚀 Let me know if you need any changes!
