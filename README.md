# NI Language Classifier

<img width="1180" alt="Screenshot 2024-04-10 at 10 31 13" src="photo.jpg">


## Description

This project is part of our Natural Language Processing (NLP) class. The goal is to apply well-known models to perform a widely used task: classification of languages in a text corpus.

## Meaning 

In this project, we address the problem of language identification in a given text corpus. Our objective is to utilize the knowledge gained during our NLP course to develop a language classification model. We explore various NLP approaches and methods to optimize language detection accuracy. This project falls within the fundamental domain of automatic language processing and serves as a practical application of text classification techniques.

To tackle this problem, we started with a classical Machine Learning approach before experimenting with more advanced models like RoBERTa and BERT.

## To keep in mind

This project was very hard to run in the case where you don't have a GPU. This was the main issue in our case, obliging us to use less epochs and by consequence leading to a smaller accuracy.

## Collaborators
- [@irenedagherr](https://github.com/irenedagherr)
- [@Nancy-222](https://github.com/Nancy-222)

## More Details

This project contains four main .ipynbs. And a latex document

## Dataset

To train and evaluate our model, we used two CSV files:

-test_without_labels.csv: A test dataset containing texts to be classified, but without labels.

-train_submission.csv: A training dataset with labeled texts, used for training the model.



## Installation
To run this project, follow these steps:

1-Clone the Repository : git clone https://github.com/your-repo/NI-Language-Classifier.git 
cd NI-Language-Classifier

2-Create a virtual environment
python -m venv venv
source venv/bin/activate  # On Windows use: venv\Scripts\activate

3-Run the jupyter notebook : jupyter notebook

## Project Status


We welcome feedback and contributions from the community! If you encounter any issues or have suggestions for improvement, please let us know by opening an issue on GitHub or reaching out to us on our community forums.




