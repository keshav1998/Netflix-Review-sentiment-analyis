# Netflix Review sentiment analyis

Creating a **LSTM** neural network for predicting the sentiment of the review using a data set of 5000 positive and 5000 negative reviews.


# LSTM 
_Long Short-Term Memory_ networks — usually just called “_LSTMs_” — are a special kind of _RNN_, capable of learning long-term dependencies. _LSTMs_ don’t have a fundamentally different architecture from _RNNs_, but they incorporate additional components.
![](https://miro.medium.com/max/884/1*Cr6Qu331zIo17_QunwJGeQ.png)

The key to _LSTMs_ is the cell state **_C(t)_**, the horizontal line running through the top of the diagram. A cell state is an additional way to store memory, besides just only using the hidden state **_h(t)_**. However, **_C(t)_** makes it possible that _LSTMs_ can work with much longer sequences in opposite to vanilla _RNNs_.

## Data set used

The given model contains two text files, containing positive and negative reviews seperately, I would like to thank Artem Opperman for providing me the data set.



## Accuracy

Accuracy in predicting the positive review and negative reviews

|                |Accuracy                |
|----------------|-------------------------------|
|Positive        |`66.71`            |
|Negative        |`77.92`            |







```
