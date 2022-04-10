**This is a description of the files listed in this folder. These files were
obtained from a private study provided by Bangkit through Coursera at TensorFlow
DeepLearning.AI Developers. This file includes lessons on TensorFlow from CNN,
RNN, NLP, and Image Recognition.**

- C1_W2 : Use the MNIST fashion library to create the model. There are several
  explanations about the functions used and their uses. In addition, there are
  some important notes at the end.
- C1_W3 : Improvise on computer vision accuracy using Convolutions Layer. There
  are several questions regarding the use of the convolutions layer.
- C2_W1 : Replaces the dataset with `DogvsCat` and makes model predictions with
  only 2 options. Here we can insert an image to check if it is a “Dog” or “Cat”
  image.
- C2_W2 : Introduction to the use of Data Augmentation as a precaution against
  overfitting models. This is done so that the prediction of the input can be
  better.
- C2_W3 : Introduction to Transfer Learning method. This method is used by
  taking the results of someone else's train model that has more data, and using
  it in our model.
- C2_W4 : Introduction to Multi-Class Classifier. The dataset is now not only
  binary but becomes 3 choices at the end of the prediction. Here we use the
  `Rock-Paper-Scissor` dataset. At the end of the prediction, the value that
  will be issued is the probability value for each of these choices, which if
  added up is 1.
- C3_W1 (LAB2) : Text data processing uses Natural Processing Language (NLP).
  Here we are given the information to convert the words into a sequence of
  numbers, and add padding (or a value of 0) for each sentence to make it the
  same length.
- C3_W1 (LAB3) : Use of hard.tokenizer on the sarcasm dataset.
- C3_W2 (LAB1) : Training a binary classifier with the IMDB Reviews Dataset. In
  this lab, we will be building a sentiment classification model to distinguish
  between positive and negative movie reviews.
- C3_W2 (LAB2) : Same as C3_W2, but uses the Sarcasm dataset to detect sarcasm
  words in the Headline News dataset. In terms of modeling, this time the lab
  uses `GlobalAveragePooling1D()`
- C3_W2 (LAB3) : In this lab, we saw how **subword** text encoding can be a
  robust technique to avoid out-of-vocabulary tokens. It can decode uncommon
  words it hasn't seen before even with a relatively small vocab size.
  Consequently, it results in longer token sequences when compared to full word
  tokenization.
- C3_W3 (LAB2) : This lab showed how you can build deep networks by stacking
  LSTM layers. LSTM adalah salah satu layer model pada NLP yang dapat melakukan
  train data secara keseluruhan atau dikenal sebagai Long-Short Term Memory.
  LSTM layer yang digunakan di lab ini adalah 2 Bidirectional LSTM.
- C3_W3 (LAB3) : In this lab, modeling is assisted by convolution layers and
  GlobalMaxPooling1D. This is another way of creating an NLP model.
- C3_W3 (LAB4) : In this lab, we are shown various ways to create NLP models.
  There are 4 comparison methods, namely Flatten, LSTM, GRU, and Conv1D.
- C3_W3 (LAB5) : Modeling from Sarcasm Dataset using Bidirectional LSTM.
- C3_W3 (LAB6) : Modeling from Sarcasm Dataset using Convolution Layer.
- C3_W4 (LAB1) : In this lab, we will look at techniques to prepare data and
  build models for text generation. We will train a neural network with lyrics
  from an Irish song then let it make a new song for us. The process is very
  similar to the ones we've been using in the previous weeks. Only minor
  modifications are needed.
- C3_W4 (LAB2) : In this lab, we also guess and produce word predictions from
  the input we input. The difference with the previous lab is that we will use
  more datasets, so the prediction results will be better and not repeated.
