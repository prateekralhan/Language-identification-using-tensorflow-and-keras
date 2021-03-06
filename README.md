# Language-identification-using-tensorflow-and-keras

Language identification is one of the most common feature of every Social Network or Web application, this is commonly paired with Machine Translation to improve the user experience and content accesibility(a must have in the 2.0 society). The goal of the task is to detect the natural language of a given piece of text. What can you use it for? This is a foundation for other features such as Machine Translation (as mentioned before) and post/tweets/articles and documents analysis.
Language identification of short pieces of text from Wikipedia

In this notebook we will build a deep learning model able to detect the languages from short piceces of text (140 characters, old Tweets length) with high accuracy using neural networks. The task is commonly solved using hard-coded rules or NLP library, but we will attack the problem using Deep Learning.

I had gathered the raw dataset](https://floydhub.com/floydhub/datasets/language-identification/1) from https://dumps.wikimedia.org for 7 languages: Italian, Spanish and French which are considered to be in Latin language group, English and German have also common roots. Czech and Slovakian are extremely similar and are considered to be one of major challenged in the language recognition.
iso-code 	language 	example
en 	English 	Hello world!
fr 	French 	Bonjour tout le monde!
es 	Spanish 	Hola mundo!
it 	Italian 	Ciao mondo!
de 	German 	Hallo welt!
cz 	Czech 	Ahoj světe!
sk 	Slovakian 	Dobrý deň svet!

We will:

    Preprocess text data for NLP
    Build and train Deep Neural Network using Keras and Tensorflow
    Evaluate our model on the test set
    Run the model on your own text!



![lang](https://user-images.githubusercontent.com/29462447/44868408-5d9f3c00-aca8-11e8-83ab-356496670bfd.png)
