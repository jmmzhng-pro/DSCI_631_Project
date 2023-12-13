# DSCI_631_Project
S&amp;P 500 Stock Price and FOMC Textual Data

**Securities Data Analysis and FOMC: Sentiment Analysis For a Predictive Model of S&P 500 Stock Price**

**Table of Contents:**

 - 1. Description
 - 2. Features 
 - 3. Installation 
 - 4. Usage 
 - 5. Configuration 
 - 6. Troubleshooting 
 - 7. Changelog
 - 8. Dependencies and Requirements
 - 9. Contact Information
 - 10. Acknowledgements

**Description**:
This project aims to develop a predictive model capable of forecasting changes in the S&P 500 stock price and therefore forecast economic turbulence of the US economy. We leverage two key data sources: textual data from the Federal Open Market Committee (FOMC), encompassing FOMC meetings, speeches, and meeting minutes, and numerical data from the S&P 500 stock. To extract valuable insights from the FOMC textual data spanning from 2008 to present, we conducted a sentiment analysis on FOMC meetings. Additionally, we trained a Bidirectional Encoder Representations from Transformers (BERT) model to perform sentiment analysis on the FOMC textual data. These analyses gather more understanding of the sentiment surrounding key economic discussions. Utilizing numerical data of the S&P 500 stock index, we developed a basic linear regression model to forecast the S&P 500 stock price from 2008 to the present, as well as produce numerous visualizations of trends in the S&P 500 through Exploratory Data Analysis (EDA). The goal of this project is to provide a valuable tool for forecasting stock market trends and understanding economic turbulence in the US economy.

## 1. Sentiment Analysis

### 1.2The FiGAS Sentiment Analysis (Script)

This script is designed for performing sentiment analysis on textual data. It utilizes various Python libraries and methods to analyze the sentiment expressed in text, 
providing insights into the overall emotional tone. 

### 1.2.1 Features of FiGAS
- **Sentiment Analysis**: The core functionality of this script is to evaluate the sentiment of given text using multiple sentiment analysis techniques.
- **Library Use**: It makes use of several Python libraries like `numpy`, `spacy`, `pandas`, and others for efficient processing and analysis.
- **Multiple Sentiment Sources**: The script integrates different sentiment analysis resources like `senticnet` and `sentiwordnet`.

### 1.2.2 Installation Requirements
- Python 3.x
- `numpy`
- `spacy`
- `pandas`
- `nltk`
- c.f. `get_sentiment.py` for other dependencies as specified in the script.
- download the scripts `sentibignomics.py` and `get_sentiment` from: https://github.com/consose/SentiBigNomics/tree/main/python
- Lastly, you will `senticnet.py`, senticnet 7 from: https://sentic.net/downloads/

### 1.2.3 Usage
1. Ensure all dependencies are installed.
2. Run the script with the required text data input.
3. The script will output sentiment analysis results.

### 1.2.4 Important Functions in FiGAS `get_sentiment`
- `safe_string_cast_to_numerictype`: Safely converts strings to numeric types.
- `FeelIt`: Main function for sentiment analysis, with options to specify the sentiment analysis resource.

### 1.2.5 Customizing `get_sentiment.py`
The script allows for various customizations including the choice of sentiment analysis resource. Modify the parameters as needed for your own specific use case, i.e. texts and word lists to include.

## 2. ARIMA
## 3. Prophet
## 4. LSTM

**Changelog:**
This is the second version of the project and **future changes will be recorded here.**

**Dependencies and Requirements:**
This project utilized the Yahoo Finance API. While all the data used in this project will be provided in the data dictionary, the Yahoo Finance API is accessible to the public and can be employed, as we did, with the yfinance module. It also used 

**Contact Information:**
For communication related to this project, please contact Jimmy Zhang (jz876@drexel.edu), Jonathan Watkins (jfw68@drexel.edu), or Jake Jarosik (jj3268@drexel.edu)

**Acknowledgements:**
https://github.com/consose/SentiBigNomics
https://towardsdatascience.com/fedspeak-how-to-build-a-nlp-pipeline-to-predict-central-bank-policy-changes-a2f157ca0434



 

