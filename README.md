# Projects
Some of my data science and machine learning projects using python packages such as Pandas, SciKit-Learn, Imblearn, Keras etc.

## [PCA - Relative Value Trading](https://github.com/uditgt/Projects/blob/main/PCA%20-%20Relative%20Value%20Trading/PCA%20-%20Relative%20Value%20Trading.ipynb)
* This is a PCA driven (unsupervised) model, which uses PCA to derive latent/state variables signifying structural movements to the interest rates at various term points along the yield curve. By using the top 3 PCA, we are in essense able to separate Noise from Signal. This can be used to build a relative value trading strategy - which is market neutral and earns alpha solely from the mispricing implied by mean-reverting noise. Or determine opportunate entry point in the market.

## [NLP & Keras - Classifying Tweets into various emotions using Bidirectional LSTM model](https://github.com/uditgt/Projects/blob/main/NLP%20%26%20Keras%20-%20Tweet%20Emotions/NLP%20%26%20Keras%20-%20Multi-class%20Tweet%20Emotions.ipynb)
* Multi-class classfication problem of identifying emotion (= joy, sadness, anger, fear, love, surprise) from a tweet's text. The dataset is part of the NLP library.
* After using preprocessing functions from TensorFlow to tokenize & pad the tweets, I create a neural network comprising vector embedding layer and **Bidirectional LSTM**  layers for sequence classification, to achieve a **test accuracy of 88%**.

## [Tutorial Notebooks](https://github.com/uditgt/Data_science_python)
* Notebooks showcasing concepts and use of various other ML models, including both supervised & unsupervised techniques:
	* Linear & Logistic regressions - including regularization, custom threshold tuning, and grid search
	* Support Vector Machines - including using pipelines
	* Decision Trees
	* XGBoost etc.

