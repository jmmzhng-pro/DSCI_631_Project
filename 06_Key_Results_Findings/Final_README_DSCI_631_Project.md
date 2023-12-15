
# DSCI 631 Project: Using Economic Indicators and Sentiment Analysis of Economic Policies to Build a Predictive Model of S&P 500 Stock Price

## Project Overview
This project focuses on advanced data analysis techniques, integrating time series modeling, sentiment analysis, feature aggregation and selection, and data acquisition with exploratory data analysis (EDA). It's designed to provide comprehensive insights into financial texts and stock price prediction, specifically the S&P 500 stock price and FOMC textual data analysis for prediction of stock changes.

## Table of Contents
1. Project Description
2. Data Acquisition and Exploratory Data Analysis (EDA)
3. Sentiment Analysis and Feature Aggregation & Selection
4. Time Series Modeling: ARIMA, Prophet, and LSTM
5. Installation and Usage
6. Configuration and Troubleshooting
7. Dependencies and Requirements
8. Contact Information
9. References

### 1. Project Description
This master project aims to develop a predictive model capable of forecasting changes in the S&P 500 stock price based on sentiment analysis of FOMC textual data and advanced time series modeling.

### 2. Notebook 1: Data Acquisition and Exploratory Data Analysis (EDA)
This part covers data acquisition techniques and initial exploratory data analysis methods. It's structured to facilitate understanding of data gathering and analysis for financial datasets.

### 3. Notebook 2: Sentiment Analysis and Feature Aggregation & Selection
This section delves into the methodologies of sentiment analysis, focusing on the sentiment analysis of financial texts. It includes specific techniques like Loughran and McDonald and FiGAS (Fine-Grained Aspect-based Sentiment analysis).

### 4. Notebook 3: Time Series Modeling: ARIMA, Prophet, and LSTM
Time series modeling is explored through ARIMA, Prophet, and LSTM models. This section provides an in-depth understanding of these models and their application in predicting financial time series data.

### 5. Installation and Usage
To run the notebooks associated with this project, you need to have Python installed along with several libraries. The following steps outline the installation process:
- Ensure you have Python installed. The notebooks were developed using Python 3.8.
- It's recommended to use a virtual environment (like `venv` or `conda`) to manage the dependencies.
- Install necessary Python libraries by running `pip install <library-name>`. The required libraries include:
  - `pandas`, `numpy`, `matplotlib`, `seaborn`, `scikit-learn`
  - For the ARIMA, Prophet, and LSTM notebook: `tensorflow`, `datetime`
  - For the Sentiment Analysis notebook: `utm`, `lxml`, `fastavro`, `h5py`, `spacy`, `nltk`, `joblib`, `toolz`, `textblob`, `gensim`

### 6. Configuration and Troubleshooting
- If you encounter any issues with library versions, check the specific versions used in the notebooks and adjust your environment accordingly.
- For TensorFlow-related errors, ensure that you have a compatible version of TensorFlow installed. You may also need to configure your environment to support TensorFlow's requirements, particularly if using GPU acceleration.

### 7. Dependencies and Requirements
The main dependencies for the project include:
- Data handling and visualization: `pandas`, `numpy`, `matplotlib`, `seaborn`
- Machine Learning and Modeling: `scikit-learn`, `tensorflow`
- Sentiment Analysis: `utm`, `lxml`, `fastavro`, `h5py`, `spacy`, `nltk`, `joblib`, `toolz`, `textblob`, `gensim`

### 8. Contact Information
For communication related to this project, please contact Jimmy Zhang (jz876@drexel.edu), Jonathan Watkins (jfw68@drexel.edu), or Jake Jarosik (jj3268@drexel.edu)

### 9. References
Board of Governors of the Federal Reserve System. (n.d.). Federal Open Market Committee (FOMC). Federal Reserve. Retrieved [July 22, 2023], from https://www.federalreserve.gov/monetarypolicy/fomc.htm


Consoli, S.; Barbaglia, L.; and Manzan, S. (2020). Fine-grained, aspect-based semantic sentiment analysis within the economic and financial domains. In Proceedings - 2020 IEEE 2nd International Conference on Cognitive Machine Intelligence, CogMI 2020, 52 – 61.

Consoli, S.; Barbaglia, L.; and Manzan, S. (2021). Explaining sentiment from Lexicon. In CEUR Workshop Proceedings, volume 2918, 87 – 95.

Consoli, S.; Barbaglia, L.; and Manzan, S. (2022). Fine-grained, aspect-based sentiment analysis on economic and financial lexicon. Knowledge-Based Systems, 247: 108781

Conti-Brown, P. (2016). The Power and Independence of the Federal Reserve. Princeton: Princeton University Press. https://doi.org/10.1515/9781400873500

Esri. (2023). How change point detection works. ArcGIS Pro Documentation. Retrieved from https://pro.arcgis.com/en/pro-app/latest/tool-reference/space-time-pattern-mining/how-change-point-detection-works.html

Facebook. (2023). Quick Start. In Prophet Documentation. Retrieved from https://facebook.github.io/prophet/docs/quick_start.html

Hansen, K. B. (2021). Model Talk: Calculative Cultures in Quantitative Finance. Science, Technology, & Human Values, 46(3), 600–627. https://doi.org/10.1177/0162243920944225

Jabbri Maleki, F. (2023). Metrics. In Time Series Exploration with Python: A Journey from Traditional to Advanced Forecasting Models. Retrieved from https://faridjb.github.io/Time-Series-Exploration/chapters/chapter_09.html

Kutzkov, K. (2023, July 31). ARIMA vs Prophet vs LSTM for Time Series Prediction. Neptune.ai. Retrieved from https://neptune.ai/blog/arima-vs-prophet-vs-lstm

Krieger, M. (2021, February 19). Time series analysis with Facebook Prophet: How it works and how to use it. Towards Data Science. Retrieved from https://towardsdatascience.com/time-series-analysis-with-facebook-prophet-how-it-works-and-how-to-use-it-f15ecf2c0e3a 

Ma, E. (2018, November 3). Understand how to transfer your paragraph to vector by doc2vec. Towards Data Science. https://towardsdatascience.com/understand-how-to-transfer-your-paragraph-to-vector-by-doc2vec-1e225ccf102

Mehdian, S., Rezvanian, R., & Stoica O. (2019). "The Effect Of The 2008 Global Financial Crisis On The Efficiency Of Large U.S. Commercial Banks," Review of Economic and Business Studies, Alexandru Ioan Cuza University, Faculty of Economics and Business Administration, issue 24, pages 11-27, December.

Mikolov, T., Chen, K., Corrado, G. & Dean, J. (2013). Efficient Estimation of Word Representations in Vector Space. CoRR, abs/1301.3781.

Mukhiya, S. K., & Ahmed, U. (2020). Hands-on exploratory data analysis with Python: Perform EDA techniques to understand, summarize, and investigate your data. Packt Publishing.

Takahashi, Y. (2020, November 13). FedSpeak — How to build an NLP pipeline to predict central bank policy changes: A guide to analyse policymakers’ conversations by deep neural network. Towards Data Science. https://towardsdatascience.com/fedspeak-how-to-build-a-nlp-pipeline-to-predict-central-bank-policy-changes-a2f157ca0434

Tensorflow. (2023). Time series forecasting. TensorFlow Core. Retrieved from https://www.tensorflow.org/tutorials/structured_data/time_series
Stocker, M., Lakatos, C., Ohnsorge, F., & Kose, M. A. (2017, February 27). Understanding the global role of the US economy. CEPR. https://cepr.org/voxeu/columns/understanding-global-role-us-economy

