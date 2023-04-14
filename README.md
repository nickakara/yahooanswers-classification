
# Yahoo Answers Classification Project

## Building and evaluating classification models using Machine Learning models

This project uses a Yahoo Answers dataset to train multiple machine learning models for accurately predicting a question's category. It involves extensive data preparation and cleaning using NLP and preprocessing techniques, as well as the evaluation of multiple classification models to determine which one performs best for this particular dataset. This project was originally aimed at creating models that optimise both prediction and processing performances


## Table of Contents

- [Introduction](#introduction)
- [Technologies](#technologies)
- [Data](#data)
- [Methods](#methods)
- [Results](#results)
- [Usage](#usage)
- [License](#license)

## Introduction

In this section, provide a brief overview of the project, its purpose, and the problem it addresses. You can also include any background information that might be relevant.

## Packages Used

List the technologies that were used in this project. For example:

- Python
- Scikit-learn
- Pandas
- NumPy
- Matplotlib

## Data

Data used was derived from the ‘Yahoo! Answers Comprehensive Questions and Answers version 1.0’ dataset found on the Yahoo Webscope website (https://webscope.sandbox.yahoo.com/catalog.php?datatype=l%20&guccounter=1). The original data contained over 4 million questions, and features include 
answers, categories and sub-categories. However, the dataset used for this study was a modified version using only categories. The following categories 
are used:

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


More specifically, for each question, 3 categories were labelled, ranked in order of how related the categories are to each questions. As an example, 
a question with the label of 4, 2 and 7 is most likely under the Education & Reference category, followed by Science & Mathematics, and Business & Finance.

Describe the data that was used in this project. Where did it come from? How was it collected? What format is it in? How was it preprocessed?

## Methods

Describe the machine learning algorithms and techniques that were used in this project. How were they implemented? What parameters were used?

## Results

Describe the results of the project. What metrics were used to evaluate the performance of the model? How well did it perform? Include any visualizations that might be helpful.

## Usage

Provide instructions on how to use the model. Include any dependencies that need to be installed, and provide examples of how to run the model.

## License

Specify the license under which the project is released. For example:

