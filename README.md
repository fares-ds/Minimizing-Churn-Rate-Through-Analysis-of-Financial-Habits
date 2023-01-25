# Machine Learning: Use cases in FINTECH
- The data for these projects are manufactured fields based on trends found in real-world case studies. The fields describe what companies usually track from their users, and the distributions are based on observed distributions in the real-world analysis. This means that, although the data has been artificially created, the patterns, associations, and distributions are not random.
- The data serves as a good representation of what you may encounter in the workplace. That is, the data is rarely clean, and a lot of pre-processing is needed to get it ready for modeling.

****

# Note on models Building:
The Model Building Process is composed of multiple parts:

- **Plotting with Matplotlib and Seaborn** - A lot of time will be spent on Exploratory Data Analysis (EDA)
- **Data Manipulation** - We will use Pandas and Numpy for all of our data formatting steps.
- **Classification Models** from Sklearn Library (Logistic Regression, Tree, SVM, ...)
- **K-Fold Cross Validation, Grid Search** (Parameter Tuning), and **Feature Selection** algorithms.

*****

# 1. Introduction

Subscription Products often are the main source of revenue for companies across all industries. These products can come in form of an over compassing subscription, or in multi-level memberships. Regardless of how they structure their memberships, or what industry they are in, companies almost always try to minimize customer churn (a.k.a. subscription cancellations). To retain their disengagement with the product.

- **Market:** The target audience is the entirety of a company's subscription base. They are the ones companies want to keep.
- **Product:** The subscription products that customers are already enrolled in can provide value that users may not have imagined, or that they may have forgotten.
- **Goal:** The objective of this model is to predict which users are likely to churn, so that the company can focus on re-engaging these users with the product. These efforts can be email reminders about the benefits of the product, especially focusing on features that are new or that the user has shown to value.

****

# 2. Business Challenge

- In this case study we will be working for a fin-tech company that provides a subscription product to its users, which allows them to manage their bank accounts (savings accounts, credit cards, etc), provides them with personalized coupons, informs them of the latest low-APR loans available in the market, and educates them on the best available methods to save money (like videos on saving money on taxes, free courses on financial health, etc)
- We are in charge of identifying users who are likely to cancel their subscription so that we start building new features that they may be interested in, these features can increase the engagement and interest of our users towards the product.
****
