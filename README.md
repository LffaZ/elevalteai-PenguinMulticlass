# Penguin Species Multiclass Classification

## Project Description

This project aims to build and compare multiple machine learning models to classify the species of penguins based on their physical characteristics. The dataset consists of measurements from penguins, including their species, island, and sex. The primary focus of this project is to evaluate the performance of different classification models and select the best model based on accuracy.
The dataset used in this project can be found on Kaggle at this [link](https://www.kaggle.com/datasets/larsen0966/penguins).

## Project Goals
- Develop and train several classification models to predict the species of penguins.
- Evaluate all models by comparing their accuracy and selecting the best model.
- Understand the relationships between different features (such as island, sex, bill length, etc.) and their impact on model performance.

## Methodology
1. **Load Data**: The penguin dataset is loaded from Kaggle.
2. **Data Cleaning**: Handle missing values, encode categorical features, and scale the data.
3. **Exploratory Data Analysis (EDA)**: Data exploration to understand the structure of the dataset.
5. **Splitting and Scaling Data**: Split the data into training and testing sets, and apply scaling where necessary.
6. **Modelling**:
   - **One-vs-Rest (OVR) with Logistic Regression**: Using OVR approach with Logistic Regression as base classifier.
   - **Multinomial Naive Bayes (MNB)**: Applying MNB to classify penguin species.
   - **One-vs-Rest (OVR) with Multinomial Naive Bayes**: Using OVR approach with Multinomial Naive Bayes as base classifier.
   
## Conclusion

### Project Key Insights:
- **Species Distribution**: The dataset consists of three species with Adelie being the most represented and Chinstrap the least, which could lead to class imbalance affecting model performance.
- **Species Distribution per Island**: Every island has **Adelie** species, but in **Torgersen Island**, only **Adelie** is present. **Biscoe Island** has no **Chinstrap** species, and **Dream Island** has no **Gentoo** species, highlighting island-specific species distribution.
- **Data Quality**: No outliers were detected in the data and it follows a normal distribution, suitable for analysis.

### Best Model:
- Based on accuracy and overall performance, the best model is One-vs-Rest Logistic Regression. It achieved the highest accuracy of 0.99 and maintained balanced performance across all classes.

If you have any suggestions or improvements for this repository, feel free to reach out to me:

- **Email**: [alifah.zuhrah@gmail.com](mailto:alifah.zuhrah@gmail.com)
- **LinkedIn**: [Alifah Zuhrah](https://www.linkedin.com/in/alifahzuhrah/)
