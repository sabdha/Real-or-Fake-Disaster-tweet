# Real-or-Fake-Disaster-tweet
This model uses the implementation of BERT from the Tensorflow models repository to classify disaster tweets into real or fake ones. It uses 12 hidden layers (transformer blocks), a hidden size of 768, and 12 attention heads. This model has been pre-trained for English on the Wikipedia and Books Corpus. Inputs have been "uncased". The tokenization of input text is performed with the Full Tokenizer class from Tensorflow models. Parameters such as learning rate, epochs and batch size can be used for controlling the learning process. There are no dense or pooling layers added after last layer of BERT. SGD is used as optimizer since others have hard time while converging. The plot function plots Accuracy, Precision, Recall and F1 Score after every epoch alongside with training/validation loss curve. This helps to see which metric fluctuates most while training.
Tools and Libraries: BERT, Python, Scikitlearn, Tensor Flow, Matplotlib, seaborn
Cloud Services: Google Colab
Processing Unit: GPU   
  
My Score:![hippo](https://github.com/sabdha/Real-or-Fake-Disaster-tweet/blob/master/My_Score.png)

