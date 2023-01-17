# Bank Customer Churn

https://www.kaggle.com/datasets/gauravtopre/bank-customer-churn-dataset

> **Dataset**

1. **customer_id**, unused variable.
2. **credit_score**, used as input.
3. **country**, used as input.
4. **gender**, used as input.
5. **age**, used as input.
6. **tenure**, used as input.
7. **balance**, used as input.
8. **products_number**, used as input.
9. **credit_card**, used as input.
10. **active_member**, used as input.
11. **estimated_salary**, used as input.
12. **churn**, used as the target. 1 if the client has left the bank during some period or 0 if he/she has not.

> **Project Structure**

    ├── data
    │   ├── clean
    │   ├── raw
    ├── models
    ├── notebooks
    ├── src
    │   ├── classifier
    │   ├── load
    │   ├── train
    │   ├── transform
    
    ├── .gitignore
    ├── LICENSE
    ├── README.md
    ├── requirements.txt

## S1: Notebooks

```
$ python3 -m venv venv
$ source venv/bin/activate
$ pip install -r requirements.txt
```
