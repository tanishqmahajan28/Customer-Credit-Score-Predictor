# Credit Score Prediction using ANN 📊

This project predicts whether a customer's credit score is categorized as Good, Poor, or Standard based on various financial attributes using a Deep Learning model (Artificial Neural Network - ANN).

## Project Overview 📝

The dataset contains customer financial information such as income, loan details, outstanding debt, and more. The objective is to classify customers into three categories of credit score: **Good**, **Poor**, and **Standard**.

### Dataset Features 📁

- **Customer Demographics**: Age, Occupation, Monthly Inhand Salary, etc.
- **Financial Attributes**: Annual Income, Number of Loans, Outstanding Debt, Credit Utilization Ratio, etc.
- **Credit Score Category**: Target variable with three possible outcomes: Good, Poor, Standard.

## Workflow 🚀

1. **Data Preprocessing**
   - Handle missing values by imputing or dropping as necessary.
   - Detect and treat outliers using the interquartile range (IQR) method.
   - Encode categorical variables using one-hot encoding.
   - Normalize numerical features to improve model performance.

2. **Modeling with ANN**
   - Build and train an Artificial Neural Network (ANN) using Keras and TensorFlow.
   - The model architecture includes input layers corresponding to the features, hidden layers with `ReLU` activation functions, and an output layer with `softmax` for multi-class classification.
   - Optimize the model using the Adam optimizer and categorical cross-entropy loss.

3. **Evaluation**
   - Evaluate the model performance using accuracy, precision, recall, and F1-score.
   - Visualize loss and accuracy metrics over epochs.

## Dependencies 🔧

TensorFlow / Keras,
Pandas, NumPy,
Scikit-learn (for preprocessing),
Matplotlib / Seaborn (for visualizations)

## Usage 💻

1. Ensure the dataset (train (ANN).csv) is in the root directory.
2. Run the notebook or script to preprocess the data and train the model:
    ```bash
    jupyter notebook Final_ann.ipynb
3. After training, the model will classify customer credit scores.

## Results & Conclusions 🏁

The ANN model achieves competitive accuracy in predicting credit score categories. The confusion matrix and classification report provide insights into model performance.

## Contact 📞

For any queries or suggestions, please contact Tanishq Mahajan at trmahajan28@gmail.com.
