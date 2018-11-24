# RMA_Prediction
This contains the notebooks describing the creation process of a Binary Text Classification Model to predict RMA (Return Merchandise Authorization) probability from the problem description supplied by the user.

### Problem Statement in Detail
Devise a solution to assist the engineers dealing with accepting or rejecting RMA (Return Merchandise Authorisation) requests submitted by general user of any product or service.

### Probable Approach
- Try to predict the chances of avoidability of a request from the historical data of previous requests
- Try to integrate the predictive model into a chatbot solution to assist the engineers in real-time
- Operationalise and Monitor the solution as microservices with development and enhancement design for each component

The contents of the repository are as per following:
- <i>Notebooks</i> : Contains the notebook files describing the process of creation of the model to predict the avoidability of a case from the raw text provided by the user. It has been modularised into the following components-
  - <b>Text Cleaner Module</b>:-
  - <b>Text EDA Module</b>:-
  - <b>Word Embedding Module</b> :-
  - <b>Prediction Model Module</b> :-
