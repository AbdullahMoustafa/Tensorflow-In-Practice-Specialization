# Natural language processing tutorials.
1st | 2nd | 3rd week
. Text classification as BBC news and sercastic.

4th week
. predict the most common word that comes next in the sequence
. create new sets of words using their embeddings!
_________________________________________________________________________________________________________________________________

1st week - Explore the BBC news archive
For this exercise get the BBC text archive.
1- tokenize the dataset,
2- removing common stopwords.
Passed 100%

2nd | 3rd  weeks - BBC news archive
This week you will build on last week’s exercise where you tokenized words from the BBC news reports dataset. This dataset contains articles that are classified into a number of different categories. See if you can design a neural network that can be trained on this dataset to accurately determine what words determine what category. Create the vecs.tsv and meta.tsv files and load them into 
the embedding projector:  https://projector.tensorflow.org/

4th week Generate/ predict word "poetry"

 you’ll take a corpus of Shakespeare sonnets, and use them to train a model. Then, see if that model can create poetry!
 poetry generator project

___________________________________________________________________________________
Sequence Modeling is the task of predicting what word/letter comes next. Unlike the FNN and CNN, in sequence modeling, the current output is dependent on the previous input and the length of the input is not fixed.

 how to do Natural Language processing with TensorFlow and Keras. You went from first principles -- basic Tokenization and Padding of text to produce data structures that could be used in a Neural Network.

You then learned about embeddings, and how words could be mapped to vectors, and words of similar semantics given vectors pointing in a similar direction, giving you a mathematical model for their meaning, which could then be fed into a deep neural network for classification.

From there you started learning about sequence models, and how they help deepen your understanding of sentiment in text by not just looking at words in isolation, but also how their meanings change when they qualify one another.

You wrapped up by taking everything you learned and using it to build a poetry generator!



