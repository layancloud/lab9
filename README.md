#Decision #trees #& #Random #Forests
This project aims to assess whether a borrower will be able to pay off a full loan amount depending on credit history such as FICO scores and reasons for borrowing money.

1. Comparison of models  
Decision Tree Model: This is similar to a human decision making process which involves asking questions. These questions have Yes or No answers only. This model suffers from "overfitting" because it does not learn patterns but memorizes data.

Random Forest Model: This model resembles several trees (600 trees for us), predictions of which form a single conclusion by majority voting.

2. Outcome (Which one is better?)  
Efficiency: Random Forest Model is superior in terms of accuracy and stability.

The Problem: Both Random Forest Model and Decision Tree find it difficult to predict Class 1 people due to class imbalance in the dataset – much fewer defaulters than non-defaulters.
