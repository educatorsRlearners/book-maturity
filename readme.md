# Book Maturity

## Motivation  
While there are several ways to measure the linguistic complexity of a text, I've yet to see a program that identifies a minimum age a reader needs to be for a particular book. Therefore, this project aims to meet this need. 
## Data Collection - Scraping [Common Sense Media Book Reviews](https://www.commonsensemedia.org/book-reviews)
* [0: Getting Search Pages](https://github.com/educatorsRlearners/book-maturity/blob/master/00_get_search_pages.ipynb)
* [1: Getting Links to the Book Titles](https://github.com/educatorsRlearners/book-maturity/blob/master/01_get_title_links.ipynb)
* [2: Collect Every Book Review](https://github.com/educatorsRlearners/book-maturity/blob/master/02_get_book_reviews.ipynb)
* [3: Extract Details from Each Review](https://github.com/educatorsRlearners/book-maturity/blob/master/03_get_book_details.ipynb)

## Inspect the Data
* [4: Exploratory Data Analysis](https://github.com/educatorsRlearners/book-maturity/blob/master/04_Split_Data_EDA.ipynb)

## Establish the Baseline Model
* [5: Naive Baseline](https://github.com/educatorsRlearners/book-maturity/blob/master/05_baseline.ipynb)  

## [XGBoost](https://machinelearningmastery.com/gentle-introduction-xgboost-applied-machine-learning) - aka "King of Kaggle"
* [6: Baseline XGBoost](https://github.com/educatorsRlearners/book-maturity/blob/master/06_baseline_xgboost.ipynb)  
* [7: XGBoost Version II](https://github.com/educatorsRlearners/book-maturity/blob/master/07_xgboost.ipynb)      
* [8: XGBoost Version III](https://github.com/educatorsRlearners/book-maturity/blob/master/08_xgboost_concat.ipynb)  


## [Long Short Term Memory](https://colah.github.io/posts/2015-08-Understanding-LSTMs/)
* [9: Baseline LSTM](https://github.com/educatorsRlearners/book-maturity/blob/master/09_baseline_lstm.ipynb)
* [10: LSTM Version II](https://github.com/educatorsRlearners/book-maturity/blob/master/10_lstm_title.ipynb)
* [11: LSTM Version III](https://github.com/educatorsRlearners/book-maturity/blob/master/11_lstm_plot.ipynb)
* [12: LSTM Version IV](https://github.com/educatorsRlearners/book-maturity/blob/master/12_lstm_csm_review.ipynb)
* [13: LSTM Version V](https://github.com/educatorsRlearners/book-maturity/blob/master/13_lstm_pntk.ipynb)
* [14: LSTM Version VI](https://github.com/educatorsRlearners/book-maturity/blob/master/14_lstm_concat.ipynb)

## Computer Vision - Can you judge a book by its cover?
* [15: Get All Covers](https://github.com/educatorsRlearners/book-maturity/blob/master/15_get_covers.ipynb)
* [16: Convolutional Neural Network (CNN)](https://github.com/educatorsRlearners/book-maturity/blob/master/16_analyze_covers.ipynb)


## Final Results
| Model       |Train MAE     |Test MAE     |
| :------------- |------------ |------------- |
| [Naive Baseline](https://github.com/educatorsRlearners/book-maturity/blob/master/05_baseline.ipynb) | n/a | 3.27  |
| [Computer Vision](https://github.com/educatorsRlearners/book-maturity/blob/master/16_analyze_covers.ipynb)| 2.69 | 2.50  |
| [LSTM Version II](https://github.com/educatorsRlearners/book-maturity/blob/master/10_lstm_title.ipynb)| 1.35 | 1.65  |
| [XGBoost Version III](https://github.com/educatorsRlearners/book-maturity/blob/master/08_xgboost_concat.ipynb)| 1.50 | 1.62|
| [LSTM Version VI](https://github.com/educatorsRlearners/book-maturity/blob/master/14_lstm_concat.ipynb)| 0.66| 1.04|


## Presenation

Finally, to watch a presenation of this project, please click below: 

[![](http://img.youtube.com/vi/BpOrMErz988/0.jpg)](http://www.youtube.com/watch?v=BpOrMErz988 "Using Machine Learning to Identify Text Maturity")