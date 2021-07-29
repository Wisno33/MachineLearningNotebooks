# MachineLearningNotebooks
A collection of small machine learning projects.

The projects in this repository are all written in Jupyter Notebooks. This repository is not limited to any particular model or dataset type. Requirements such as the dataset and modules are listed for each notebook. Many of the notebooks have extensive markdown, therefore their section of the README will be minimal on the description.

## Pulsar Stars 

This project deals with the detection of pulsar stars. The dataset is structured data (csv), several models were utilized they are as follows: Logistic Regression, K Neighbors Classifier, Decision Tree Classifier, Random Forest Classifier, and Support Vector Classifier (SVC). The models overall performed well with the Random Forest Classifier producing the best results, 98% accuracy. I as of now have no future plans for this project.

### Dataset and Required Modules

Dataset: https://www.kaggle.com/spacemod/pulsar-dataset

Requirements: <br />
- Python 3.7.10 <br />
- numpy 1.20.2 <br />
- pandas 1.2.4 <br />
- scikit-learn 0.24.2 <br />

## Malaria Detection

This project does preprocessing and then evaluates image data of cells to detect if they contain the Malaria parasite. The model used is a Constitutional Neural Network (CNN). The images were run on the model in two forms one with little preprocessing, and once more with significant feature engineering. The feature engineering produced a noticeable improvement on this dataset. The first iteration had a 81% accuracy as it started to over fit the training data. The second iteration with the feature engineering produced a 95% accuracy. If any project would be a candidate for a complete implementation it would be this model.

### Dataset and Required Modules

Dataset: https://www.kaggle.com/iarunava/cell-images-for-detecting-malaria

Requirements: <br />
- Python 3.7.10 <br />
- matplotlib 3.3.4 <br />
- numpy 1.20.2 <br />
- opencv 3.4.2 <br />
- scikit-image 0.18.1 <br />
- scikit-learn 0.24.2 <br />
- tensorflow 2.0.0 <br />

## Question Answer

This project aims to create a model capable of answering passage based questions with a true of false answer. At the time of this project I did not realize the difficulty of this problem. The dataset is text based composed of a question, title, answer, and passage. A recurrent neural network (RNN) was utilized, but despite many alterations produced less than desirable results. The final accuracy was 61%, which due to the dataset distribution (60/40). The conclusion here is that the model learned the distribution and nothing else. With better feature engineering, and layers that can recognize key words from the question and passage, then relate them may improve the model. At the time of making this model, there were some new natural language processing layers in testing.

### Dataset and Required Modules

Dataset: https://github.com/google-research-datasets/boolean-questions

Text vectorization file: https://nlp.stanford.edu/projects/glove/ glove.840B.300d.txt

Requirements: <br />
- Python 3.7.10 <br />
- matplotlib 3.3.4 <br />
- numpy 1.20.2 <br />
- scikit-learn 0.24.2 <br />
- scipy 1.6.2 <br />
- tensorflow 2.0.0 <br />
