# EECS289_Final_Project_T
Week 10 of EECS16ML covers the topic of Natural Language Processing. In order to transform text into fixed-length and numerical form that computer algorithms favor, and at the same time retaining the rich meanings included in the context, several word embedding techniques have been developed to meet the challenge. We hope students to understand both types of count-based and predictive methods along with several popular algorithms in our repository. 

## Learning Objective
  Students will learn the following word embedding algorithms as well as their applications in real machine learning tasks. Students will understand the mechanisms behind those algorithms by looking at the note/slide and/or implementing these algoirthm by themselves. Students will also be introduced efficient libraries to directly use thes algorithms, including Pandas, Skit-Learn and Gensim. In addition to building word embedding models, students will also learn how to prepare the training data with those modes and apply to the real machine learning task, movie sentiment analysis on IMDB dataset, in this assignment.
  
  * Count-based
    * Bag of Words
    * TFIDF
    * Co-occurance matrix
  
  * Predictive
    * Word2Vec
    * GloVe (need Co-occurrence matrix)
    * Bert

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
    * Implementing Stochastic Gradient Descent (for Word2Vec, GloVe and Bert)
  * 16ML - Week 3: 
    * SVD/PCA for dimension reduction

## Repository Usage

  1. Clone this repository to your personal workspace.
  ```
    git clone https://github.com/yux121/EECS289_Final_Project_T.git
  ```
  
  2. Download [Data.zip](link) that includes data files, place it inside `Assignment/`, then unzip.
  
  3. Read `Notes.pdf` for necessary concepts to complete the assignment.
  
  4. Inside `Quiz/`, use `Quiz.pdf` along with `Quiz_solution.pdf` to test your knowledge.
  
  5. Inside `Assignment/`, complete `Assignment.ipynb` and use `Assignment_solution.ipynb` to self-assess performance.
