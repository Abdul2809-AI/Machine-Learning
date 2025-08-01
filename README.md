# Machine-Learning
# House Price Prediction using Linear Regression

This project is a beginner-friendly implementation of a **Linear Regression model** to predict house prices based on different features like area, neighborhood, overall quality, and more.

It’s part of my machine learning journey — learning by doing real-world projects on real data.

----------------------------------------------------------------------------------------

## What's Inside

- `house_prediction.ipynb` — the full notebook with code, explanations, and results  
- `train.csv` and `test.csv` — the dataset used for training and testing  
- `output/visualizations/` — saved charts that helped explore the data  
- `output/model.pkl` — trained regression model  
- `requirements.txt` — dependencies used in the notebook  
- `README.md` — you're reading it!

----------------------------------------------------------------------------------------

## Project Overview

This project uses the **Ames Housing dataset** (similar to the famous Kaggle House Prices competition). The goal is to train a regression model that can estimate house sale prices using various numerical and categorical features.

----------------------------------------------------------------------------------------

## 🔍 What I Did

- Cleaned and explored the data (EDA)
- Visualized patterns and correlations
- Built a **Linear Regression model using scikit-learn**
- Evaluated its performance using real metrics
- Saved the model and results for reuse

----------------------------------------------------------------------------------------

## 📊 Model Performance

After training, here's how well the model performed on the test set:

- **Mean Absolute Error (MAE):** \$13,460  
- **Root Mean Squared Error (RMSE):** \$20,956  
- **R² Score:** 0.9304

That means the model can explain over **93% of the variation** in house prices — not bad for a simple linear model!

----------------------------------------------------------------------------------------

## 🖼️ Visualizations

I created a few visual plots to better understand the data, such as:

- **Distribution of Sale Prices**
- **Average House Price by Neighborhood**
- **Correlation Heatmap**

📁 You can find them in the [`output/visualizations/`](output/visualizations) folder.

-------------------------------------------------------------------------------------

## 📦 Requirements

To run this project locally, make sure you have the following Python packages installed:

```txt
pandas==1.5.3
numpy==1.24.3
matplotlib==3.7.1
seaborn==0.12.2
scikit-learn==1.2.2
