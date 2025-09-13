# Bike Sharing Demand Prediction 🚴‍♂️  

This project predicts bike rental demand using the **Kaggle Bike Sharing Demand dataset**.  
It leverages **AutoGluon TabularPredictor** to build and optimize models automatically.  

## 📊 Project Workflow  
1. **Dataset Preparation**  
   - Data obtained from Kaggle.  
   - Split into `train`, `test`, and `sample submission` files.  

2. **Baseline Model**  
   - Trained a simple AutoGluon model on the raw training data.  

3. **Feature Engineering**  
   - Extracted features from the datetime column (hour, day, month).  
   - Improved model accuracy with enriched features.  

4. **Hyperparameter Tuning**  
   - Adjusted AutoGluon model hyperparameters.  
   - Compared results across training runs.  

5. **Evaluation**  
   - Measured prediction accuracy at each stage.  
   - Demonstrated improvement from baseline → feature engineering → tuned model.  

## 🛠️ Tech Stack  
- Python  
- Pandas  
- AutoGluon  
- Jupyter Notebook
- Sagemaker Studio


