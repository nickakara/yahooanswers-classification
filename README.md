
  

# Yahoo Answers Classification Project

  

## Building and evaluating classification models using Machine Learning models

  

This project uses a Yahoo Answers dataset to train multiple machine learning models for accurately predicting a question's category. This project was designed to create, compare and evaluate machine learning architectures in both classification performance and processing time. 

  
  

## Table of Contents

  

- [Introduction](#introduction)

- [Technologies](#technologies)

- [Data](#data)

- [Methods](#methods)

- [Results](#results)

- [Usage](#usage)

- [License](#license)

  
  

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

  

Describe the machine learning algorithms and techniques that were used in this project. How were they implemented? What parameters were used?

  

## Insights

  
LSTM, FastText (optimised) and Logistic Regression were the best-performing models for the classification. However, when model training time is taken into consideration, Multinomial Naive Bayes, FastText (base model) and Logistic Regression are models with the best performance to training time ratio.

Furthermore, the optimal number of sample was also looked at. Model performance increases as there are more samples to test. However, the rate of change in model accuracy starts plateauing when the sample size reached 60% (n=180412). As a result, model performance increased the most when training size is less than 100,000 questions.


  

## Usage

  

Provide instructions on how to use the model. Include any dependencies that need to be installed, and provide examples of how to run the model.

  