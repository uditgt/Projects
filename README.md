# Projects
Some of my data science and machine learning projects using python packages such as Pandas, SciKit-Learn, Imblearn, Keras etc.

## [NLP & Keras - Classifying Tweets into various emotions using Bidirectional LSTM model](https://github.com/uditgt/Projects/blob/main/NLP%20%26%20Keras%20-%20Tweet%20Emotions/NLP%20%26%20Keras%20-%20Multi-class%20Tweet%20Emotions.ipynb)
* Multi-class classfication problem of identifying emotion (= joy, sadness, anger, fear, love, surprise) from a tweet's text. The dataset is part of the NLP library.
* After using preprocessing functions from TensorFlow to tokenize & pad the tweets, I create a neural network comprising vector embedding layer and **Bidirectional LSTM**  layers for sequence classification, to achieve a **test accuracy of 88%**.

## [Time-Series Forecasting](https://github.com/uditgt/TimeSeries)
* Forecasting Daily Bike Shares data, using different models - Prophet, SARIMAX, Holt-Winters, TBATS, Tensorflow structural time series. For this dataset, a combination of Prophet + XGBoost performs the best.
<p align="center">
  <img width="600" height="300" src="https://github.com/uditgt/TimeSeries/blob/main/assets/DailyBikeSharing%20-%20fitted.png">
</p>

## [Neural Network - MNIST digits dataset](https://github.com/uditgt/Projects/blob/main/NN%20-%20MNIST/NN%20-%20MNIST%20dataset.ipynb)
* Built a multi-class neural network, usign the preferred architecture which creates lower numerical precision error. The NN uses 'linear' activation in the last layer with the loss function directly using the 'logit' output created, in places of creating/ using softmax output. This does require one additional step at the time of prediction - that of converting logit output to probabilities to make them more interpretable. 
* Built a simple 3-layer neural network that achieves over 95% accuracy over the test set.
<p align="center">
  <img width="300" height="300" src="https://github.com/uditgt/Projects/blob/main/NN%20-%20MNIST/MNIST_test_op.png">
</p>


## [PCA - Relative Value Trading](https://github.com/uditgt/Projects/blob/main/PCA%20-%20Relative%20Value%20Trading/PCA%20-%20Relative%20Value%20Trading.ipynb)
* This is a PCA driven (unsupervised) model, which uses PCA to derive latent/state variables signifying structural movements to the interest rates at various term points along the yield curve. By using the top 3 PCA, we are in essense able to separate Noise from Signal. This can be used to build a relative value trading strategy - which is market neutral and earns alpha solely from the mispricing implied by mean-reverting noise. Or determine opportunate entry point in the market.
* Relative value changing over time for the 10yr term point
<p align="center">
  <img width="600" height="300" src="https://github.com/uditgt/Projects/blob/main/PCA%20-%20Relative%20Value%20Trading/rv_10yrterm.png">
</p>


## [Tutorial Notebooks](https://github.com/uditgt/Data_science_python)
* Notebooks showcasing concepts and use of various other ML models, including both supervised & unsupervised techniques:
	* Linear & Logistic regressions - including regularization, custom threshold tuning, and grid search
	* Support Vector Machines - including using pipelines
	* Decision Trees
	* XGBoost etc.

