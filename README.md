
# Loan Approval Model

This project contains a machine learning model to predict loan approval decisions based on various financial and demographic features. The model is built and tested in a Jupyter Notebook.

## Project Structure

- **loan-approval.ipynb**: Jupyter Notebook containing data processing, model building, evaluation, and results.

## Installation

To run this project, you’ll need Python and Jupyter Lab installed. You can install the required dependencies with:

```bash
pip install -r requirements.txt
```

If you haven't created a `requirements.txt`, you can use the following command to generate it:
```bash
pip freeze > requirements.txt
```

## Usage

1. Clone this repository.
   ```bash
   git clone https://github.com/your-username/FUTURE_DS_03.git
   ```

2. Install dependencies.
   ```bash
   pip install -r requirements.txt
   ```

3. Launch Jupyter Lab to open and run the notebook.
   ```bash
   jupyter lab
   ```

4. Open `loan-approval.ipynb` to view and run the loan approval model.

## Model Overview

The model predicts the likelihood of loan approval based on input features such as:
- Applicant’s income
- Loan amount
- Credit history
- Employment status

### Evaluation

The model is evaluated using metrics such as:
- Accuracy
- Precision
- Recall
- F1 Score
