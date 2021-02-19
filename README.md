# doc2vec
Original doc2vec implementation by Tomas Mikolov from [this Google Groups discussion](https://groups.google.com/forum/#!msg/word2vec-toolkit/Q49FIrNOQRo/J6KG8mUj45sJ). Just keeping this here for backup.

## Mikolov's words
>I'm sending modified word2vec version that I wrote during the summer to help one intern with his project. It allows to train the sentence vectors, and the attached script runs it on IMDB. It also trains recurrent neural network language model to perform classification (another baseline, showing that generative models can work reasonably well for this task too, although the discriminative ones are obviously better). You can comment out this part of the script.

>This combined with SVM classifier with bag of bigram features actually achieves state of the art on the IMDB dataset (though this is not in the attached script).
