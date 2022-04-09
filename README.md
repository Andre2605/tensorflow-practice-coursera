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
- C1_W4_ASSIGNMENT : Testing on the `Happy or Sad` dataset, in the form of
  emoticon images. Here is also given a way to stop testing the model when it
  reaches a certain value.
- C2_W1_ASSIGNMENT : Testing on the `CatsVSDogs` dataset. Here is the code to
  create a new directory after downloading the data set. The created model
  consists of 3 Convolution Layers.
- C2_W2_ASSIGNMENT : Testing on the `CatsVSDogs` dataset. Here there is
  additional code to avoid data overfitting.
- C2_W3_ASSIGNMENT : This assignment specifically uses Transfer Learning, and it
  is hoped that the prediction results will be better.
- C2_W4_ASSIGNMENT : In this exercise, you will have the opportunity to work on
  a multi-class classification problem. You will use the `Sign Language MNIST`
  dataset, which contains 28x28 hand-drawn images representing the 26 letters of
  the English alphabet. Here we are using Convolutional Layers.
- C3_W1_ASSIGNMENT : In this assignment we will work with a variation of the
  `BBC News Classification Dataset`, which contains 2225 examples of news
  articles with their respective categories (labels). This is the first time
  using Hardware.Tokenizer to create NLP models
- C3_W2_ASSIGNMENT : In this assignment we will use the same dataset which is
  `BBC News Classification Dataset`. This time we will not only work with the
  tokenization process but we will also create a classifier using special layers
  for text data such as Embedding and GlobalAveragePooling1D. The output
  prediction model for this assignment is quite good and is not overfitting.
- C3_W3_ASSIGNMENT : In this assignment we will explore how to reduce
  overfitting in NLP. We will use GRU, LSTM, and Conv to determine the best
  model to deal with the overfitting model.
- C3_W4_ASSIGNMENT : In this assignment, we will predict the words that appear
  after the sentence we give. The dataset is from `Shakespeare's sonnets`.
