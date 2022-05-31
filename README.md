# Bangladesh's Judicial Data Analysis and Classification Using Machine Learning.

## Abstract

Laws protect our general safety and defend our rights as citizens against abuse by others, organizations, and the government itself. To utilize laws, we must first 
understand them, which necessitates a comprehensive inspection and identification of the connections between them. Due to the increased availability of documents in 
digital form and the resulting need to arrange them, automatic categorization (or classification) of texts into preset categories has seen a surge attention in the 
last ten years. We used NLP (Natural language processing) to try to uncover a meaningful connection between Bangladesh's laws and cluster them into groups for better 
understanding. \textbf{bdlaws.minlaw.gov.bd}'s data was compiled into a dataset and used to categorizing Bangladesh's judicial law. The  Preprocessing steps (Removing 
Stop words, Removing punctuation's, Tokenize, Weighting), as well as the text's representation structure, are critical for dealing with text without artifacts. The study
method to the topic is based on machine learning techniques: a generic inductive process learns from a group of preabeled documents that are extracted using unsupervised
(Elbow method, K-mean clustering) learning to automatically build a classifier for the classification. The proposed system had a classification accuracy of 52\% percent.
Precision, Recall, and F1-score are 55\% percent, 56\% percent, and 52\% percent, respectively. 

## Result Evaluation

We examined a few data sets after structuring the model and got to the conclusion that our model works alright, however the accuracy is limited owing to data limitations.
Below are the test data and the projected class for that data:

| Test data        | Classified classes |
| :-----           | :-----             |
| Whoever makes or mends, or performs any part of the process of making or mending, or buys, sells or disposes of,
  any die or instrument, for the purpose of being used, or knowing or having reason to believe that it is intended 
  to be used, for the purpose of counterfeiting coin, shall be punished with imprisonment of either description for 
  a term which may extend to three years, and shall also be liable to fine. |'bangladesh','coin','counterfeit','counterfeiting','government','issued','knowingly','punished',
  'stamp','war' |
