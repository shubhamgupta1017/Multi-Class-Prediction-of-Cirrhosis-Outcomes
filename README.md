# Multi-Class Prediction of Cirrhosis Outcomes

## Kaggle Competition Solution

This repository contains my solution for the Kaggle competition on predicting the status of patients after a certain number of days post-liver transplantation. The dataset includes information such as age, sex, and other relevant features. The objective is to predict the probability of patients being alive, dead, or alive until a specified number of days with minimal log loss.

## Approach

1. **Data Cleanup:** 
   - Performed data cleaning to handle missing values and ensure data quality.
  
2. **Dimensionality Reduction using Principal Component Analysis (PCA):**
   - Utilized PCA to reduce the dimensionality of the dataset while retaining essential information.

3. **Classification using XGBoost:**
   - Employed XGBoost, a powerful gradient boosting algorithm, for multi-class classification and probability prediction.

4. **Hyperparameter Tuning:**
   - Fine-tuned hyperparameters to optimize the performance of the XGBoost model.

5. **Performance:**
   - Achieved a final log loss of 0.47 on the training dataset.

## Usage

To reproduce the results or experiment with the code, follow these steps:

1. **Clone the Repository:**
   ```bash
   git clone https://github.com/shubhamgupta1017/Multi-Class-Prediction-of-Cirrhosis-Outcomes.git
   cd Multi-Class-Prediction-of-Cirrhosis-Outcomes
   ```

2. **Install Dependencies:**
   ```bash
   pip install -r requirements.txt
   ```

3. **Run the Jupyter Notebook:**
   - Open and run the provided Jupyter Notebook to execute the entire workflow.

4. **Experiment and Fine-Tune:**
   - Feel free to experiment with different parameters or modify the code to further fine-tune the model for your specific requirements.

## Results

The model achieved a final log loss of 0.47 on the training dataset, showcasing its effectiveness in predicting cirrhosis outcomes.

## Acknowledgments

Special thanks to Kaggle for hosting the competition and providing the dataset.


## Author

Shubham Gupta
