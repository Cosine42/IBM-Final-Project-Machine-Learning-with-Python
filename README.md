# IBM-Final-Project-Machine-Learning-with-Python
This is a project that I did as a part of the final project for IBM's course https://www.coursera.org/learn/machine-learning-with-python on Coursera.

This is a classification problem on a loan dataset. Various models like Logistic Regression, KNN Classifier, Decision Tree Classifier, 
Random Forest Classifier. The objective was to practice all the classification algorithms taught in the course and try to
select a best performing model.

### The Dataset
The dataset contains the past records of 346 customers whose loan are already paid off or defaulted. It includes following features:

| Field          | Description                                                                           |
|----------------|---------------------------------------------------------------------------------------|
| Loan_status    | Whether a loan is paid off on in collection                                           |
| Principal      | Basic principal loan amount at the                                                    |
| Terms          | Origination terms which can be weekly (7 days), biweekly, and monthly payoff schedule |
| Effective_date | When the loan got originated and took effects                                         |
| Due_date       | Since it’s one-time payoff schedule, each loan has one single due date                |
| Age            | Age of applicant                                                                      |
| Education      | Education of applicant                                                                |
| Gender         | The gender of applicant                                                               |


### Performance Report
After comparing the various models, these conclusions were obtained:

| Algorithm          | Jaccard | F1-score | LogLoss |
|--------------------|---------|----------|---------|
| KNN                | 0.740741| 0.851064 | NA      |
| Decision Tree      | 0.680851| 0.810127 | NA      |
| SVM                | 0.740741| 0.630418 | NA      |
| LogisticRegression | 0.740741| 0.630418 | 8.9547  |
