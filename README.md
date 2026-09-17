## Machine Learning Journey | Practical 01 — Linear Regression

After completing the Python and Mathematics foundations of my Data Science journey, I’ve now started exploring Machine Learning through hands-on practicals.

## 🤖 What is Machine Learning?

Machine Learning is a branch of Artificial Intelligence that allows computers to learn patterns from data and use those patterns to make predictions or decisions.

Instead of explicitly programming every rule, we provide data to a model and allow it to learn the relationship between input variables and the target.

## 📚 Types of Machine Learning:

• Supervised Learning — learns from labeled data

• Unsupervised Learning — discovers patterns in unlabeled data

• Reinforcement Learning — learns through rewards and penalties

My first practical focuses on **Supervised Learning → Regression → Linear Regression**.

## 📈 What is Linear Regression?

Linear Regression is a supervised learning algorithm used to predict a **continuous numerical value**.

It tries to establish a relationship between independent variables (features) and a dependent variable (target).

For a simple linear regression:

**y = mx + c**

Where:

• y = predicted value
• x = input feature
• m = coefficient/slope
• c = intercept

For multiple features, the model can be represented as:

**y = β₀ + β₁x₁ + β₂x₂ + ... + βₙxₙ**

## 🔍 My Practical Workflow:

1️⃣ Loaded the dataset using Pandas

2️⃣ Performed data preprocessing

3️⃣ Separated features (X) and target (y)

4️⃣ Split the dataset into training and testing sets

5️⃣ Created the Linear Regression model using Scikit-learn

6️⃣ Trained the model on the training data

7️⃣ Generated predictions on the test data

8️⃣ Evaluated the predictions using regression metrics

9️⃣ Compared actual and predicted values through visualization


## 📊 Model Output:

Intercept: 4.831195723111648

Coefficients: [2.50912402 1.19752671]


📏 Regression Evaluation Metrics:

• MAE — Mean Absolute Error

• MSE — Mean Squared Error

• RMSE — Root Mean Squared Error

• R² Score — Coefficient of Determination

## 💡 What I Learned:

This practical helped me understand how a machine learning model learns relationships from data and how important preprocessing, train-test splitting, prediction, and model evaluation are in the ML workflow.

This is just the beginning of my Machine Learning practical journey. 

Next: **Logistic Regression — Practical 02**

#MachineLearning #LinearRegression #DataScience #Python #ArtificialIntelligence #ScikitLearn #MachineLearningJourney #LearningByDoing
