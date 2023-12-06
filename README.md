# Amazon_review_nlp


## NLP_Project_Amazon_review.ipynb :  
    data loading;
    data cleaning;
    cleaned_data.csv created;
    train, validation, test split;
    word vectorization ( count vectorizer, tfidf vectorizer)
    ML models (each model under 2 diff vectorizers): 
        Naive bayes , 
        Logistic Regression,
        SVM ( takes too long to run, might delete)
    DL models ( used Keras's text_to_sequence with Embedding Layer)
        LSTM (2 bidirectional layers, 2 epochs)
        MLP ( 2 dense layers, 2 epochs)
        
        
    (! note: models haven't be tuned, might need hyperparameters tuning for ML model, and need improving for DL models)

    

  ## cleaned_data.csv
  (! note: data cleaning process takes 45 mins to run, can use the cleaned_data.csv to start to run models from "start here" signal in notebook.)

  There is code in notebook to upload this file in google drive and use.

  cleaned_data.csv:  completed the NLP text cleaning process, has a cleaned_reviewText column  (string type)

