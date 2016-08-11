# programming-language-classifier

This program takes snippets of code and tries to guess the programming language it's written in.  This classifier uses the pipeline linear regression library with count vectorizer.  

The classifier was trained with 14 different types of languages. The training seem to do quite well as our our score was about 99%.

When a single program was tested one from language – the classifier did quite well and got them all right as long as the program it was given had substantial link.  
In other words the bigger the program the more likelihood of guessing the correct programming language.

However when single lines of code was given the guesses were anywhere from 14% to as high as 64%. But it only averaged about 32%
