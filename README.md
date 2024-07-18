# Machine Learning Project

In this machine learning project, I explored the main machine learning algorithms included in the scikit-learn library. The goal of the project is to predict the future price movement of stocks based on historical data, specifically focusing on the past 10-day trend in closing values of the stocks. In addition I decided to implement two techniques  that ensured a robust and efficient model development, I implemented the following techniques:

* **Pipelines**: I leveraged pipelines to streamline the machine learning workflow. This allowed for the seamless integration of data preprocessing steps (i.e., scaling), feature engineering, and model training, making the entire process more organized and reproducible.

* **Cross-Validation Grid Search**: To optimize the performance of each machine learning algorithm, I employed cross-validation grid search. This technique systematically tuned hyperparameters for each model while assessing their performance using cross-validation. It ensured that the selected models were well-optimized and less prone to overfitting.

The machine learning algorithms I utilized in this project include:

1. Random Forest Classifier
2. Gradient Boosting Classifier
3. XGBoost Classifier
4. Logistic Regression
5. Support Vector Machine (SVM)
6. Naïve Bayes Classifiers:
   * MultinomialNB
   * GaussianNB
   * BernoulliNB
  
This project allow me to gain a deeper understanding of machine learning with python and of the scikit-learn library. More precisely, I focused my attention on the training of the algorithms. I was able to improve the accuracy of the algorithms by implementing new techniques (cross-validation, and grid search), this allowed me to keep refining the hyperparameters and achieve the best result possible. 

### Files Descriptions
* **Predicting Stock Prices Trend.ipynb**: Jupyter Notework of the project
* **stock_values_train.csv**: datasets of 100 well-known stock indices, with different stock metrics across a one year period (adjusted close value, close value, High, Low, Open, Volume);
* **stock_tweets_train.csv**: datasets of tweets about stock indices and the stocks they relate too;
* **test_samples.pkl**: pickle file that include a list of touples of dataset: first dataset is stock values for a 10/15 day period of a stock index, and the second dataset include tweets on that stock index of the same period; 
* **test_samples_raw.pkl**: ickle file that include a list of touples of dataset: first dataset is percent change of stock values for a 10/15 day period of a stock index, and the second dataset include tweets on that stock index of the same period; 


