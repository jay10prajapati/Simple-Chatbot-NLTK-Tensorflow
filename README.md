# Simple-Chatbot-NLTK-Tensorflow


**Deep Learning Specialization (overview 5 Courses)**

**Note:** This simple chatbot is build mainly using python NLTK and Tensorflow libraries. The model is build on a limited dataset contains arround 10000 sentences in the question-answer format. 

**Approch to build chatbot:** 
  * Preprocess data by removing unnecessary stopwoards, punctuations and convert it in such a format that model can use.
  * Filter data base on some category and build a _Bag Of Words(BOW)_ and _Documents_ as a training data.
  * Build a supervised classification model using _3 Layer Fully Connected Nueral Network_. 
  * Build a response generator which will give appropriate responce in two steps:
    * Predict class of user's input
    * Fetch more appropriate responce within a class using _Cosine Simillarity_
 
 **Project Structure:**
 It mainly contains to jupyter notebook.
  
  1. PreprocessData_ModelBuild.ipynb :      
      * It will do all requiered pre-processing of data.
      * Build necessary Bag Of Words(BOW), Documents, Dictionaries as a Training Data.
      * Build a model on top of this data.
      * Save all intermediate data format, model and thier checkpoints for future use.
  
  2. Response_Generator.ipynb :      
      * Restrive model and data from priveously saved checkpoints
      * Predict user's input class
      * Generate appropriate response using Cosine Simillarity
      

*************************************************************************************************************************************
