# Steps followed

## High-level working:
- File 1:
    1. Load raw datasets
    2. Perform EDA
    3. Perform Data Cleaning
    4. Save clean datasets as files

- File 2:
    1. Load clean datasets
    2. Perform feature engineering with different methods
    2. Divide datasets as appropriate
    3. Train models
    4. Test models
    5. Compare models and choose the best one

- File 3:
    1. Load clean datasets
    2. Divide datasets as appropriate
    3. Tune the parameters for the chosen best model to get the best result
    4. Save the final file

## Primary EDA
* View the data samples
* View the data shape
* Compare the distribution of labels of training dataset
* Compare the distribution of tweet lengths for different training data and the test data

**done**

## Data Preprocessing
* Remove user handles
* Remove urls
* Tokenize words (Tweet tokenizer)
* Remove punctuation
* Remove words with length less than 2/3
    - Add another dimention to data and compare to decide

**tweet_id label orig_tweet tweet_2_rem tweet_3_rem**

## Data Processing
* Stem vs Lemmatize words?
    * Porter Stemmer
    * Snowball Stemmer
* Lemmetization
    * test nltk pos tagger
    * test spacy pos tagger
* Remove most frequently and least frequently occurring x% words (stopwords)?
    * named entity recognition
    * view the stopwords in the data to decide if removing is a good idea
    * modifying existing stopwords corpus
* SMOTE balancing vs taking imbalanced dataset
    - Take both kinds of data and train with models

## Secondary EDA
* Wordcloud?
* FreqDist of words & hashtags

## Feature Engineering
* BOW
* TF-IDF
* Word2Vec

## Models

