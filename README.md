# 🌿 Drug Addiction Detection Among Teenagers

![Header Image](URL_TO_A_RELEVANT_IMAGE)

Drug addiction among teenagers is a pressing concern in today's society. With the power of machine learning, we aim to detect and possibly predict addiction, ensuring timely interventions.

## Table of Contents
- [Objective](#objective)
- [Dataset Overview](#dataset-overview)
- [Methodology & Notebooks](#methodology--notebooks)
- [Conclusion](#conclusion)
- [Project Scope](#project-scope)
- [Usage](#usage)
- [Support](#support)
- [Contributing](#contributing)

## 🎯 Objective
Our main objective is to detect drug addiction among teenagers using machine learning classifiers. With the help of accurate predictions, we aim to initiate early interventions and prevent further consequences of addiction.

## 📊 Dataset Overview
Our dataset comprises multiple variables, capturing various aspects of individuals' lifestyles and attributes that might be leading to drug addiction.

#### Sample Data:
Age: between 22 to 35 years
Gender: Male
Education: Undergraduate
...
Frequency of drug usage: Once/twice a week

markdown
Copy code
_(This is a summarized version. The actual dataset consists of more detailed and varied entries.)_

## 📔 Methodology & Notebooks
Our project includes 5 Jupyter notebooks:
1. **Baseline Model Notebook**: This notebook sets up a foundational model without any oversampling.
2. **SMOTE Oversampling Notebook**: Here, we utilize the Synthetic Minority Over-sampling Technique.
3. **BorderlineSMOTE Oversampling Notebook**: In this notebook, we apply the BorderlineSMOTE technique for a nuanced approach.
4. **ADASYN Oversampling Notebook**: Advanced ADaptive overSampling is employed here.
5. **RandomOverSampler Notebook**: This notebook uses the straightforward random oversampling method.

From our classifiers - Logistic Regression, K Nearest Neighbour, Random Forest, Decision Tree, and Gaussian Naïve Bayes, K-nearest neighbor and Random Forest stood out. Both these classifiers exhibited an approximate accuracy of 80% on our test and training dataset.

## 🔍 Conclusion
Having achieved a commendable accuracy rate of 80% with the K-nearest neighbor and Random Forest classifiers, we have a promising model to detect drug addiction. This model will be instrumental in averting potential drug consumption and the repercussions on teenagers.

## 🚀 Project Scope
We primarily focus on predicting the state of an individual concerning drug addiction using input and target variables.

## 🛠 Usage
To get started with our model:
- **Clone** the repository.
- Navigate to the desired notebook.
- Ensure all the **required libraries** are installed.
- Run the model and make predictions on new data.
- Seamlessly integrate with web or mobile applications for a wider reach.

## 🤝 Support
For any queries or support, please raise an issue or contact the repository owner.

## 🌱 Contributing
Open to enhancements & bug-fixes. Feel free to submit a pull request.

---

_Found our project helpful? Give us a ⭐️ and share it with others!_
