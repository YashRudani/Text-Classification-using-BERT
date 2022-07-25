# Text-Classification-using-BERT
Email Classification into spam or not categories using BERT base model.

This was a task given to us as data science intern where we need to learn the basics of NLP and the first project we were asked to do in NLP was text clasification using BERT.
So here I have performed email classification into two classes(spam, ham) using BERT base model.

I did the classification using both sequential and functional model.
I got the accuracy of 91% in 10 epochs. By doing some hyper paramater tuning we can increase the accuracy.

Below is the Confusion Matrix:

![image](https://user-images.githubusercontent.com/68957471/180886793-6af9ee5e-ffb6-46b1-965f-20700424ea31.png)

Challenges I ran into:

The dataset was Highly imbalanced(85% not spam, 15% spam)
So for this time I removed the excessive part of dataset and ran the model on the remaining ones but we can do other process on imbalanced dataset as well.
