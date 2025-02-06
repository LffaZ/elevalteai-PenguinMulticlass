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
- **Species Classification**: The features used in the dataset (such as bill length, flipper length, and body mass) provide discriminative information to classify penguin species.
- **OVR Approach**: The One-vs-Rest (OVR) method using both Logistic Regression and Multinomial Naive Bayes gives good results, but performance varies depending on the model.
- **Model Evaluation**: By evaluating each model's performance, you can see the differences in accuracy and how each model generalizes to unseen data.

### Best Model:
- The top-performing models in this evaluation are OVR Logistic Regression and Multinomial Naive Bayes, both achieving perfect results across all metrics.

If you have any suggestions or improvements for this repository, feel free to reach out to me:

- **Email**: [alifah.zuhrah@gmail.com](mailto:alifah.zuhrah@gmail.com)
- **LinkedIn**: [Alifah Zuhrah](https://www.linkedin.com/in/alifahzuhrah/)
