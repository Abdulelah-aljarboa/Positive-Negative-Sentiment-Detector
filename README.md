# Positive-Negative-Sentiment-Detector
in this Project, we built a Positive/Negative detector using the gained knowledge from the natural language processing course.
we used Python as it is the go-to for AI and NLP and with it we used TensorFlow 

the model used was Long short-term memory (LSTM) which is a recurrent neural network (RNN)
aimed to deal with the vanishing gradient problem present in traditional RNNs. Its relative insensitivity
to gap length is its advantage over other RNNs, hidden Markov models, and other sequence learning methods.

in the notebook, you can find all the findings and graphs

I couldn't upload the tokenizer and the model files because they were too big for GitHub so
you need to run the code in your machine and train it, just run everything after making sure
the data set is in the right folder and referenced in the notebook.
the training would be faster if you have an Nvidia GPU and CUDA installed
see the links for more information : 

https://developer.nvidia.com/cuda-toolkit

https://www.anaconda.com/download

## Libraries:
- **Tensorflow:** is an open-source machine-learning framework that allows us to build machine
learning, deep learning, and neural networks.
- **Nltk:** an open-source library for natural language processing that provides an easy-to-use
interface for a wide range of NLP tasks such as tokenization, stemming, lemmatization, parsing,
and much more.
- **Numpy:** is a Python library used for working with arrays. It also has functions for working in the
domain of linear algebra, Fourier transform, and matrices. We used it to perform a wide variety
of mathematical operations on arrays and tuning.
- **Pandas:** is a Python library used for working with data sets. It has functions for analyzing,
cleaning, exploring, and manipulating data. We used it to read and clean the dataset.
- **Sklearn:** is an open-source data analysis library and the gold standard for Machine Learning in
the Python ecosystem. We used it to split the dataset, import the models, train, evaluate, and test
the models.
- **Re:** is a library that provides powerful regular expression features.
- **String:** is a built-in Python library that is used to process strings in Python.
- **Keras:** is a library that gives us the ability to create deep learning models.
- **Matplotlib:** is a comprehensive library for creating static, animated, and interactive visualizations
in Python. We used it to make the data visualization.
- **Seaborn:** is a Python data visualization library based on matplotlib it is used to create static,
animated, and interactive visualizations. We used it to make the data visualization.

## Data Set
The data set for the project was taken from this Kaggle link: https://www.kaggle.com/datasets/abedkhooli/arabic-100k-reviews
