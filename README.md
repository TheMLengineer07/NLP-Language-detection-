# NLP Language detection using Bag of Words

* Natural Language Processing(NLP) is a crucial field in arificial intelligence(AI) that enables computers to understand,interpret and manipulate human 
  language. One key aspect of NLP is language detection,Which is essentail for tasks like machine translation,sentiment analysis and chatbot development.

# Objective

* The primary objective of this project is to develop an NLP-based Language Detection Model using the Bag of Words (BoW) technique. By leveraging text- 
  processing methods, we classify text snippets based on their language.

# Dataset Description

# Dataset overview 
* For this project, use this link (https://github.com/TheMLengineer07/NLP-Language-detection-/blob/main/language.csv) dataset, which contains multiple text samples in different languages.

# Dataset Preprocessing
 To ensure accuracy,we clean and preprocess the text by:

* Removing special characters: Cleansing unwanted symbols, punctuation, etc.
* Lowercasing: Normalizing text for uniformity.
* Tokenization: Splitting sentences into individual words.
* Stop-word removal: Eliminating common words that don’t contribute to language detection.

# Methodology

# Bag of Words Approach

*The Bag of Words technique represents textual data as numerical values by creating a word frequency vector. This approach helps transform raw text into 
 a structured format suitable for machine learning models. 
 
# Feature Exreaction
* We use CountVectorizer from sklearn.feature_extraction.text to convert text into a word frequency matrix.
* Each document (text sample) is represented by a sparse matrix containing word occurrence frequencies

# Model Selection
  For classification, we experiment with various machine learning models:
* Naïve Bayes model is used in this project because it is best for text classification due to its probabilistic nature

# Result and Analysis

# Model Performance
  We analyze the performance based on classification metrics:
* Accuracy: Measures overall correctness.
* Confusion Matrix: Visualizes misclassification rates.
* Precision & Recall: Evaluates how well the model distinguishes languages

# Challenges
* Handling similar word structures across multiple languages.
* Improving accuracy for low-resource languages.

# Conclusion and Future Scope

# Summary
* The project successfully detects text language using Bag of Words.
* Naïve Bayes provides high accuracy due to its probabilistic nature.

# Future Work
* Experimenting with TF-IDF for better feature weighting.
* Implementing Deep Learning models (LSTMs, Transformers) for improved accuracy.

  


