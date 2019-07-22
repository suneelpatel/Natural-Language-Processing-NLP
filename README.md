# NLP-using-Python
This repository will provide an overview and working knowledge of Natural Language Processing (NLP), using Python’s Natural Language Toolkit (NLTK) library and with Keras.

# Table of Content
1. Introduction to Text Mining 
2. Introduction to NLP
3. Introduction to NLTK Environment
4. Extracting, Cleaning and Preprocessing Text
5. Analyzing Sentence Structure
6. Text Classification


# 1. Introduction to Text Mining 
Text Mining is the process of deriving useful information from text.

### What is Text Mining?
* Text mining /Text Analytics is the process of driving meaningful information from natural language text.
* As, Text mining refers to process of driving high quality information from the text.
* Text mining is defined as the process of analysing text to pull out the relevant information for specific purpose.
* Text Mining usually involves the process of structuring the input text, driving pattern within the structured data, and finally evaluating and interpreting the output.


# 2. Introduction to NLP
NLP is a branch of data science that consists of systematic processes for analyzing, understanding, and deriving information from the text data in a smart and efficient manner. 

By utilizing NLP and its components, one can organize the massive chunks of text data, perform numerous automated tasks and solve a wide range of problems such as – automatic summarization, machine translation, named entity recognition, relationship extraction, sentiment analysis, speech recognition, and topic segmentation etc.

Natural Language Processing is manipulation or understanding text or speech by any software or machine. An analogy is that humans interact, understand each other views, and respond with the appropriate answer. In NLP, this interaction, understanding, the response is made by a computer instead of a human.

### Natural Language Processing Applications
Here’s a list of real-world applications that make use of NLP techniques:
* **Sentimental Analysis:** By implementing NLP Tech giants such as Amazon and Netflix, gain insights on their customers to enhance their products and make better recommendations.
* **Chatbot:** Chatbots are becoming popular in the field of customer service. A popular example is Eva the HDFC chatbot who has addressed over 3 million customer queries, interacted with over half a million unique users, and held over a million conversations.
* **Speech Recognition:** NLP has been used widely in speech recognition, we’re all aware of Alexa, Siri, Google assistant, and Cortana. They’re all applications of NLP.
* **Machine Translation:** The popular Google translator uses Natural Language Processing to process and translate one language to the other. It is also used in spell checkers, keyword search, information extraction.
* **Advertisement Matching:** NLP is also used in advertisement matching to recommend ads based on search history.


# 3. Introduction to NLTK Environment
NLTK is a leading platform for building Python programs to work with human language data. It provides easy-to-use interfaces to over 50 corpora and lexical resources such as WordNet, along with a suite of text processing libraries for classification, tokenization, stemming, tagging, parsing, and semantic reasoning, wrappers for industrial-strength NLP libraries, and an active discussion forum.

NLTK stands for Natural Language Toolkit. This toolkit is one of the most powerful NLP libraries which contains packages to make machines understand human language and reply to it with an appropriate response.

### Tokenize Words and Sentences with NLTK

#### What is Tokenization?
Tokenization is the process by which big quantity of text is divided into smaller parts called tokens.

Natural language processing is used for building applications such as Text classification, intelligent chatbot, sentimental analysis, language translation, etc. It becomes vital to understand the pattern in the text to achieve the above-stated purpose. These tokens are very useful for finding such patterns as well as is considered as a base step for stemming and lemmatization.

For the time being, don't worry about stemming and lemmatization but treat them as steps for textual data cleaning using NLP (Natural language processing). We will discuss stemming and lemmatization later in the tutorial. Tasks such as Text classification or spam filtering makes use of NLP along with deep learning libraries such as Keras and Tensorflow.

Natural Language toolkit has very important module tokenize which further compromises of sub-modules

### Word Tokenize
### Sentence Tokenize

#### Tokenization of words
We use the method word_tokenize() to split a sentence into words. The output of word tokenization can be converted to Data Frame for better text understanding in machine learning applications. It can also be provided as input for further text cleaning steps such as punctuation removal, numeric character removal or stemming. Machine learning models need numeric data to be trained and make a prediction. Word tokenization becomes a crucial part of the text (string) to numeric data conversion. Please read about Bag of Words or CountVectorizer. Please refer to below example to understand the theory better.


#### Tokenization of Sentences
Sub-module available for the above is sent_tokenize. An obvious question in your mind would be why sentence tokenization is needed when we have the option of word tokenization. Imagine you need to count average words per sentence, how you will calculate? For accomplishing such a task, you need both sentence tokenization as well as words to calculate the ratio. Such output serves as an important feature for machine training as the answer would be numeric.

# 4. Extracting, Cleaning and Preprocessing Text


# 5. Analyzing Sentence Structure


# 6. Text Classification
