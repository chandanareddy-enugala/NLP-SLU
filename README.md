# NLP-SLU
# NLP-SLU
Scratch approach:
Goal of the project is to find the whether tweet is a positive or negative tweet. Here we are using naive bayes alogirthm from scratch.
As part of preprocessing removed @user, urls, punctuations, extra spaces, emojies,for that Ive created functions. As it is non english language didnt removed any stop words.
For the implementation of naive bayes need to calculate the word count, created a function to calculate the word count of positive and negative tweets,(clearly commented each and every line of code)
After calculating the word count need to calculate the probability of occurance of each word in positive and negative tweets for that created word_probability function,naive bayes formuala is implemented in the predict function and verified the results using evaluate function.
Tranining accuracy: 79.7782%
Test accuarcy: 76.168%
