"CUSTOMER REVIEW SENTIMENT ANALYSIS"

DESC:
    *The idea of this project is to analyze the sentiment of the reviews submitted by the customers.
    *The ML model is built in both VADER and ROBERTa (BERT) frameworks in order to compare the results.
    *The Dataset used in this project is "Amazon-fine-food-review" imported from Kaggle.

FRAMEWORKS:
    Natural Language Processing frsmeworks
      1) VADER (Valence Aware Dictionary for Sentiment Reasoning)
      2) ROBERTa (Robustly Optimized BERT Pre-training Approach)
      3) Transformer model
LIBRARIES:
      1)pandas
      2)numpy
      3)matplotlib
      4)seaborn
      5)nltk
      6)AutoTokenizer
      7)AutoModelForSequenceClassification
      8)softmax
      
MODEL:
      In the model after importing the data and setting up the Libraries, A smaple data is taken from the entire Dataset to begin modelling
      STEP 1. The Sentiment Analyser in from NLTK removes the stop words and each word is scored and combined to a totla score
      STEP 2. Plot the results 
      STEP 3. Using a model trained of a large corpus of data and Transformer model accounts for the words but also the context related to other words
      STEP 4. Combining and comparing the results of both frameworks by visualizing them
      STEP 5. Reviewing Examples(additional).
