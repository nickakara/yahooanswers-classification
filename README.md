
  

# Yahoo Answers Classification Project

  

## Building and evaluating classification models using Machine Learning models

  

This project uses a Yahoo Answers dataset to train multiple machine learning models for accurately predicting a question's category. This project was designed to create, compare and evaluate machine learning architectures in both classification performance and processing time. 

  
  

## Table of Contents

  

- [Introduction](#introduction)

- [Packages Used](#packages-used)

- [Data](#data)

- [Methods](#methods)

- [Insights](#insights)

- [Remarks](#remarks)

  
  

## Packages Used

  

- Python

- Scikit-learn

- Pandas

- Matplotlib

  

- NLTK

NLTK was used extensively when testing preprocessing methodologies. The dataset requried extensive work and

NLTK provided lots of fucntionality

  

Sciklit-learn

ML tool that allows the training of classification models

  

## Data

  

Data used was derived from Yahoo! Answers, a defunct question-and-answer website that ran from 2005 to 2021. This data derived from the ‘Yahoo! Answers Comprehensive Questions and Answers version 1.0’ dataset found on the Yahoo Webscope website (https://webscope.sandbox.yahoo.com/catalog.php?datatype=l%20&guccounter=1). The original data contained over 4 million questions, and features include answers, categories and sub-categories. However, the dataset used for this study was a modified version using only categories, and contained only 320,000 questions.

  

The following categories are present in the dataset, and were used as labels for the classification model:

  

<ol>

<li>Society & Culture</li>

<li>Science & Mathematics</li>

<li>Health</li>

<li>Education & Reference</li>

<li>Computers & Internet</li>

<li>Sports</li>

<li>Business & Finance</li>

<li>Entertainment & Music</li>

<li>Family & Relationships</li>

<li>Politics & Government</li>

</ol>

  
  
  

<!-- More specifically, for each question, 3 categories were labelled, ranked in order of how related the categories are to each questions. As an example,

a question with the label of 4, 2 and 7 is most likely under the Education & Reference category, followed by Science & Mathematics, and Business & Finance. -->

  

## Methods




  

## Insights


<img width="625" alt="graph_eval" src="https://user-images.githubusercontent.com/91995206/232135517-ffcac6fc-494a-48e7-babe-b64da559f0c3.png">


LSTM, FastText (optimised) and Logistic Regression were the best-performing models for the classification. 

<img width="625" alt="Screenshot 2023-04-14 at 8 18 13 pm" src="https://user-images.githubusercontent.com/91995206/232136585-1e2031fa-81d2-4001-a276-de01263f7854.png">

However, when model training time is taken into consideration, Multinomial Naive Bayes, FastText (base model) and Logistic Regression are models with the best performance to training time ratio.


<img width="757" alt="sizevsscore" src="https://user-images.githubusercontent.com/91995206/232136023-f37bfaaf-2b89-484e-9d0d-facadb56c7e0.png">



Model performance increases as there are more samples to test. However, the rate of change in model accuracy starts plateauing when the sample size reached 60% (n=180412). As a result, model performance increased the most when training size is less than 100,000 questions.


  

## Remarks

It is important to note that this project was not primarily designed to identify models with the best classification performance, but rather to balance efficiency and computational resources. However, it should be emphasized that if the objective is to maximize the cost function solely based on accuracy, then deep learning models will be further evaluated, along with other models, to determine their potential to improve performance.
