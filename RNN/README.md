## Recurrent Neural Network

I trained a RNN using the fast.ai library, which works on top of the famous PyTorch library, to classify texts between me and my girlfriend. For privacy I haven't uploaded the dataset but to be clear is a NX2 matrix with one column being the text and the other column identifies the person who sent the text. I, first, made a language model to teach the NN how we speak between us and the goal was to predict the next words of a sentence. Then, I trained the classifier model to classify, given a sentence, who it is from.
