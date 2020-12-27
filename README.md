# Twitter-Sentiment-Prediction

This project is intended to get a basic understanding of sentiment prediction. As usual, the process is divided into 3 main parts :
<ol>
<li> Fetching Data </li>
<li> EDA & Pre processing </li>
<li> Modelling </li>
</ol>
This project does not dwelve into the deployment part of the machine learning work as illustrated below. 

<ol>
  <li> Fetching Data: The training and test data is available in nice csv format. I just load them using pandas. </li>
  <li> EDA & Pre processing: This code does some preliminary EDA. I have tagged my observations and comments in the notebook as I go through the process. For preprocessing, I have used Bag-of-words encoding, TF-IDF, OHE, Word2Vec and Doc2Vec preprocessing methods. Aim is to compare how each of them performs when given as an input to same algorithm while training
    <li> Modelling: This part of the code is where I go through various pre processed inputs and check which performs best for my use case. Then I proceed to do some hyperparameter tuning to get better results from the same input. </li>
</ol>

## Path forward ##
This project was done to gain a basic understanding of sentiment prediction problem. This leaves a lot of questions unanswered like if there is a way to extract more features from the data?, using deep learning architectures to achieve better performance than XGBoost, understanding why a method of preprocessing works/does not work etc. 
