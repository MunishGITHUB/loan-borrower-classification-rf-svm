# loan-borrower-classification-rf-svm
<b>What:</b> Assignment 2 for ISYS 620 (Data Analytics with Artificial Intelligence)

<b>Goal:</b> to predict whether a borrower paid their loan back in full

<b>About the <i>Loan Borrower Classification.ipynb</i> file:</b> I implemented dummy variables for categorical variables, scaled features using StandardScaler, optimized parameters via GridSearchCV, built a Random Forest model, and built a Support Vector Machine model. 

<b>Best Model Selection Criteria:</b> The final model minimized the number of borrowers who were predicted they paid back their loan in full when they actually did not. In other words, <b>I was looking to minimize the magnitude of the model's Type I error, which is the same thing as minimizing the total count of false positives.</b>
