# Fashion Size Prediction

This repository presents a machine learning project focused on predicting clothing sizes based on various product level features. The goal is to assist retailers or e-commerce platforms in offering better size recommendations to customers using data-driven insights.

## Dataset
The dataset contains information on fashion products, including the product name, brand, category, price, customer rating, and color. The target variable is the clothing size (S, M, L, XL). The dataset reflects a mix of men's and women's fashion items.

## Preprocessing
Several preprocessing steps were carried out to prepare the data for modeling. These included handling missing values, encoding categorical variables using LabelEncoder, and separating the dataset into features (X) and target (y). The data was then split into training and testing sets using an 80/20 split.

## Models Used
Four supervised learning algorithms were trained and compared:
- **Logistic Regression**
- **Decision Tree Classifier**
- **Random Forest Classifier**
- **XGBoost Classifier**

Each model underwent hyperparameter tuning using GridSearchCV to improve performance and reduce overfitting. All models were trained on the same split for fair comparison.

## Evaluation and Results

Model performance was evaluated using accuracy, precision, recall, and F1-score. The Decision Tree Classifier achieved the highest overall accuracy at **27.5%**, followed by Logistic Regression (24.5%), XGBoost (23.5%), and Random Forest (21%). Confusion matrices and classification reports were generated to provide deeper insights into prediction strengths and class-level weaknesses.

## Repository Contents
- `fashion_size_prediction.ipynb`: Full notebook containing preprocessing, model training, evaluation metrics, and visualizations.
- 
## Author
Rupinder Singh | MSBA Candidate | Passionate about AI in Fashion
