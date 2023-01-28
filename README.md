# Hi there!)

Let's try this time to create a neural network that determines the toxicity of the message, and when she learns, let's look at the features that it identified as important for the task

for starters, let's take a simple LSTM model, which was popular before the arrival of transformers

how it works:

![header](https://github.com/MariaSultanbekova/mental_health_analyzer/blob/main/images/lstm_sequence.png)


LSTM consists of a sequence of cells, each cell has a mechanism that allows you to remember important features and forget those that do not help in prediction
![header](https://github.com/MariaSultanbekova/mental_health_analyzer/blob/main/images/lstm.png)

and this model turns our sequence into a representative one, which helps to classify the text as toxic or non-toxic

In general, what is a neural network: 
- layers of lstm, which turn a sequence of words into a more informative one, 
- layers called dropout, they randomly reset the weights of neurons so that the network does not retrain, 
- and the final fully connected layers, called Dense - they are a classifier

train the network on 4 epochs (that is, let it look at all the data 4 times)

ok, our network has learned to discriminate toxicity with over 90% accuracy!!



now take one of the modern models of transformers










