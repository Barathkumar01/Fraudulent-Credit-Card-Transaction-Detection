# Fraudulent Credit Card Transaction Detection

This project aims to identify fraudulent transactions in credit card data using machine learning models. Developed by a team of analytics professionals, the project leverages a comprehensive dataset to train decision trees and logistic regression models, providing insights into transaction authenticity.

**Project Overview**

Every day, millions of credit card transactions are processed, exposing consumers and financial institutions to potential fraud. Our project analyzes transaction data to distinguish between legitimate and fraudulent activities, thereby enhancing security measures and minimizing financial losses.

**Models Used**

* **Decision Tree Classifier:** This model was trained on a split of 70% training data and 30% testing data, achieving high accuracy and low error rates. It includes an interpretation of tree results through confusion matrices.

* **Logistic Regression:** Also trained on a 70/30 data split, this model assesses the influence of variables like transaction distance and purchase price ratio on the likelihood of fraud.

**Data Analysis**

* **Data Visualization and Exploration:** We used box plots and calculated interquartile ranges (IQR) to identify outliers and understand data spread. Specific features like distance from home and last transaction were highlighted as significant predictors of fraud.

**Results**
* **Decision Tree Performance:**
  * Accuracy: 98.8%
  * Error Rate: 1.2%
  * True Positive Rate (TPR): 88%
  * True Negative Rate (TNR): 99.8%

* **Logistic Regression Performance:**
  * Accuracy: 96%
  * Error Rate: 4%
  * TPR: 59%
  * TNR: 99%

**Conclusions**

The results underscore the effectiveness of machine learning in detecting fraudulent credit card transactions. The project demonstrates the potential of statistical models to improve transaction security and mitigate risks associated with credit card fraud.

**Contribution**

Contributions to this project are welcome. To discuss potential improvements or submit a pull request, please refer to the contributing guidelines or contact the project maintainers.

**License**

This project is licensed under the MIT License - see the LICENSE.md file for details.
