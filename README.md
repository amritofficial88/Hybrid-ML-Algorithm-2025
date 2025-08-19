
# Introduction

During my 4th semester I felt the need to delve into a bit of hands on machine learning but this time I wanted to develop something new from the ground up instead of doing another one of those typical machine learning projects that you see everybody doing.

So I reached out to one of my professors and she provided me with a csv file that I could try to classify.

So the target class of the csv file was either normal or abnormal and the aim was to train a Machine Learning Model that could classify a given gene into one of those two classes with a good accuracy.

My efforts in doing so were successful and the code for it is in the file _'CSV_Classification.ipynb'_

## Trying to Improvise

In my first attempt, all I did was apply __Deep Learning__ and that seemed to do the job but the goal was to develop a __Hybrid code that could utilize gradient descent/machine learning model along with a classifier and an optimizer__

All of this this in an attempt to see what the accuracy would be like and to see the levels of overfitting/underfitting if any.

Perhaps we could also overcome the limitation of most classification problem - Sample Size.

## The Outcome

The first thing I did to improve on my previous code was to include __K-cross validation__ and __mRMR(Minimum Redundancy Maximum Relevance)__ in all of my subsequent codes to improve accuracy and decrease chances of overfitting.

I applied K-cross validation in a different (better) way in my subsequent codes and hence I named those files as '_'-2; I applied this using several different libraries to see the accuracy that could be achieved and the results were interesting to say the least :P

_'mRMR_ABC_with_SVM_and_K_Cross_Validation_.ipynb'_ is the file where I tried to implement my best model along with an optimizer but its still a work in progress and you can expect me to update it every now and then.


## Acknowledgements

 - __[Nature-Inspired Computation and Swarm Intelligence by Xin-She Yang](https://www.elsevier.com/books/nature-inspired-computation-and-swarm-intelligence/yang/978-0-12-819714-1)__
 
 - __[mRMR-ABC: A Hybrid Gene Selection Algorithm for Cancer Classification Using Microarray Gene Expression Profiling](https://www.hindawi.com/journals/bmri/2015/604910/)__


