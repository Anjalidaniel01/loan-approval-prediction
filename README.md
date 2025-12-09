**Project title:**  
Loan Approval Prediction using Decision Tree

**Short description:**  
This project uses a Decision Tree classifier to predict whether a loan application will be approved (1) or not approved (0) based on features such as age, income, credit score, loan amount, loan term, and employment status. The model is trained on historical loan data, then evaluated on a test set to measure accuracy and other classification metrics.

**Steps to run:**

1. Clone or download this repository to your local machine.  
2. (Optional) Create and activate a virtual environment.  
3. Install the required Python packages:

   ```bash
   pip install -r requirements.txt
   ```
   or, at minimum:
   ```bash
   pip install pandas scikit-learn
   ```

4. Make sure the dataset file (e.g. `loan_data.csv`) is in the same folder as the notebook/script.  
5. Open the Jupyter Notebook:

   ```bash
   jupyter notebook loan_prediction.ipynb
   ```

   or run the Python script:

   ```bash
   python loan_prediction.py
   ```

6. Run all cells (or the script) to:
   - Load the dataset  
   - Preprocess the data (encode employment status, handle missing values)  
   - Split into train and test sets  
   - Train the Decision Tree model  
   - Print accuracy and the classification report.
