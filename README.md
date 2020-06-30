# CTR_Testing

In this repository I test CTR of a dataset using Reinforcement Learning. It is also called Online Learning. This kind of learning algorithm is used to solve interacting problems where the data is observed upto 't' time to consider(/decide) which action to take at time 't+1'. It can also be used for AI to perform tasks such as walikng. The desired outcomes provide the AI with reward (generally 1) and undesired with punishment (gennerally 0), so that machine can learn thorugh trail & error.
<br>
Now for this repo I have to share a good news and a bad news with you. The bad news is in python (and R) I could not find any inbuilt library or package to impliment this algo. And the good news is, I know how to impliment this from basic, because it is very simple. I tired this with 2 different algorithm, one is UCB(Uppper Confidence Bound) and another one is Thompson Samlpling. the second one gave me a better accuracy, and I thinkthis algo is stable than UCB. So I provide its source code.
<br>
As always I'll provide a dataset(with more than 1000 observation) and source code for Python and R so that anyone can impliment it. You can reu it on your machine, I expect it to perform with a good score.
