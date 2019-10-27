# Text Generation using Recurrent Neural Networks (RNN)

### Goals

The goal of the project is to develop a recurrent neural network (RNN) capable of generating text.

### Dataset

The data source used to train the RNN is "A Tale of Two Cities" by Charles Dickens.
This was obtained from the Gutenberg Project, [here](https://www.gutenberg.org/files/98/98-0.txt).

Some 'heading' data was removed and is saved as [a text file](https://github.com/juschan/ml_textgen/a_tale_of_two_cities.txt) as part of this repo.

### References

We reference the coding examples to build our RNN.

- [Creating A Text Generator Using Recurrent Neural Network, by Trung Tran  ](https://chunml.github.io/ChunML.github.io/project/Creating-Text-Generator-Using-Recurrent-Neural-Network/)

- [Chun ML's Github repo on text generation](https://github.com/ChunML/text-generator)

- [The Unreasonable Effectiveness of Recurrent Neural Networks, by Andrej Karpathy](http://karpathy.github.io/2015/05/21/rnn-effectiveness/)

The example provided by Karpathy showed interesting examples of how character-by-character trained and generation allowed for varied examples including generation of C code, Shakespeare etc.

### Results

We observed the RNN model 'learning' various aspects of the text - from repetition of various words in the earlier epochss, to the understanding of punctuation and direct speech in later epochs. A possible next step is to see whether RNN is able to reproduce word associations after sufficient training epochs (ie. word2vec).  