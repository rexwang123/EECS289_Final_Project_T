# Word Embedding
Week 10 of EECS16ML covers the topic of Natural Language Processing. In order to transform text into fixed-length and numerical form that computer algorithms favor, and at the same time retaining the rich meanings included in the context, several word embedding techniques have been developed to meet the challenge. Assuming prior knowledge in vector space, multivariate differential, PCA/SVD, and fundamental understanding of classification tasks from EECS 16A/B, CS 61B, and previous weeks in EECS 16ML, we hope students to understand both types of count-based and predictive methods along with several popular algorithms with our 
repository. 

*See [Updates](#updates) for fixes made based on feedbacks and comments received

## Learning Objective
  Students will learn the following word embedding algorithms as well as their applications in real machine learning tasks. Students will understand the mechanisms behind those algorithms by looking at the notes/slides and/or implementing and using these algorithms by themselves. Students will also be introduced to efficient libraries to directly use these algorithms, including Pandas, Skit-Learn and Gensim. In addition to building word embedding models, students will also learn how to prepare the training data with those models and apply them to a real machine learning task, which in our designed assignment is a movie review sentiment analysis on IMDB dataset.
  
  * Count-based
    * Bag of Words
    * TFIDF
    * Co-occurrence matrix
  
  * Predictive
    * Word2Vec
    * GloVe
    * Bert (only experimental)

## Pre-requisites/Prior knowledge 
  * 16A:
    * Vector Space
    * Linear Transformation
    * Eigendecomposition
    * Classification
  * 16B: 
    * Multivariate Differential
  * 61B:
    * Classes/Object Methods
    * Lists/Arrays
  * 16ML - Week 1: 
    * NumPy
    * Pandas 
  * 16ML - Week 2: 
    * Spliting training/test data
    * Scikit-Learn (SVM) for classification task 
    * Implementing Stochastic Gradient Descent (for Word2Vec, GloVe)
  * 16ML - Week 3: 
    * SVD/PCA for dimension reduction
  * 16ML - Week 5:
    * Intro to MLP's (for Word2Vec)
    * Implementing Backpropagation (for Word2Vec)
  * 16ML - Week 8:
    * How to use pre-trained models  (for Bert)
    * Pytorch/Tensorflow Tutorial (for Bert)
  

## Repository Usage

  1. Clone this repository to your personal workspace.
  ```
    git clone https://github.com/yux121/EECS289_Final_Project_T.git
  ```
  
  2. Download [Data.zip](https://drive.google.com/file/d/14mFmHL-dHXICgi2jIRpnbOqVPsMz2QSa/view?usp=sharing) that includes data files, place it inside `Assignment/`, then unzip.
  
  3. Read `Notes.pdf` and `Slides.pdf` for necessary concepts to complete the assignment.
  
  4. Inside `Quiz/`, use `Quiz.pdf` along with `Quiz_solution.pdf` to test your knowledge.
  
  5. Inside `Assignment/`, complete `Assignment.ipynb` and use `Assignment_solution.ipynb` to self-assess performance.


## Updates

* Notes and Slides:
  * Added transition/motivation between count-based approaches and predictive models
  * Added CBOW/Skip Gram use case comparison in Word2Vec
* Assignments:
  * Added an overview of the whole assignment at the beginning
  * Provided more comments/explanations on data cleaning process 
  * Added more comments/explanations for transitions for the whole assignment in general
  * Removed parts of BoW implementation to avoid overlapping with BoW team
  * Reworded BoW part and ask students to compare results of different n-grams
  * Added confusion matrix visualizations
  * Added visualizations of loss vs #epoch trained
  * Provided comparison between CBOW and Skip Gram by two ways: 1) let them predict close words respectively. 2) use them as different embedding methods for classification task

  

