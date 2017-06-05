# AWS-DeepLearning
A guide on how to set up an Amazon Web Services Instance (basically a remotely accessible GPU server for relatively cheap) to use Deep Learning **anywhere there is internet**.

Congratulations! You've decided to take the plunge into Deep Learning, and realise that the easiest way to use Deep Learning without going outright and buying a GPU is to set up a remote instance using Amazon Web Services that, for the price of $0.9 per hour (actually it ends up being more around $1.5 - $2.0 /h)

Note this guide borrows heavily from the folks over at [course.fast.ai](www.course.fast.ai), and includes some other elements I've found useful in using Deep Learning to apply to my own X-Ray analysis project with some members of the University of Auckland Data Science Club.

**Structure**: Creating the Instance — Configuring the Instance — Using the Instance

## Creating the Instance
The first step will be to go onto [Amazon Web Services](www.aws.amazon.com) and create an account. Jeremy Howard (from course.fast.ai) happens to have a mostly up-to-date and clearly illustrated [video](https://www.youtube.com/watch?v=8rjRfW4JM2I) on how to set up a p2 instance (p2 is the name of the GPU instance that Amazon currently offers to a select few).  I'll cover some of the inconsistencies I encountered when trying to use the video myself, as well as point out some of the changes that you'll have to take into account.
