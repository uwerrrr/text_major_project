# text_major_project
The main task of the this project is to build and compare predictive models which are to predict emotions of tweets. The emotions are "anger","fear","sadness" and "joy".

Done by Oscar NGUYEN.

## Project structure
This notebook is for the major project submission for COMP8220, on the language dataset and task. 

It contains the following main sections:
- Preparation
  - Data exploration
  - Data cleaning 
- Conventional ML models
  - Data transformation
    - TF.IDF - vectorzing text data   
  1. Naive Bayes Classifier
  2. Random Forest Classifier
  3. Logistic Regression model
  4. LinearSVC model

- Deep learning models
  - Data transformation
    - vectorize training data
    - one-hot encoding label data
    - set up embeding layer (GloVe and normal)
  - 6 models in total depeending on the training data:
    1. Model using normal embeding layer with processed data
    2. Model using normal embeding layer with original data
    3. Model using GloVe embeding with processed data with trainable = False
    4. Model using GloVe embeding with processed data with trainable = True
    5. Model using GloVe embeding with original data with trainable = False
    6. Model using GloVe embeding with original data with trainable = True
- Discussion of Model Performance and Implementation

Note:
- Each model section also contains observation part at the end which highlights my observation from the process of training the models.
- Since this notebook is lengthy, it is suggested to use table of content sidebar for better navigation.

## Project metadata

### Access
You can access the project using Google Colab with this [link](https://colab.research.google.com/drive/1N9Iy4mfvcwihaAXFYW5lri77VR2bipM7#scrollTo=Pwq6jYZIrGgU).

### Tech stack:
- Python
