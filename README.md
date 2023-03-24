<H1 align='center'> LOGISTIC-REGRESSION-ON-CANCER-DATASET</h1>

<h2>INTRODUCTION</h2>

Logistic regression is a statistical modeling technique used to analyze relationships between a dependent variable and one or more independent variables. It is commonly used in medical research to predict the occurrence of diseases such as cancer.The cancer dataset is a commonly used dataset in machine learning and statistical analysis. It contains information about patients who were diagnosed with breast cancer, including various medical features such as the size of the tumor, the age of the patient, and the number of positive lymph nodes.

In this project, we will use logistic regression to analyze the relationship between these medical features and the occurrence of breast cancer. By building a predictive model using the cancer dataset, we aim to identify which features are most strongly associated with the likelihood of breast cancer and ultimately improve our ability to diagnose and treat this disease.

<h2>OBJECTIVES </h2>

**- Demonstrate the Logistic Regression for different penalties/regularisation methods - none, l1, l2 (you may use 'saga' solver as the parameter)**

**- What happens when the Maximum Iterations are kept as 1, 2, 5, 10, 20, 50, 100, 500 and 1000? Is there any change in the accuracy.**

**- Get the attributes: classes_, coef_ and intercept_ and print the same in the above case.**

<h2> REGULARIZATION IN MACHINE LEARNING </h2>

As mentioned above, regularization is used to avoid overfitting due to complex models. When a regularization model is used, the learning model takes only a limited set of parameters. Instead of choosing parameters from a discrete grid, this process chooses values from a continuum that produces a smoothing effect (thereby reducing the noise terms).
In ML models, individual significance of variables and interaction effects is not observed stage wise. In such a case, regularization also helps in the selection process of features contribute to the model. The regularization methods in ML generally adds some kind of penalty to the cost function which is further used in the adjustment process.

L1 and L2 are two types of regularization techniques. Both of these models introduces an additional term of "penalty" on the model based on the error function. The process of weight adjustment hence will also consider the penalty that is applied by these penalties. The key difference between these two is the penalty term.

𝗟𝟭 𝗥𝗲𝗴𝘂𝗹𝗮𝗿𝗶𝘇𝗮𝘁𝗶𝗼𝗻:

L1 (Lazzo) regularization uses the sum of the absolute values of the weights is considered as a penalty. This type is preferred when the model is generally linear in nature with lesser number of coefficients, since it encourages the convergence towards 0. It is also useful for the case of considering a categorical variable with many levels (as mention above, helps in feature selection).

𝗟𝟮 𝗥𝗲𝗴𝘂𝗹𝗮𝗿𝗶𝘇𝗮𝘁𝗶𝗼𝗻:

L2 (Ridge) regularization uses the sum of squared values of weights as the penalty. It tries to make the convergence closer to 0 and prevents overfitting; which becomes very useful when the number of variables are very large and smaller data samples. Genomic data is a very good example to apply L2 regularization.

The regularization parameter penalizes all parameters except intercept; and as the complexity of the model is increased, it also adds penalty for the higher terms. Apart from L1 and L2 regularization techniques, there is something also known as "Elastic Net" which is a hybrid type of both of these techniques.

<h2> CONCLUSION </h2>

In conclusion, logistic regression is a powerful statistical modeling technique that can be used to analyze the relationship between various medical features and the occurrence of breast cancer. By building a predictive model using the cancer dataset, we can identify which features are most strongly associated with the likelihood of breast cancer and improve our ability to diagnose and treat this disease.

Through this project, we have gained a deeper understanding of logistic regression and how it can be used to analyze medical data. We have also seen the importance of using machine learning and statistical analysis to improve medical research and ultimately, patient outcomes. Moving forward, continued research and analysis using tools such as logistic regression will be essential in advancing our understanding of cancer and developing more effective treatments for patients.

<h2> REFERENCES </h2>

- https://www.quora.com/What-is-regularization-in-machine-learning
- https://towardsdatascience.com/regularization-in-machine-learning-76441ddcf99a
- https://towardsdatascience.com/regularization-an-important-concept-in-machine-learning-5891628907ea
- https://www.geeksforgeeks.org/regularization-in-machine-learning/
- https://analyticsindiamag.com/regularization-in-machine-learning-a-detailed-guide/
- https://towardsdatascience.com/l1-and-l2-regularization-methods-ce25e7fc831c

#
