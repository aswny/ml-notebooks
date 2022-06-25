How does Embedding Layer work?
------------------------------
Embeddings are learned by adding a dense layer to our network that is much smaller than the width of our one hot encoding and the network learns weights to translate from the one hot encoding to a dense floating point representation that captures meaning. The nueral network is trained on an auxiliary task, like predict each word of a sentence given last 4 words, to learn the symantic/syntatic similarity of words.\
\
`Embedding` layer in Keras doesn't learn any embeddings then. Instead, it acts like a lookup table which finds the continuous representation of one-hot encoded vectors from an already pre-trained embedding matrix (?).

See also:
 - [Deep Learning, NLP, and Representations on Colah's blog](http://colah.github.io/posts/2014-07-NLP-RNNs-Representations/)
 - [RNN W2L05 : Learning word embeddings by Andrew Ng on Youtube](https://www.youtube.com/watch?v=xtPXjvwCt64)
 - [How does Keras 'Embedding' layer work? on Stackoverflow](https://stats.stackexchange.com/a/305032)
 - [How does Embedding Layer work? Issue #3110 on Keras' Github](https://github.com/keras-team/keras/issues/3110#issuecomment-345153450)
