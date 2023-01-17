# Machine Learning
Whenever we hear the word "Machine Learning", most of us immediately think of a robot performing crazy amount of tasks very efficiently or worse, Robots now replicating themselves and are planning to rule over Humans. Well, it's not always as fascinating of a Sci-Fi thriller as you think.
Machine Learning is already being used over a lot of places and you might not even know. It's been around for decades now.

## So, **What is Machine Learning?**
There are variety of definitions. These are the two most popular ones:
* According to Arthur Samuel, "Machine Learning is the field of study that gives the computer the ability to learn without being explicitly programmed.
* According to Tom Mitchell, "A computer program is said to learn from experience E with respect to some task T and some performance measure P, if it's performance on T, as measured by P, improves with experience E".
Arthur Samuel's definition provides a very general definition and it's easy to understand.

## But... Why?
But the question we need to ask is, "Why Machine Learning?". Why don't we write just programs?
Let's try to understand this with the help of an example. Suppose we want to build a tool for censoring bad words or negative comments. If we want to write a program for the same, then we need to know every possible bad word and every negative comment that a person can make which is very close to impossible. Even if we're somehow able to write a program, there are lot of workarounds like using Grawlix (a string of typographical symbols (such as %@$&\*!) used in place of an obscenity, especially in comic strips).
So, what we do instead is we feed in the previously known obscene words and negative comments to our Machine Learning Model. Now, that model tries to identify the features of a negative comment and if some another comment has all or some of those features then it can classify whether it's a negative comment or not.

## Types of Machine Learning
* **Supervised:** In Supervised Machine Learning, a set of data is provided along the with the desired output to train our model. We assisst the model by providing features along with the what it should output. Model then generalizes over the given dataset and tries to predict the output for new data.
* **Unsupervised:** In Unsupervised Machine Learning, no assisstance is provided from the programmer. Model is left to make guesses on their own mostly by clustering data with similar features.
* **Reinforcement:** In Reinforcement Machine Learning, model or agent interacts with the environement or try out some actions on their own. When they take an action they're either awarded or punished for their action. Based on the award or punishment, agent make choices so as to maximize the awards and minimize the punishment.

This is just an overview of different types of Machine Learning model. We'll understand them in detail later on!
