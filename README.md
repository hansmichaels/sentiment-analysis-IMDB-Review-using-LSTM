# Sentiment Analysis on IMDB Reviews using LSTM and Keras

<b>Sentiment Analysis</b> is a classification of emotions (in this case, positive and negative) on text data using text analysis techniques (I use LSTM).

<b>LSTM</b> (Long Short-Term Memory) is one of the Recurrent Neural Network (RNN) architecture used in Deep Learning.

<b>Keras</b> is an open-source Python Deep Learning library, that could be run on Tensorflow back-end.


### Dataset
<hr>
In this work, I use <a href="https://www.kaggle.com/lakshmi25npathi/imdb-dataset-of-50k-movie-reviews">50.000 IMDB Movie Reviews from Kaggle</a>.
This dataset contains 2 columns, where the first column is the list of movie reviews and the second column is the list of sentiments (positive and negative). It is split equally between the positve and negative data.

### Architecture
<hr>
<ol type="1">
    <li>Embedding Layer</li>
    <li>LSTM Layer</li>
    <li>Dense (activation function using Sigmoid)</li>
    <li>Optimizer: Adam, Loss Function: Binary Crossentropy</li>
</ol>
    

### References
<hr>
<li><a href="https://www.tensorflow.org/api_docs/python/tf/keras">
    https://www.tensorflow.org/api_docs/python/tf/keras</a>
</li>
<li><a href="https://github.com/sanjay-raghu/sentiment-analysis-using-LSTM-keras/blob/master/lstm-sentiment-analysis-data-imbalance-keras.ipynb">
    https://github.com/sanjay-raghu/sentiment-analysis-using-LSTM-keras/blob/master/lstm-sentiment-analysis-data-imbalance-keras.ipynb</a>
</li>
<li><a href="https://towardsdatascience.com/sentiment-analysis-using-lstm-step-by-step-50d074f09948">
    https://towardsdatascience.com/sentiment-analysis-using-lstm-step-by-step-50d074f09948</a>
</li>
<li><a href="https://www.kaggle.com/ngyptr/lstm-sentiment-analysis-keras">
    https://www.kaggle.com/ngyptr/lstm-sentiment-analysis-keras</a>
</li>
<li><a href="https://www.youtube.com/watch?v=qpb_39IjZA0">
    https://www.youtube.com/watch?v=qpb_39IjZA0</a>
</li>
<li><a href="https://towardsdatascience.com/illustrated-guide-to-lstms-and-gru-s-a-step-by-step-explanation-44e9eb85bf21">
    https://towardsdatascience.com/illustrated-guide-to-lstms-and-gru-s-a-step-by-step-explanation-44e9eb85bf21</a>
</li>
<li><a href="https://medium.com/@hunterheidenreich/understanding-keras-dense-layers-2abadff9b990">
    https://medium.com/@hunterheidenreich/understanding-keras-dense-layers-2abadff9b990</a>
</li>
