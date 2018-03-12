# Email-Spam-Filtering
Email spam filtering with scikit - learn

Text mining (deriving information from text) is a wide field which has gianed popularity with the huge text data being generated.
Automation of a number of applications like sentiment analysis, document classification, topic classification, text summarization, machine translation, etc has been done using machine learning models.

Spam filtering is a beginner's example of document classification task which involves classifying an email as spam or non - spam (hum) mail. just like gmail.

I am providing data - set in above files you can use it.

## We will walk through the following steps to build this application:
### 1. Preparing the text data.
### 2. Creating word dictionary.
### 3. Feature extraction process
### 4. Training the classifier

## Preparing the text data
The data - set used here, is split into a training set and a test set containing 702 mails and 260 mails respectively, divided equally b/w spam and ham emials.

In any text mining problem, text cleaning is the first step where we remove those words from the document which may not contribute to the information we want to extract. Emails may contain a lot of undesirable characters like punctuation marks, stop words, digits, etc which may not be helpful in detecting the spam email. The emails in Ling - spam corpus have been already preprocessed in the following ways:
a) Removal of Stop Words - stop words like "and", "the", "of", etc are very common in all english sentences and are not very meaningful in deciding spam or legitimate status, so these words have been removed from the emails.

B) Lemmatization - It is the process of grouping together the different inflected forms of a word so they can be analysed as a single item. For example, "include", "includes", and "included" would all be represented as "include". 
